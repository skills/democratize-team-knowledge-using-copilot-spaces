## Step 3: Add a new issue based on an issue template and a pull request for project management processes improvements

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
> Use the **GPT-4.1** model for all conversations with Copilot Spaces.

### ⌨️ Activity: Attach an issue template and create an issue for process improvements

_Use the following prompt in a new Copilot Space conversation:_

- Attach the issue template `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` to this new Copilot Space conversation.

<img width="50%" height="50%" alt="Attach" src="https://github.com/user-attachments/assets/2a447ff9-76d7-462f-9292-4663c8dc0fc9" />

<img width="50%" height="50%" alt="Attach files" src="https://github.com/user-attachments/assets/6ac6e33d-b333-424f-b431-e3feb7022b841" />

<img width="50%" height="50%" alt="Attach issue template" src="https://github.com/user-attachments/assets/c02537ad-173e-430d-9e24-6a95763b8f30" />

<img width="60%" height="60%" alt="Attach issue template conversation" src="https://github.com/user-attachments/assets/5256e137-286d-4479-89bc-fc745021d4b1" />

   > ![Static Badge](https://img.shields.io/badge/-Prompt-text?style=social&logo=github%20copilot)
   >
   > ```prompt
   > Use the attached issue template
   > - Identify potential new personas/roles that could be added to the project management processes documentation
   >   to enhance clarity and accountability.
   > - Create an issue titled "Adding more personas and roles to the project management processes" 
   >    that outlines the need to expand the defined roles and responsibilities in the project management documentation.
   > - Make sure the new roles/personas have descriptions of their responsibilities and how they interact with existing roles.
   > - The issue should detail why this is important, potential personas to add, and how it will improve project outcomes.
   > ```
<img width="50%" height="50%" alt="personas/roles issue draft" src="https://github.com/user-attachments/assets/b563450e-8304-426c-a9b2-70e460c8db84" />

<img width="50%" height="50%" alt="personas/roles issue created" src="https://github.com/user-attachments/assets/c6e3f128-6254-4f0c-a1a6-f31b9d8b56b2" />

### ⌨️ Activity: Attach an issue and create a Pull Request

_Use the following prompt in the current Copilot Space conversation:_

In the same Copilot Space conversation do the following:

- In this activity we will attach the issue you created in the previous activity 
- This will assign the issue to the coding agent to create a pull request with an update to our personas/roles document in the `docs/` folder
- Copy and paste the url for the issue that we created in the previous activity. ex. https://github.com/octocat/skills-democratize-tribal-knowledge-using-copilot-spaces/issues/3

> [!IMPORTANT]
> - In all conversations with Copilot Spaces, always be aware of the following:
> - Use the **GPT-4.1** model
> - Pull request drafts utilizes GHCP coding agent, therefore your prompt should contain `Using the github-copilot-agent tool`
> - There is a known issue for pull requests that you may get following response

<img width="50%" height="50%" alt="pull request error" src="https://github.com/user-attachments/assets/45bffd57-4608-4458-9282-4ae78578a2fe" />

   > ![Static Badge](https://img.shields.io/badge/-Prompt-text?style=social&logo=github%20copilot)
   >
   > ```prompt
   > - Using the github-copilot-agent tool create a pull request that implements process improvements
   >   based on the analysis we did earlier.
   > - The improvements should address gaps or inefficiencies identified in the project management documentation.
   > - The pull request should include updates to existing docs or new templates/checklists as needed.
   > ```
<img width="50%" height="50%" alt="repository issue and pull request creation" src="https://github.com/user-attachments/assets/67086db2-0572-45cc-aed0-408c99656cc7" />

Select **Allow**

<img width="50%" height="50%" alt="Copilot coding agent allow" src="https://github.com/user-attachments/assets/b0c92c04-d12b-4c5e-b682-33643b90ee11" />

You should have gotten a notification that Copilot coding agent is working on your pull request.

Go to your repository and click **Pull requests** and you should see something similar to the following:

<img width="70%" height="70%" alt="pull requests" src="https://github.com/user-attachments/assets/d30685c3-046b-4c6e-8254-4bcb8aa959b5" />

- It takes approximately 5 to 15 minutes for the coding agent to work on the issue and the **[WIP]** will be removed from the title.
- If you would like to see how the Copilot coding agent is progressing you can click the **View session** button and interact in the session.
- Once you are satisfied with the content **Submit review**, leave a comment (optional), click **Approve**, then **Submit review**
- At the bottom select **Ready for review** and then **Merge pull request** and **Confirm merge**

<details>
<summary>Having trouble? 🤷</summary><br/>

- Focus on the most impactful improvements identified in your analysis
- Consider adding templates, checklists, or clarifying existing processes
- Common improvements include: role clarification, communication protocols, decision-making frameworks
- Even small improvements like adding examples or clarifying steps can be valuable

</details>
