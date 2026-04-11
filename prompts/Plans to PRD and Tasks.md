
Now with the product strategy, system architecture and module design and execution plan, use /ralph-tui-prd to
generate PRDs for execution. Given the system complexity, it's okay to generate several PRDs to reflect the
phases of execution and the modular design. Assume the PRDs will be executed sequentially, so make sure you
structure it correctly according to the module designs, and make it explicit in the PRDs of which module it's
building, and their dependencies.
After the PRDs are generated then:
1. Use /ralph-tui-create-json for each generated PRDs to generate the task list.

---

/skill-creator I am a product manager turned consultant.

I am trying to win work from prospects from a range of industries and sectors, and I need to build demo apps (most likely to have AI and agentic elements when possible) to showcase my capabilities of meeting their specific needs.

What I usually hear from them is usually a set of loosely structured stories and complaints about pain points in their operations that's hurting their revenue or bottom line.

I want to an adaptive skill that allows an agent to take in a user pain-point (or a complain, feature request, user story), try understand the user pain, and proactive research about the particular pain point to find any inspirations of competitors and status quo solutions, and creatively generate a PRD for coding agents to execute.

Outcome:
- A well formatted PRD in markdown.
- A set of user acceptance test cases written in a markdown file, covering the entire user journey, so the QA agent can run through the test cases and ensure the solution works as expected.

Requirements:
- The PRD should focus on building an MVP scope of a solution that focuses on demonstrating "how a particular problem (or a set of problems) could be solved by our consultancy end to end", instead of trying to build a complex production solution. So the "depth of the stack" and system complexity should be kept low, but the coverage wide enough to **cover the entire user journey to demonstrate how it solves a complete set of user problems to deliver value.**
- Ensure the solution have a good UX and UI design, focused on the demo of core values and user journey, instead of over investing in things like configs, security, and scalability. Use commonly used frameworks and tools when possible.
- When possible and applicable, try to design an agentic solution where AI agent is responsible of reasoning, deciding and executing tasks for better result than status quo. That said, when AI's introduction is an overkill, don't force it into the solution (i.e. users don't need AI to do simple and fixed data manipulation.)
- This is a PRD, not a technical plan. So leave the hard technical details out of the scope, that's the scope of the coding agent.
- The PRD should user focused, including a well defined user journey and exact steps of how the targeted personas will use the solution to complete the JBTDs and get value, as well as the user-level success criteria.
- Aim for the 'aha' moment of the demo MVP, think of how you will use this demo to impress the client, convince that our tech and AI can solve their problems and eventually close deals.

----



Technical planner:

- Ensure the solution has enough and well-structured demo data 