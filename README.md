# 🚀 Collaborative Git & GitHub Workflow Demonstration

This document summarizes the step-by-step collaborative Git and GitHub workflow completed as part of team repository management.
---
## 🛠️ Actions Taken

### 1. Accept Collaboration Invitation
- Accepted the email invitation to join the team repository as a official collaborator.

### 2. Clone Repository to Local Machine
- Cloned the remote repository to the local environment using:
  ```bash
  git clone <repository-url>
  cd <repository-folder>

### 3. Create and Switch to a Feature Branch
    git checkout -b user2Yohan2


### 4. Code Modification & Branch Switching Verification
    Made code updates within project files.

    Tested branch isolation by checking out back to main (git checkout main) to confirm the changes were hidden, then switched back to user2Yohan2 (git checkout user2Yohan2) to verify the modifications were preserved.

### 5. Clone Repository to Local Machine
Staged, committed, and pushed the new branch to the remote GitHub repository: 
git add .
git commit -m "say something"
git push origin main

### 6.Create a Pull Request (PR)
Created a Pull Request on GitHub comparing user2Yohan2 against main.
Kept the PR open (without merging) to allow team members to review the code.

### 7. Code Review & Merge Pull Request
 Reviewed teammates' Pull Requests on GitHub and submitted code review comments.
 Merged an approved Pull Request into the main branch upon code verification.
### 8. Clone Repository to Local Machine

 Switched back to the local main branch and pulled all latest changes merged by team members:

 git checkout main
 git pull origin main


## Summary: Successfully implemented the core end-to-end Git collaboration workflow, including repository cloning, feature branching, code review, PR merging, and local repository synchronization.
