# 📘 Git & GitHub Complete Notes


A beginner-friendly and structured guide to understanding **Git** and **GitHub** fundamentals, including commands, workflow, branching, tagging, and collaboration.

---

## 📌 Topics Covered

- Git Initialization  
- Working Directory, Staging Area & Commit Flow  
- Adding & Committing Files  
- Viewing Changes (diff)  
- Removing Files from Staging  
- Tags (Lightweight & Annotated)  
- Cloning Repositories  
- Branching Concept  
- Merging Branches  
- Pushing to Remote Repository  

---

# 🚀 Git Workflow

```
Working Directory
        ↓ (git add)
Staging Area
        ↓ (git commit)
Local Repository
        ↓ (git push)
Remote Repository (GitHub)
```

---

# 🔹 Basic Commands

## 1️⃣ Check Status

```bash
git status
```

---

## 2️⃣ Initialize Repository

```bash
git init -b main
```

- `init` → Initialize repository  
- `-b` → Create branch  
- `main` → Branch name  

---

## 3️⃣ Add Files to Staging

Add single file:

```bash
git add file_name
```

Add all files:

```bash
git add .
```

---

## 4️⃣ Commit Changes

```bash
git commit -m "Your message"
```

Skip staging (tracked files only):

```bash
git commit -a -m "message"
```

---

## 5️⃣ Push to GitHub

```bash
git push origin main
```

- `origin` → Remote name  
- `main` → Branch  

---

# 🔍 Viewing Changes

See working directory changes:

```bash
git diff
```

See staged changes:

```bash
git diff --staged
```

🟢 Green → Added/Modified  
🔴 Red → Deleted  

---

# ❌ Remove File from Staging

```bash
git rm --cached file_name
```

---

# 🏷️ Tags (Versioning)

## See All Tags

```bash
git tag
```

## Lightweight Tag

```bash
git tag v1.0
```

## Annotated Tag

```bash
git tag -a v1.0 -m "Version 1.0 release"
```

## Show Tag Details

```bash
git show v1.0
```

---

# 📥 Clone Repository

```bash
git clone repository_link
```

---

# 🌿 Branching

## Create Branch

```bash
git switch -c branch_name
```

OR

```bash
git checkout -b branch_name
```

---

## View Branches

```bash
git branch
```

All branches (including remote):

```bash
git branch --all
```

---

## Switch Branch

```bash
git switch branch_name
```

Switch to previous branch:

```bash
git switch -
```

---

## Delete Branch

```bash
git branch -d branch_name
```

---

# 🔀 Merge Branch

Switch to main:

```bash
git switch main
```

Merge:

```bash
git merge branch_name
```

---

# 🧠 Why Git?

- Version control  
- Track history  
- Team collaboration  
- Safe experimentation using branches  
- Professional workflow  

---

Note : This readme was polished by using AI tool

# 👨‍💻 Author

**Guduru Jeevan Kumar**  
Frontend Developer (HTML, CSS, Tailwind, JavaScript)  
Python & SQL Learner  