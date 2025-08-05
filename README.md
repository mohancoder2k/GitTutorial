# 🧠 Git Learning Journey – Mohan's GitTutorial

This repository is a hands-on Git practice project where I explored and mastered essential Git commands and workflows using VS Code, Git Bash, and GitHub.

---

## ✅ Git Concepts Covered

### 🔹 1. Git Initialization
- Initialized a Git repository using `git init`
- Set up remote repo connection via `git remote add origin`

---

### 🔹 2. Basic Git Workflow
- Created and edited files
- Staged changes using `git add`
- Committed changes with `git commit -m "message"`
- Pushed code to GitHub using `git push`

---

### 🔹 3. Tags
- Created annotated tags using `git tag -a v1.0 -m "Initial release"`
- Viewed tag metadata with `git show v1.0`
- Pushed tags to remote with `git push origin --tags`

---

### 🔹 4. Git Stash
- Used `git stash` to temporarily save uncommitted changes
- Switched branches safely
- Used `git stash pop` to retrieve saved work

---

### 🔹 5. Branching & Merging
- Created feature branches: `git checkout -b new-design`
- Worked in isolation without affecting main branch
- Switched between branches using `git checkout branch-name`
- Merged branches using `git merge branch-name`
- Handled merge commits and fast-forward merges

---

### 🔹 6. Git Pull Errors & Fixes
- Encountered and resolved `non-fast-forward` errors
- Used `git pull --rebase` to sync changes
- Understood when Git refuses to merge without stashing

---

### 🔹 7. Pushing to GitHub
- Pushed both code and image files
- Verified changes in correct branches via GitHub UI

---

## 🧪 Key Git Commands Practiced

```bash
git init
git status
git add .
git commit -m "Message"
git push origin branch-name
git pull origin branch-name --rebase
git checkout -b branch-name
git merge branch-name
git stash
git stash pop
git tag -a v1.0 -m "Version 1"
git show v1.0
