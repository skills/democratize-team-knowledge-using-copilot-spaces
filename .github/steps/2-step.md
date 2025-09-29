## Step 2: Explore & summarize project management processes and create a README

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
> Use the **GPT-4.1** model for all conversations with Copilot Spaces.

### ⌨️ Activity: Explore the project management process docs and Summarize in your Copilot Space

- Generate a summary. Should be 3-4 paragraphs covering the main processes OctoAcme uses for project management.
- Open your Copilot Space you created in the previous step. https://github.com/copilot/spaces or by clicking the name <img width="50%" height="50%" alt="link to Copilot Space" src="https://github.com/user-attachments/assets/13534299-c764-4d20-9760-88bd7dac7cff" />
- Start a new conversation in the Copilot Space and prompt the following:
<img width="70%" height="70%" alt="Copilot Space conversation OctoAcme project management process docs summary" src="https://github.com/user-attachments/assets/342605be-4b36-48b2-b54f-18ae85f16bb8" />

   > ![Static Badge](https://img.shields.io/badge/-Prompt-text?style=social&logo=github%20copilot)
   >
   > ```prompt
   > - Create a 3-4 paragraph summary of the project management processes used by OctoAcme
   >   based on the documentation in the docs folder of this repository.
   > - Focus on key workflows, personas/roles, communication strategies, and quality assurance practices.
   > ```

<img width="50%" height="50%" alt="Copilot response with the summary" src="https://github.com/user-attachments/assets/26a54642-a14b-498d-a195-d1ffd45e5679" />

### ⌨️ Activity: Attach an issue and create a pull request for the Copilot coding agent

- In this activity we will attach the issue you created in the previous step for adding a README
- Use the previous summary we created and create a pull request to address the issue
- This will assign the issue to the coding agent to create a pull request with the README file in the `docs/` folder
- Copy and paste the url for the issue that we created in the previous step.</br>
  Issues: [https://github.com/{{full_repo_name}}/issues](https://github.com/{{full_repo_name}}/issues) </br>

> [!NOTE]
> - Make sure the issue below matches the issue you want to attach
> - Hit **\<SHIFT\> + \<ENTER\>** so you don't start Copilot working on the conversation
  
  >```text
  > @{{full_repo_name}}/issues/2
  > ```
  
> [!IMPORTANT]
> - In all conversations with Copilot Spaces, always be aware of the following:
> - Use the **GPT-4.1** model
> - Pull request drafts utilizes GHCP coding agent, therefore your prompt should contain `Using the github-coding-agent tool`
> - There is a known issue for pull requests that you may get following response.</br>
> - There is a chance when you get this error you the coding agent may not create pull request
> - If 5 minutes passes by and the pull request is not created
> - Please open a **new Copilot Space conversation** and try this activity again

<img width="50%" height="50%" alt="pull request error" src="https://github.com/user-attachments/assets/f1c44603-2b01-4c33-b910-253ce84edbc6" />

<img width="80%" height="80%" alt="repository issue and pull request creation" src="https://github.com/user-attachments/assets/aab825e3-53bb-40e7-adbd-efbae520293d" /> </br>

   > ![Static Badge](https://img.shields.io/badge/-Prompt-text?style=social&logo=github%20copilot)
   >
   > ```prompt
   > - Using the github-coding-agent tool create a pull request based on the attached issue.
   > - The README should also contain a brief overview of the project management processes
   >   used by OctoAcme based on the summary we just created.
   > - The README should be in the `docs/` folder
   > - Add this pull request to the attached issue.
   > - Add {{login}} as a reviewer
   > ```

Select **Allow**

<img width="50%" height="50%" alt="Copilot coding agent allow" src="https://github.com/user-attachments/assets/b0c92c04-d12b-4c5e-b682-33643b90ee11" />

You should have gotten a notification that Copilot coding agent is working on your pull request.

Go to your repository and click **Pull requests** and you should see something similar to the following:

<img width="70%" height="70%" alt="pull requests" src="https://github.com/user-attachments/assets/d30685c3-046b-4c6e-8254-4bcb8aa959b5" />

- It takes approximately 5 to 15 minutes for the coding agent to work on the issue.
- If you would like to see how the Copilot coding agent is progressing you can click the **View session** button and interact in the session.
- Once you are satisfied with the content **Submit review**, leave a comment (optional), click **Approve**, then **Submit review**
<img width="70%" height="70%" alt="Add review" src="https://github.com/user-attachments/assets/ea460dc3-a86d-467b-8469-bd9244b915ea" />

<img width="50%" height="50%" alt="Submit review" src="https://github.com/user-attachments/assets/15042891-c8fa-4acc-a25d-c588cf6a3ffe" />
</br>
- At the bottom select **Ready for review** and then **Merge pull request** and **Confirm merge**
</br>
<img width="50%" height="50%" alt="Ready for review" src="https://github.com/user-attachments/assets/2348378d-a597-404f-827d-4003d79055c0" />
<img width="50%" height="50%" alt="Merge pull request" src="https://github.com/user-attachments/assets/fda15799-a123-4e6a-b32a-c7ec44db3418" />

<details>
<summary>Having trouble? 🤷</summary><br/>

- Make sure issue is attached by pasting the link to the issue </br>
  Example: `{{full_repo_name}}/issues/2`
- Make sure you have merge permissions to the repository

</details>
