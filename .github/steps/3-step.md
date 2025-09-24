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

- Attach the issue template `github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` to this new Copilot Space conversation.z

<img width="50%" height="50%" alt="Attach" src="https://github.com/user-attachments/assets/2dd82666-4fd0-48fd-8d19-aea82a150e08" />
<img width="50%" height="50%" alt="Attach files" src="https://github.com/user-attachments/assets/729d1c78-9665-4514-8297-c37111f48601" />
<img width="50%" height="50%" alt="Attach issue template" src="https://github.com/user-attachments/assets/04ef6f5b-2fba-4108-9d7d-b18e62a029bb" />
<img width="60%" height="60%" alt="Attach issue template conversation" src="https://github.com/user-attachments/assets/400e0079-7af6-49ea-91fe-377df4395666" />

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
<img width="50%" height="50%" alt="personas/roles issue draft" src="https://github.com/user-attachments/assets/3fe2a81b-01e0-4e51-8501-d6c206b0b49d" />
<img width="50%" height="50%" alt="personas/roles issue created" src="https://github.com/user-attachments/assets/e3966030-1511-4c4f-846f-5a1e90702403" />

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

<img width="50%" height="50%" alt="pull request error" src="https://github.com/user-attachments/assets/284b3fd1-7079-4bfd-90b9-1d8245b12cbc" />

   > ![Static Badge](https://img.shields.io/badge/-Prompt-text?style=social&logo=github%20copilot)
   >
   > ```prompt
   > - Using the github-copilot-agent tool create a pull request that implements process improvements based on the analysis we did earlier.
   > - The improvements should address gaps or inefficiencies identified in the project management documentation.
   > - The pull request should include updates to existing docs or new templates/checklists as needed.
   > ```
<img width="50%" height="50%" alt="repository issue and pull request creation" src="https://github.com/user-attachments/assets/e8c70cea-42a3-44a4-9dc5-a804319b253a" />

Select **Allow**

<img width="50%" height="50%" alt="Copilot coding agent allow" src="https://github.com/user-attachments/assets/15e9b2c1-39e3-40f2-b90f-3cfdb2bb2604" />

You should have gotten a notification that Copilot coding agent is working on your pull request.

Go to your repository and click **Pull requests** and you should see something similar to the following:

<img width="70%" height="70%" alt="pull requests" src="https://github.com/user-attachments/assets/3be45204-0a27-4ce2-ad22-7cde9c9abb03" />

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
