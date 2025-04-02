| **Command** | **Description** |
| --------------|-------------------|
| `git config --global user.name "Your Name"` | Set your Git username(github name) |
| `git config --global user.email "your.email@example.com"` | your Git email |
| `git config --global user.name` | Check the current logged-in user |
| `git config --global user.email` | Check the current logged-in user email |
| `git status` | Check the status of the working directory |
| `git clone <repository-url>` | Clone a repository |
| `git init`|Initializes a local Git repository in the directory|
| `git remote add <name> <url>`|Add a remote repository with the specified name and URL|
| `git branch` | List all local branches |
| `git branch -r` | List all remote branches |
| `git branch -a` | List all branches (local + remote) |
| `git branch --show-current` | Show the current branch |
| `git branch <new-branch name>` | Create a new branch |
| `git checkout <branch-name>`| Switch to an existing branch |
| `git switch <branch-name>` | Switch to an existing branch |
| `git checkout -b <new-branch name>`| Create and switch to a new branch |
| `git switch -c <new-branch name>` | Create and switch to a new branch |
| `git fetch` | Fetch updates from the remote repository |
| `git pull` | Pull the latest changes from the current branch |
| `git pull origin <branch-name>` | Pull updates from a specific branch |
| `git add .` | Stage all changes |
| `git commit -m "commit message"` |  Commit changes with a message |
| `git push` | Push changes of the current branch |
| `git push origin <branch-name>` | Push changes to a specific branch |
| `git push --set-upstream origin <new-branch-name>` | Push a new branch and set the upstream for future pushes and pulls |
| `git stash` | Save uncommitted changes temporarily |
| `git stash list` | View stashed changes |
| `git stash apply` | Apply the latest stash |
| `git stash drop` | Remove the latest stash |
| `git stash pop` | Apply & remove the latest stash |
| `git checkout -- <file>` | Discard unstaged changes in a file |
| `git log`| View the commit history |
| `git log --oneline`| Show commit history in a compact, one-line format |
| `git revert <commit-hash>`|Undo changes from a specified commit by creating a new commit|
| `git reset --hard HEAD` | Permanently reset all changes to the last commit |
| `git reset --soft HEAD~1` | Undo last commit, keep local changes |
| `git reset --hard HEAD~1` | Undo the last commit and remove changes |
| `git branch -d <branch-name>` | Delete a local branch |
| `git push origin --delete <branch-name>` | Delete a remote branch |
| `git merge <branch-name>` | Merge the specified branch into currently active branch |
| `git checkout main && git merge <branch-name>` | Merge a branch into main |
| `git status` | Check for merge conflicts |
| `git add <file>` | Stage resolved conflicts |
| `git commit -m "Resolved merge conflict message"` | Commit the resolved merge |
|`git diff` | Show the differences between files or commits |
|`git diff <file>` | Show changes made to a specific file |

Further Resources\
Official Git Documentation - https://git-scm.com/docs 



