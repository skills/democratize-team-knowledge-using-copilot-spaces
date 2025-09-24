## Step 3: Add a new issue based on an issue template and pull requests for project management process improvements

In this step you will add content based on your analysis by:

1. Creating an issue and attaching an issue template (expanding personas/roles in project management processes).
2. Creating and attaching a pull request that implements the improvements (using the github-copilot-agent tool) by updating or adding documentation/templates.

These two activities embody an iterative improvement loop: identify a gap (issue), then implement and document the change (pull request), keeping traceability inside the Copilot Space conversation.

### 📖 Theory: Iterative Process Improvement

Effective process evolution follows a lightweight cycle:

- Review current documentation and execution reality
- Identify gaps, ambiguities, or missing personas/roles
- Record the need as a structured issue (problem statement + rationale)
- Design and implement improvements (docs, templates, checklists) in a PR
- Communicate changes via clear descriptions and linked artifacts
- Measure adoption and revisit as new insights emerge

> [!IMPORTANT]
> Use the GPT-4.1 model for all conversations with Copilot Spaces.

### ⌨️ Activity: Attach an issue template and create an issue for process improvements

- Attach the issue template `github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` to this new Copilot Space conversation.

<! image place holder >

_Use the following prompt in a new Copilot Space conversation:_

   > ![Static Badge](https://img.shields.io/badge/-Prompt-text?style=social&logo=github%20copilot)
   >
   > ```prompt
   > Identify potential new personas/roles that could be added to the project management processes documentation to enhance clarity and accountability.
   > - Create an issue titled "Adding more personas and roles to the project management processes" that outlines the need to expand the defined roles and responsibilities in the project management documentation.
   > - Make sure the new roles/personas have descriptions of their responsibilities and how they interact with existing roles.
   > - The issue should detail why this is important, potential personas to add, and how it will improve project outcomes.
   > ```

### ⌨️ Activity: Attach an issue and create a Pull Request

In the same Copilot Space conversation do the following:

- Attach the issue titled "Adding more personas and roles to project management processes" to this conversation that we created in previous activity.

_Use the following prompt in the current Copilot Space conversation:_

> [!IMPORTANT]
> In all conversations with Copilot Spaces, always be aware of the following:
> Use the GPT-4.1 model
> Pull request drafts utilizes GHCP coding agent, therefore your prompt should contain `Using the github-copilot-agent tool`

<! image place holder >

   > ![Static Badge](https://img.shields.io/badge/-Prompt-text?style=social&logo=github%20copilot)
   >
   > ```prompt
   > - Using the github-copilot-agent tool create a pull request that implements process improvements based on the analysis we did earlier.
   > - The improvements should address gaps or inefficiencies identified in the project management documentation.
   > - The pull request should include updates to existing docs or new templates/checklists as needed.
   > ```

<details>
<summary>Having trouble? 🤷</summary><br/>

- Focus on the most impactful improvements identified in your analysis
- Consider adding templates, checklists, or clarifying existing processes
- Common improvements include: role clarification, communication protocols, decision-making frameworks
- Even small improvements like adding examples or clarifying steps can be valuable

</details>
