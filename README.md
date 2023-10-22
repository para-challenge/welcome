# Welcome to the challenge task

Task goal is to verify your practice knowledge for the most common DevOps tools.
You will receive access to exam repository. The result must be send using GitHub Pull Request.
Please be aware that you have just **60 minutes** to finish task. 
Clock is start once you obtain access to the exam repository.

# Prerequisites

- You need to have GitHub account - use an existing one or create a new one;
- Setup command line authentication with GitHub account
- Install on your local computer:
    - Docker engine (verify command: `docker version` and `docker ps`);
    - Helm client (verify command: `helm version`);
    - Terraform client (verify command: `terraform version`);

## General acceptance criteria

- Each task should be in separated Pull Request
- Each Pull request should contain only one commit and resolve only specific task
- You should rebase your branch based on the `main` branch

## Access to exam repository

1. Login to GitHub.com page.
1. On this repository, click **Actions**.
2. In the left sidebar, click the workflow **Start challenge**.
3. Above the list of workflow runs, click the Run workflow button.
4. Fill the form:
   - Use workflow from: leave "Branch main"
   - Secret Token: Provide token that you received 
   - Check "I read `Prerequisites` and `Acceptance Criteria`, understand them and I'm ready to do start."

Good luck!