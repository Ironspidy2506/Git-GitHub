# 🛠️ Git Cheat Sheet

Git is a **Version Control System** (VCS) that helps track changes in your code. It is:

1. Popular
2. Free and open-source
3. Fast and scalable

---

## 🚀 Git vs GitHub

- **Git**: A tool to manage and track changes in code.
- **GitHub**: A platform that allows developers to store and manage their code using Git.

---

## 🖥️ Setting Up Git

- **Visual Studio Code**: Integrates Git functionality directly into the editor.
- **Windows**: Use **Git Bash** for Git commands.
- **Mac**: Use the **Terminal** to run Git commands.

To verify Git is installed, run:
```bash
git --version
```

---

## 🔧 Configuration
Before starting, configure Git with your name and email:
```bash
git config --global user.name "YourName"
git config --global user.email "youremail@example.com"
```
To check your current configuration:
```bash
git config --list
```

---

## 📥 Cloning a Repository
Clone an existing repository to your local machine:
```bash
git clone <repository_link>
```

---

## 📊 Git Status
Check the status of your files:
```bash
git status
```

- **Untracked**: New files that are not tracked by Git.
- **Modified**: Files that have been changed.
- **Unmodified**: Files that have not been changed.
- **Staged**: Files ready for the next commit.

---

## 📂 Adding Files to Staging Area
Add files to the staging area before committing:
```bash
git add <file_name>
```
To add all files:
```bash
git add .
```

---

## 📥 Committing Changes
Commit your staged changes with a message:
```bash
git commit -m "Your commit message"
```

---

## 📤 Pushing to Remote Repository
Push your committed changes to the remote repository:
```bash
git push origin main
```

---

## 🆕 Initializing a New Repository
Create a new Git repository:
```bash
git init
```
Add a remote origin:
```bash
git remote add origin <repository_link>
```
Verify the remote:
```bash
git remote -v
```

---

## 🌿 Branching

### Check Current Branch
```bash
git branch
```

### Rename a Branch
```bash
git branch -M <new_name>
```

### Create and Switch to a New Branch
```bash
git checkout -b <new_branch_name>
```

### Switch to an Existing Branch
```bash
git checkout <branch_name>
```

### Delete a Branch
```bash
git branch -d <branch_name>
```

---

## 🔀 Merging Branches

### Compare Changes Between Branches
```bash
git diff <branch_name>
```

### Merge Branches
```bash
git merge <branch_name>
```

---

## 🔄 Pulling Updates from Remote Repository
Fetch and integrate changes from the remote repository to your local branch:
```bash
git pull origin main
```

---

## 🛠️ Resolving Merge Conflicts
Merge conflicts occur when Git cannot automatically reconcile differences. You will need to manually resolve these by editing conflicting files, then adding and committing the resolved files.

---

## 🔙 Undoing Changes

### Staged Changes
```bash
git reset <file_name>
git reset
```

### Committed Changes (Single Commit)
```bash
git reset HEAD~1
```

### Committed Changes (Multiple Commits)
```bash
git reset <commit_hash>
git reset --hard <commit_hash>
```

---

## 📜 Git Log
View commit history:
```bash
git log
```

---

## 🍴 Forking
A fork is a copy of a repository that allows you to make changes without affecting the original repository. Once you've made changes, you can create a pull request to merge them back into the upstream repository.

---

## 🚀 Workflow Summary

1. **GitHub Repo** → **Clone** → **Make Changes** → **Add** → **Commit** → **Push**

---

Feel free to customize this file and make it your own!
