# Git Commands

## Basic

| Command                      | Description                                  |
|-------------------------------|----------------------------------------------|
| `git init`                    | Initialize current project as a new Git repository             |
| `git clone <url>`             | Copy a remote repository to your local machine |
| `git status`                  | Show the working directory and staging area status |
| `git add <file>`              | Stage a specific file for commit            |
| `git add --all`                   | Stage all changes |
| `git commit -m "your message"`     | Commit staged changes with a message        |
| `git push`                    | Upload local commits to a remote repository |
| `git pull`                    | Fetch and merge changes from a remote repository |
| `git branch`                  | List all local branches                     |
| `git checkout <branch>`       | Switch to another branch                    |
| `git checkout -b <branch>`    | Create and switch to a new branch           |


## Advanced

| Command                      | Description                                  |
|-------------------------------|----------------------------------------------|
| `git merge <branch>`          | Merge another branch into your current branch |
| `git rebase <branch>`         | Reapply commits from one branch onto another (linear history) |
| `git fetch`                   | Download new changes without merging        |
| `git reset --hard <commit>`   | Reset current branch to a specific commit and discard changes |
| `git revert <commit>`         | Create a new commit that undoes changes from a commit |
| `git cherry-pick <commit>`    | Apply a specific commit from another branch onto the current branch |
| `git stash`                   | Save uncommitted changes for later           |
| `git stash pop`               | Reapply stashed changes and remove from stash |
| `git log --oneline`           | Display the commit history compactly        |
| `git remote -v`               | Show connected remotes and their URLs       |


## Handy Commands

| Command                      | Description                                  |
|-------------------------------|----------------------------------------------|
| `git diff`                    | Show unstaged changes                      |
| `git diff --staged`           | Show staged changes                        |
| `git clean -fd`               | Remove untracked files and directories     |
| `git tag`                     | List tags (important commits like releases) |
| `git tag <name>`              | Create a new tag                           |
| `git shortlog`                | Summarize commits by contributor           |
| `git show <commit>`           | Show details of a specific commit          |
| `git blame <file>`            | Show who last modified each line of a file |
| `git archive`                 | Create an archive (e.g., zip) of your repository |
| `git describe --tags`         | Show the most recent tag reachable from a commit |
