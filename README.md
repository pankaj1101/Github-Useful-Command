# Github-Useful-Command

This repository contains a collection of useful Git commands that help with day-to-day Git operations. Whether you're cloning a repo, checking the status, managing remotes, or handling branches, this guide will help you with common tasks.

---

## To Clone the Repository

To clone the repository to your local machine:
```bash
git clone repo_url
```

---

## Check Status

To check the status of your repository:
```bash
git status
```

---

## To Add Files/Folders

To add files or folders to staging:
- Add all files:
  ```bash
  git add .
  ```
- Add a single file:
  ```bash
  git add filename
  ```

---

## Commit Changes

To commit your changes with a message:
```bash
git commit -m "initial commit"
```

---

## To Push the Branch

To push your changes to the remote repository:
```bash
git push
```

---

## Git Push Using GitHub Token

To push changes using your GitHub token (for secure access):
```bash
git push https://<Username>:<GithubToken>@github.com/repo-name.git
```

---

## List All Remote Repositories

To list all remote repositories that your local Git project is connected to — along with their URLs:
```bash
git remote -v
```

---

## Add a Remote Repository

To add a new remote URL to your local Git configuration:
```bash
git remote add origin https://repo-url.git
```

---

## Change Remote Repository URL

To change the URL of a specified remote repository:
```bash
git remote set-url origin https://github.com/user/repo2.git
```

---

## Clone Repository Using Token

To clone a repository using your GitHub token (for secure access):
```bash
git clone https://<Username>:<GithubToken>@github.com/repo-name.git
```

---

## Set Username Globally

To set the username globally for all your repositories:
```bash
git config --global credential.username "username"
```

---

## Set Username Locally

To set the username for a specific repository (without affecting other repos):
```bash
git config credential.username "username"
```

---

## Pull with Conflict Resolution

To pull changes while resolving conflicts:
```bash
git pull --rebase origin main
```

---

## Rename a Branch

To rename your current branch:
```bash
git branch -m branch_name
```

---

## Delete a Local Branch

To delete a local branch:
```bash
git branch -D branch_name
```

---

## Revert a Commit

To revert any commit using its commit ID:
```bash
git revert commitID
```
Press `Esc` + `:wq` + `Enter` to save and exit after editing.

---

## Check Git Version

To check the installed Git version:
```bash
git --version
```

---

## Check Commit Log

To view the commit log:
```bash
git log
```

---

## Checkout a Specific Commit

To go to a specific commit:
```bash
git checkout commit_id
```

---

## View Branches

To view all branches:
```bash
git branch
```

---

## Switch Branches

To switch to another branch:
```bash
git checkout branch_name
```

---

## Create and Checkout a New Branch

To create a new branch and immediately switch to it:
```bash
git checkout -b features/filename
```

---

## Merge Branches

To merge one branch into another:
```bash
git merge directory_name
```

---

## Push to Remote Repository

To add a remote and push your changes:
```bash
git remote add origin url_link
git push -u origin master
```

---

## Automate Accepting All Changes from `develop` (for All Files)

To accept all changes from the `develop` branch:
```bash
git checkout --theirs .
```

---

## Automate Accepting All Changes from `develop` (for a Single File)

To accept all changes from the `develop` branch for a single file (e.g., `DashboardScreen.dart`):
```bash
git checkout --theirs lib/screens/DashboardScreen.dart
```

---

This guide will assist you in efficiently working with Git. If you have any questions or need further details, feel free to open an issue or contribute to this repository!

---
