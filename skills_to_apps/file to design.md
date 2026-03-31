I have designed an agent skill here: https://github.com/Ryan-Yuanqing-Jiang/ryse-agent-skills/tree/main/consultancy-pdf
A Claude Code skill that converts markdown, HTML, or plain text into beautifully designed, print-ready PDF documents with consistent visual branding, typography, and colour schemes.

Now I want to turn this into a usable webapp, with simple UI, but very functional, and easily usable, so I can share with my linkedin audience and they will want to try this.

Here's a list of requirements and UX flows that I want to add, leverage the existing skill for references and functionalities:
1. A simplistic UI, fast, responsive.
2. Users can select a list of predefined design themes. Or Users can enter an company URL which agent will read and try to match the design theme to the branding. 
3. Users can upload .md, .doc, .docx files. Or they could use a simple markdown editor in the webUI to enter content.
4. Users can choose whether the ai agent will rewrite their content for better layout or readability or keep it as it is.
5. Users can include images in the markdown using the link syntax, or in .doc/.docx, the agent will be able to put this into the right layout (i.e. if it's a logo, it'd be in the header).
6. At the end users can preview and then download a PDF that's well-designed and structured. 
7. Users can give feedback to alter the design, which will trigger regeneration and preview. 

Other non-functional requirements:
- keep it simple. The UI simple, clean, accessibly, the system clean, simple, easy to navigate. Use https://github.com/huggingface/smolagents for agent framework if you need to.
- This is a demo app, not something with a price tag, so I want to invest the least amount of resources, code, to get the best reaction from my audience.
- I will use OpenRouter API for this, keep it safe and add it as an env.
- The UI should be intuitively designed, with instructions so users don't have to learn and can use it straight away. 

Before you start:
- Ask me if you have clarifying questions to make sure the job is done right.
- Do you think this is an app to one-short? If not, how would you break it down to plan and tasks?