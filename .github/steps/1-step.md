## Step 1: Create and prime your Copilot Space

In this step you will establish a Copilot Space and give it the minimum context it needs to act as a project management knowledge hub for OctoAcme.

### What you will do now

1. Create a new Copilot Space (this is the container for all subsequent conversations).
2. Add high‑level Instructions (purpose, where process docs live, why the Space exists).
3. Attach (add as a Source) your cloned exercise repository so Copilot can index `docs/` and issue templates.
4. Confirm the repository finishes indexing (appears in Sources).
5. Start a conversation in the Space to generate an issue that will track creating a README summarizing OctoAcme project management processes and linking every document in `docs/`.

### Copilot usage requirements (apply to every conversation here)

- Model: **GPT-4.1**
- For pull request draft generation: include the phrase `Using the github-coding-agent tool` in your prompt (PR drafts use the GHCP coding agent).
- Keep prompts explicit about desired outputs (issues, summaries, links).

### Readiness checklist before proceeding

- You can access https://github.com/copilot/spaces
- You have (or will fork) the exercise repository
- You know your GitHub handle to build the repository URL

Proceed to the activities below to execute each action.

### How does using Spaces affect my usage?
Questions you submit in a space count as Copilot Chat requests.

- If you're a Copilot Free user, this usage counts toward your monthly chat limit.
- If you use Spaces with a premium model, this usage counts toward your premium usage quota. Every question you submit to a premium model counts as one premium request, multiplied by the model's multiplier. For information about the multipliers applied to each model, see [Requests in GitHub Copilot](https://docs.github.com/en/copilot/managing-copilot/understanding-and-managing-copilot-usage/understanding-and-managing-requests-in-copilot#model-multipliers).

- [Use Copilot Spaces](https://docs.github.com/en/copilot/how-tos/provide-context/use-copilot-spaces/)

> [!IMPORTANT]
> In all conversations with Copilot Spaces, always be aware of the following:
> Use the **GPT-4.1** model
> Pull request drafts utilizes **GHCP coding agent**, therefore your prompt should contain `Using the github-coding-agent tool`

### ⌨️ Activity: Create your OctoAcme Project Management Hub Copilot Space

1. Navigate to GitHub Copilot Spaces https://github.com/copilot/spaces (ensure you have access to this feature)
1. Click **Create Space** button
1. Name your Space:
      > ```text
      > OctoAcme Project Management Hub
      > ```
1. Click **Save**

<img width="50%" height="50%" alt="Copilot Space Create Space" src="https://github.com/user-attachments/assets/0dcc4d78-1ee0-43cf-85c8-c1d0137aceb0" />

Add a description: 
   > ```text
   > Centralizing and democratizing project management knowledge for the OctoAcme organization
   > ```

<img width="50%" height="50%" alt="Copilot Spaces description" src="https://github.com/user-attachments/assets/5826b4bc-a40b-4705-b36a-66b234c2c07d" />

### ⌨️ Activity: Add instructions to your Copilot Space

- In your newly created Copilot Space, look for the **Instructions** button
- Add the following instructions to provide context about the repository and its purpose</br>

  <img width="50%" height="50%" alt="Copilot Spaces Instructions" src="https://github.com/user-attachments/assets/547cdbf9-9238-42af-a06b-7bb168207ec2" />
      <img width="50%" height="50%" alt="Copilot Spaces Instructions detail" src="https://github.com/user-attachments/assets/628b8534-5f14-48ba-89dc-16eec79617ea" />

- Click **Save**

   > ```markdown
   > ## Program process documents
   >
   > - Stored in `docs/`
   >
   > ### Purpose of this Copilot Space
   >
   > - Centralize scattered project management knowledge in Copilot Spaces
   > - Convert tacit tribal insights into searchable, versioned artifacts
   > - Give all team members equal access to processes, decisions, and rationale
   > - Connect a repository as a structured knowledge source
   > - Extract, refine, and standardize workflows collaboratively
   > - Feed validated improvements back into living documentation
   > - Accelerate onboarding and reduce single-person dependency risk
   > - Enable consistent, repeatable project execution
   >
   > ## Issue templates for program process documents
   >
   > - Stored in `.github/ISSUE_TEMPLATE/`
   > ```

### ⌨️ Activity: Add your cloned repository as a source repository to your Copilot Space

1. In your newly created Copilot Space, look for **Add sources** button
1. Add this exercise repository as a source:
   - Copy and paste your GitHub repository for this exercise called out below. 
   - You can also type the name in the search and it will come up as well or copy/paste the name below.
   
      > ```text
      > {{full_repo_name}}
      > ```
      
   - This gives Copilot access to the project management documentation and processes in the repository
1. Select the `docs` and the `.github/ISSUE_TEMPLATE` folders
1. Verify the repository appears in your sources list

      <img width="30%" height="30%" alt="Add sources" src="https://github.com/user-attachments/assets/05268c3f-5270-4e60-bc87-69fc27b1df72" />
      <img width="30%" height="30%" alt="Add sources repository" src="https://github.com/user-attachments/assets/d8b38b95-98ca-44a3-b7b4-d1ab4c12d348" />
      <img width="50%" height="50%" alt="Add sources repository files" src="https://github.com/user-attachments/assets/8340a69c-0d05-49df-92e7-bf929b57443b" />

### ⌨️ Activity: Create an issue in the repository for a README for OctoAcme Project Management Docs

> [!IMPORTANT]
> Use the **GPT-4.1** model for all conversations with Copilot Spaces.

- Open your Copilot Space you created above. https://github.com/copilot/spaces
- In the conversation interface prompt the following:

   > ![Static Badge](https://img.shields.io/badge/-Prompt-text?style=social&logo=github%20copilot)
   >
   > ```prompt
   > Create an issue in the repository {{full_repo_name}} for a README for OctoAcme Project Management Docs
   > that has links to all the docs in the docs folder.
   > - The README should also contain a brief summary of the project management processes used by OctoAcme.
   > - Make sure README, project management processes summary, and links are in the title of the issue.
   > ```

You can then add this issue to your repository by clicking the **Create** button.

<img width="50%" height="50%" alt="conversation to create an issue" src="https://github.com/user-attachments/assets/cc152bc6-d189-4143-8eea-719f70e43a6f" />

You can copy or open the link in a new tab to see the newly created issue

<img width="50%" height="50%" alt="cs-9" src="https://github.com/user-attachments/assets/a174f9cc-6c28-4698-a9b0-9e61e711413a" />

<details>
<summary>Having trouble? 🤷</summary><br/>

- Make sure you have access to GitHub Copilot Spaces (currently in beta/limited access)
- The repository should be publicly accessible for Copilot to index it
- If you can't access Copilot Spaces, you can continue by manually exploring the repository structure and documentation
- Repository indexing can take seconds to minutes depending on size

</details>
