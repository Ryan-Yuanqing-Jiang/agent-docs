## The Job
I have designed an agent skill here: https://github.com/Ryan-Yuanqing-Jiang/ryse-agent-skills/tree/main/consultancy-pdf
It's working well, but non-technical users would don't have access to agent can't easily use it, creating a gap in reaching our users. 
I want you to build a webUI wrapper around an agent that uses this skill.
### What the skill does
It converts markdown, Microsoft Office documents, HTML, or plain text into beautifully designed, print-ready PDF documents with consistent visual branding, typography, and colour schemes.

**IMPORTANT**: You need to read the entire skill and its reference files very carefully and fully understand what it does and how. Start with the `README.md`
## Requirements
### The key requirement
I want this to be an agentic solution: 
1. To build a simplistic agent, with a simplistic and easy-to-use webUI wrapped around it so that I can share with my linkedin audience and they will want to try this without accessing their own agent.
2. The application should be oriented around the agent and the skill (with all the files and references it comes with), with a layer of UX to orchestrate the UX and flow.

Here's a list of requirements and UX flows that I want to add, leverage the existing skill for references and functionalities:
1. A simplistic UI, fast, responsive.
2. Users can use the UI to select and give inputs that the skill could ingest:
	1. select a list of predefined design themes from the themes defined in the skill. Or Users can enter an company URL which agent will read and try to match the design theme to the branding.
	2. Layout parameters — page count and paper size
	3. Header variables — eyebrow, title
	4. Footer variables — left and right with resolution chains
	5. (These variables are optional, when not provided they should be derived from the document provided by the user)
3. Users can upload .md, .doc, .docx files. Or they could use a simple markdown editor in the webUI to enter content.
4. Users can choose whether the ai agent will rewrite their content for better layout or readability or keep it as it is. 
5. At the end users can preview and then download a PDF that's well-designed and structured.
6. Users can give feedback to alter the design, which will trigger regeneration and preview.

Other non-functional requirements:
- Download and use the skill where possible. 
- Make sure the agent's runtime environment has all the dependencies that it needs to run the skill.
- Write great system prompts to make sure the agent uses the skill efficiently, works well with the UI and unexpected but valid user instructions, to deliver the final result.
- Keep it simple. The UI simple, clean, accessibly, the system clean, simple, easy to navigate.
- Use https://github.com/huggingface/smolagents for agent framework when building the agent.
- I will use OpenRouter API for this, keep it safe and add it as an env.
- The UI should be intuitively designed, with instructions so users don't have to learn and can use it straight away.
- Use sub-agents to research the skill and the agent framework to have a thorough understanding without blowing your context window.
- I want to be able to run the app with 1 command using `docker-compose` (instead of a series of complex commands).
