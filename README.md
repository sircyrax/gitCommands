<h1>Git Commands</h1>

Here are some very important or useful Git Commands.
 

## Start a Project

| Command | Description |
| --- | --- |
| git init	 | Creates a new Git repository (.git file) |
| git clone https://github.com/sircyrax/gitCommands.git | Clone a repository into a new directory on local |
| git clone https://github.com/sircyrax/gitCommands.git test | Clone a repository into a new directory with folder name |

## Update the Project 

| Command | Description |
| --- | --- |
| git status | To check the modified or untracked files |
| git add . / git add -A	 | To add all changed files in staging area |
| git add FILE_NAME	 | To add single files in staging area |
| git commit –m COMMIT_MSG 	 | Commit the changes |
| git commit -a –m COMMIT_MSG 	 | To add the changes and commit that changes (only include modified files not untracked files) |
| git push	 | Push the updates on remote repository |
| git push origin BRANCH_NAME	 | Push a local branch to your remote repository |
| git push -d origin BRANCH_NAME	| Delete a branch from remote |

## Working with Branches

| Command | Description |
| --- | --- |
| git branch | Show all the local branches |
| git branch -a | Show all the local and remote branches |
| git branch BRANCH_NAME | Create a new branch |
| git checkout -b BRANCH_NAME | Create a new branch and switch to it |
| git checkout BRANCH_NAME | Switch to a branch |
| git checkout - | Switch to the last checked out branch |
| git branch --merged | To get branches name which have merged |
| git branch --no-merged | To get branches name which have merged |
| git merge BRANCH_NAME | Merge the branch into the current branch |
| git branch -v | To get all branch with their last commits |
| git branch -d BRANCH_NAME| Delete a branch (will give warning if that branch is not merged) |
| git branch -D BRANCH_NAME | Delete a branch (Force delete) |
| git push -d origin BRANCH_NAME | Delete a remote branch |

## Pull the project

| Command | Description |
| --- | --- |
| git pull | Get the updated files on local repository  |
| git pull origin BRANCH_NAME | Merge into the current branch from remote branch |

## Commands for User

| Command | Description |
| --- | --- |
| git config --global user.name "USERNAME" | To add username |
| git config --global user.email "test@example.com"| To add the email address |
 
## Some useful commands

| Command | Description |
| --- | --- |
| git diff | To get difference in two files (one in staging area and one in working directory) |
| git diff --staged | To compare last commit with the staging area |
| git rm FILE_NAME | To remove file from folder(it will auto add the file in staging area) |
| git mv OLD_FILE_NAME NEW_FILE_NAME |To rename a file(it will auto add the file in staging area) |
| git rm --cached FILE_NAME | To remove a file from tracking |
| git restore --staged FILE_NAME | To unstage a file |
| git checkout -- FILE_NAME | To get the particular file data from the last commit (Ex - if we delete the data from a file and want to restore from the last commit) |
| git checkout -f | To get the all files data from the last commit |
| git config --global alias.cmt commit | To change a git command with short words(Ex – to change the commit command with cmt) |
| touch FILE_NAME | To create a new file |
| rm -rf .git | To remove track the folder from git and to delete git local repository |


## Commands for Verification

| Command | Description |
| --- | --- |
| git log | To check the commits |
| git log --stat | To check the commits in short details |
| git log --pretty=oneline | To check the commit in online |
| git log --pretty=short | To check the commit in short |
| git log --since=10.days | To filter the commits(get the last 10 days commit) |
| git log --since=10.months | To filter the commits(get the last 10 days commit) |
| git log --since=10.years | To filter the commits(get the last 10 days commit) |
| git log -p | To check the commits with changes |
# gitCommands
