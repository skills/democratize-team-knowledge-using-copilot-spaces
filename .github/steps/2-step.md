## Step 2: Explore & Summarize Project Management Processes and Create README

In this step you will:

- Explore the process docs in the docs/ folder (e.g., project-lifecycle.md, roles-responsibilities.md, communication-plan.md)
- Generate a 3–4 paragraph summary in your Copilot Space (workflows, roles, communication, quality)
- Use that summary to create/attach the existing issue about the README
- Create a pull request adding a README that links all process docs and includes the brief overview

### 📖 Theory: Attaching issues and assigning to the GitHub Copilot coding agent

While reading, note:

- End-to-end workflow stages and handoffs
- Defined roles/personas and responsibilities
- Decision / escalation points
- Communication cadences and channels
- Quality gates, reviews, and acceptance criteria

You will use the prompts below to:

1. Summarize the docs
2. Attach the prior issue
3. Generate a PR adding a docs/ README with links + overview

Proceed to the activities and run the provided prompts in your Copilot Space.

> [!IMPORTANT]
> Use the GPT-4.1 model for all conversations with Copilot Spaces.

### ⌨️ Activity: Explore the Project Management Docs

- Open your Copilot Space you created in Step 1. https://github.com/copilot/spaces
- Start a new conversation in the Copilot Space and prompt the following:
  
   > ![Static Badge](https://img.shields.io/badge/-Prompt-text?style=social&logo=github%20copilot)
   >
   > ```prompt
   > Summarize the project management processes docs from the `docs` folder in this repository.
   > ```

### ⌨️ Activity: Summarize Project Management Processes in your Copilot Space

Generate a summary should be 3-4 paragraphs covering the main processes OctoAcme uses for project management.

   > ![Static Badge](https://img.shields.io/badge/-Prompt-text?style=social&logo=github%20copilot)
   >
   > ```prompt
   > Create a 3-4 paragraph summary of the project management processes used by OctoAcme based on the documentation in the docs folder of this repository.
   > Focus on key workflows, personas/roles, communication strategies, and quality assurance practices.
   > ```

<!-- image place holder -->

### ⌨️ Activity: Attach an issue and create a Pull Request

- In this activity we will attach the issue you created in step 1 for adding a README
- Use the previous summary we created and create a pull request to address the issue
- This will assign the issue to the coding agent to create a pull request with the README file in the `docs/` folder
- Attach the issue titled "README and project management processes summary and links" to this conversation that we created in step 1.

> [!IMPORTANT]
> In all conversations with Copilot Spaces, always be aware of the following:
> Use the GPT-4.1 model
> Pull request drafts utilizes GHCP coding agent, therefore your prompt should contain `Using the github-copilot-agent tool`

<!-- image place holder -->

   > ![Static Badge](https://img.shields.io/badge/-Prompt-text?style=social&logo=github%20copilot)
   >
   > ```prompt
   > - Using the github-copilot-agent tool create a pull request that adds a README file for OctoAcme Project Management Docs that has links to all the docs in the docs folder.
   > - The README should also contain a brief overview of the project management processes used by OctoAcme based on the summary we created earlier.
   > ```

<details>
<summary>Having trouble? 🤷</summary><br/>

- Look for files like `project-lifecycle.md`, `roles-responsibilities.md`, `communication-plan.md` in the docs folder
- Focus on understanding the overall workflow rather than memorizing every detail
- If using Copilot, try asking: "Summarize the project management processes in the docs folder"

</details>

