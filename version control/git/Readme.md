# 🧑‍💻 Git Commands by Use Case

## 🔹 1. Initializing and Cloning Repositories

- `git init`  
  Initialize a new local Git repository.

- `git clone <repository-url>`  
  Clone a remote repository into your local machine.

---

## 🔹 2. Checking the Status of Files

- `git status`  
  Show the working tree status: staged, unstaged, or untracked files.

- `git diff`  
  See the changes made to files that are not yet staged.

- `git diff --staged`  
  Show changes that have been staged but not yet committed.

---

## 🔹 3. Staging and Committing Changes

- `git add <filename>`  
  Stage a specific file for commit.

- `git add .`  
  Stage all changes (new, modified, deleted) in the current directory.

- `git commit -m "message"`  
  Commit staged changes with a message.

---

## 🔹 4. Working with Branches

- `git branch`  
  List all local branches.

- `git branch <branch-name>`  
  Create a new branch.

- `git checkout <branch-name>`  
  Switch to a different branch.

- `git checkout -b <branch-name>`  
  Create and switch to a new branch in one command.

---

## 🔹 5. Merging and Rebasing

- `git merge <branch-name>`  
  Merge changes from the specified branch into the current branch.

- `git rebase <branch-name>`  
  Reapply commits from one branch onto another for a linear history.

---

## 🔹 6. Working with Remote Repositories

- `git remote -v`  
  Show the URLs of your remote repositories.

- `git fetch`  
  Download changes from the remote repository but don’t merge.

- `git pull`  
  Fetch and merge changes from the remote repository into your current branch.

- `git push`  
  Push committed changes to the remote repository.

- `git push origin <branch>`  
  Push a specific branch to the remote.

---

## 🔹 7. Undoing Changes

- `git reset <file>`  
  Unstage a file from the staging area.

- `git checkout -- <file>`  
  Discard changes in the working directory.

- `git revert <commit>`  
  Create a new commit that undoes the changes of a specific commit.

- `git stash`  
  Save your uncommitted changes temporarily.

- `git stash pop`  
  Apply the last stashed changes back to your working directory.

---

## 🔹 8. Tagging Versions

- `git tag`  
  List all tags.

- `git tag <tag-name>`  
  Create a new tag for the current commit.

- `git tag -a <tag-name> -m "message"`  
  Create an annotated tag with a message.

---

## 🔹 9. Log and History Inspection

- `git log`  
  View the commit history.

- `git log --oneline`  
  Show a simplified one-line-per-commit history.

- `git blame <file>`  
  Show who last modified each line of a file.

- `git show <commit>`  
  Display information about a specific commit.

---

## 🔹 10. Aliases for Productivity

```bash
git config --global alias.st status
git config --global alias.co checkout
git config --global alias.ci commit
git config --global alias.br branch
