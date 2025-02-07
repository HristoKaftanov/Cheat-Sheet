# Git Commands Cheat Sheet
### Initialize a new Git repository:
```
git init
```
### Clone an existing repository:
```
git clone <repository-url>
```
## Staging & Committing
### Check the status of files:
```
git status
```
### Add a file to staging area:
```
git add <file>
```
### Add all files to staging:
```
git add .
```
### Commit changes with a message:
```
git commit -m "Your commit message"
```
### View commit history:
```
git log
```
## Branching & Merging
### Create a new branch:
```
git branch <branch-name>
```
### List all branches:
```
git branch
```
### Switch to a different branch:
```
git checkout <branch-name>
```
### Create and switch to a new branch:
```
git checkout -b <branch-name>
```
### Merge a branch into the current branch:
```
git merge <branch-name>
```
## Remote Repositories
### Add a remote repository:
```
git remote add origin <repository-url>
```
### Fetch changes from the remote repository:
```
git fetch
```
### Pull changes from the remote repository:
```
git pull origin <branch-name>
```
### Push changes to the remote repository:
```
git push origin <branch-name>
```
## Viewing & Diffing Changes
### See the changes you made:
```
git diff
```
## Stashing Changes
### Save changes to a stash:
```
git stash
```
### Apply the most recent stash:
```
git stash apply
```
### List all stashes:
```
git stash list
```
## Git Help
### Get help for a specific Git command:
```
git help <command>
```
### Get a quick overview of Git commands:
```
git
```