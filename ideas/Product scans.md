**Product Requirement Document (PRD)**

**1. Problem Statement**
A friend of mine is trying to execute an idea to help a whiskey option seller who is having trouble entering their data.

**2. Target Users & Use Cases**
- **Target Users:** Whiskey option sellers facing data entry issues.
- **Use Cases:**
  - Scan whiskey bottles using a mobile phone and match them against a database.
  - Verify if the product is already in the database (stock verification).
  - If the product is not in the database, create a new database entry.

**3. Goals & Non-Goals**
- **Goals:**
  - Help the whiskey option seller save the main effort around entering product data.
  - Provide a system that automates the data entry process using image recognition.

**4. Key Features / Requirements (Bulleted, Concise)**
- **Image Recognition System:** Scan whiskey bottles and match them against a database.
- **Database Entry Verification:**
  - Verify if the product is already in the database (stock verification).
  - If the product is not in the database, create a new database entry.

**5. UX / Workflow Notes (High Level)**
- **User Experience:** The system should be intuitive for users who are not familiar with image recognition technology.
- **Workflow:** The workflow involves scanning a whiskey bottle with a phone (using web app instead of having to install an app), using image recognition to extract information, then match it against a database, and then either creating (if no existing data is found) or verifying a database entry based on the match.

Now I want to create a super simple but functional end-to-end demo of this high-level user flow, so that I can just send it to the whiskey shop owner and amaze him.

Requirements:
- Web-based solution:
	- There needs to be a web-based client that can be opened on a phone to spin up a camera and start recording and scanning bottles, after which results can be shown on the phone as well as in the portal, in real time. 
	- There also needs to be a web-based dashboard or portal which displays existing and newly created data entries.
- MVP demo: this is a e2e functional demo, so it doesn't have to be a super complex system, but needs to be super easy to use, with great experience, to deliver the proof of concept and wow our prospect. **I want to spend the least effort and complexity, to get this e2e POC working and win this contract**.
- Demo data: there needs to be some demo data to get users started.
- AI-based: I want to use a LLM with strong visual comprehension and extraction capability from openrouter.

Now help me create an execution plan.