# Git Basics

### Committing in a local repository

| Git command                      | Git task                                         |
| -------------------------------- | ------------------------------------------------ |
| `git status`                     | List all files that have changed and their state |
| `git add <filename>`             | Add a file to the stage                          |
| `git commit -m "Commit message"` | Create a commit including all staged files       |
| `git log --oneline`              | Show the commit history                          |

### Git `branch` commands

| command                           | functionality                        |
| --------------------------------- | ------------------------------------ |
| `git switch -c <branchname>`      | create a new branch and switch to it |
| `git switch <branchname>`         | switch branches                      |
| `git branch`                      | list your branches                   |
| `git branch -a`                   | list all branches (local and remote) |
| `git branch -d <branchname>`      | delete a branch                      |
| `git push -u origin <branchname>` | create a remote branch               |

### Synchronizing local & remote repositories

| Git command | Git task                                    |
| ----------- | ------------------------------------------- |
| `git push`  | Upload content to the remote repository     |
| `git pull`  | Download content from the remote repository |
