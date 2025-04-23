## Github-Useful-Command

# To clone the repository
-> git clone repo_url

# Check status
-> git status 

# To add file/folder 
-> git add . (for all)
-> git add filename (for single)

# Commit
-> git commit -m “initial commit”

# To push the branch
-> git push

# Git Push using github token
git push https://<Username>:<GithubToken>@github.com/repo-name.git

# List all remote repositories that your local Git project is connected to — along with their URLs.
git remote -v

# Adds a new remote URL to your local Git configuration.
git remote add origin https://repo-url.git

# This changes the URL of the specified remote repository.
git remote set-url origin https://github.com/user/repo2.git

# To Clone the repo
git clone https://<Username>:<GithubToken>@github.com/repo-name.git

# To set the username global to all the repo
git config --global credential.username "username"

# To set the username global to all the repo
git config credential.username "username"

# To pull when conflict 
git pull --rebase origin main

# To rename the branch
git branch -m branch_name

# To delete local branch
git branch -D branch_name

# How to revert any commit 
git revert commitID
esc + :wq + enter

# To check the git version
Git —version

# To check commit log
-> git log

# To go to any commit
-> get checkout commit_id

# To see the branch
-> git branch

# To switch to any branch
-> git checkout branch_name

# To create a branch and open that branch
-> git checkout -b features/filename

# To merge the branch 
-> git merge directory_name

# git remote add origin url_link
-> git push -u origin master

# If you want to automate accepting all of develop’s changes:
git checkout --theirs .

# If you want to automate accepting all of develop’s changes only for single file:
git checkout --theirs lib/screens/DashboardScreen.dart
