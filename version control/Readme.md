# 🧑‍💻 Git Commands with Descriptions

This markdown file provides a list of essential **Git commands** along with their **descriptions and common use cases**.

| **Command**                         | **Description**                                                                 | **Example & Use Case**                                                                 |
|-------------------------------------|----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|
| `git init`                          | Initializes a new Git repository in the current directory                        | `git init` sets up a `.git` folder to start version control                           |
| `git clone <repo-url>`              | Clones an existing repository from GitHub or another remote                      | `git clone https://github.com/user/repo.git` copies repo locally                      |
| `git status`                        | Shows the current status of files (staged, modified, untracked)                  | Helps check what changes are pending                                                   |
| `git add <file>`                    | Stages specific file(s) for commit                                               | `git add index.html` adds the file to staging area                                     |
| `git add .`                         | Stages all modified and new files                                                | Useful when you want to stage everything at once                                       |
| `git commit -m "message"`           | Commits staged changes with a message                                            | `git commit -m "Added login feature"` saves snapshot with message                      |
| `git log`                           | Shows the commit history                                                         | `git log --oneline` gives a concise view                                               |
| `git diff`                          | Shows changes between working directory and index                                | Helps review changes before staging                                                    |
| `git branch`                        | Lists all branches or creates a new one                                          | `git branch dev` creates a `dev` branch                                                |
| `git checkout <branch>`             | Switches to the specified branch                                                 | `git checkout main` switches to main branch                                            |
| `git checkout -b <branch>`          | Creates and switches to a new branch                                             | `git checkout -b featureX` creates and switches to `featureX`                          |
| `git merge <branch>`                | Merges changes from the named branch into current branch                         | `git merge dev` merges dev into current branch                                         |
| `git pull`                          | Fetches and merges changes from remote repository                                | Keeps local branch up to date                                                          |
| `git push`                          | Uploads local commits to remote repository                                       | `git push origin main` pushes changes to GitHub                                        |
| `git remote -v`                     | Displays the remote repository URLs                                              | Useful to verify connection to GitHub                                                  |
| `git reset <file>`                  | Unstages a file (removes it from the staging area)                               | `git reset index.html`                                                                 |
| `git rm <file>`                     | Deletes a file and stages the removal                                            | `git rm file.txt` removes file from both disk and Git                                 |
| `git stash`                         | Temporarily shelves changes without committing                                   | `git stash` saves changes; `git stash pop` restores them                               |
| `git rebase <branch>`              | Re-applies commits on top of another base tip                                    | Used to maintain linear project history                                                |
| `git tag`                           | Tags a specific commit (used for releases)                                       | `git tag v1.0` marks the current commit as version 1.0                                 |
| `git fetch`                         | Retrieves latest changes from remote without merging                             | Use before reviewing changes from others                                               |
| `git config`                        | Sets Git configuration options                                                   | `git config --global user.name "Your Name"` sets username globally                     |
| `git blame <file>`                 | Shows who made changes to each line of a file                                    | Helpful in tracking code history                                                       |
| `git revert <commit>`              | Reverts a specific commit by creating a new one                                  | `git revert abc1234` undoes the effects of a commit safely                            |
| `git cherry-pick <commit>`         | Applies the changes from a specific commit                                       | Useful to apply a bug fix from another branch                                          |

---

💡 **Tip:** Always pull (`git pull`) before pushing (`git push`) to avoid merge conflicts.

---

### Git Aliases

You can create aliases to shorten commonly used commands:

```bash
git config --global alias.co checkout
git config --global alias.br branch
git config --global alias.ci commit
git config --global alias.st status
