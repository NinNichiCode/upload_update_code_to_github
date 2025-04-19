# 🛠️ Git Upload & Update Automation Scripts

This repository provides two handy shell scripts to help you **upload** and **update** your local code projects to GitHub automatically and more easily using Git Bash.

---

##  Scripts Included

### 1. `upload_git`
- Initialize a Git repository in the current folder (if not already)
- Configure Git (optional)
- Add all files and make an initial commit
- Push the project to a **new GitHub repository** using the GitHub API

 You’ll need a **GitHub personal access token** to create repositories via API.

### 2. `update_git`
- Automatically stage all changes in your project
- Commit with a message (optional)
- Push to the `main` branch

---

## Requirements

- Windows OS
- Git Bash with PowerShell access
- Git installed and configured
- GitHub account
- (Optional for upload_git) GitHub Personal Access Token with `repo` permission

---

##  How to Use
###  `upload_git`
- Open git bash and cd /path/to/your/project
- Type: upload_git <link_github_repo_URL>

###  `update_git`
Use it to update an **existing** project you've already pushed to GitHub:
cd /path/to/your/project
update_git "Fix: improved image parser"
