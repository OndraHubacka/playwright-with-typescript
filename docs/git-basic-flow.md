# 🚀 Git Cheatsheet (QA Automation)

Basic Git commands for everyday work with projects and GitHub.

---

## 🔥 Basic Flow (most important)

```bash
git add -A
git commit -m "your message"
git push
```

### 🧠 What it means

- `git add -A` → prepare all changes (new, modified, deleted)
- `git commit` → save changes locally
- `git push` → upload changes to GitHub

---

## 📦 Clone project

```bash
git clone https://github.com/your-name/repo.git
cd repo
```

---

## 📂 Check status

```bash
git status
```

👉 Shows:
- modified files
- new files
- deleted files

---

## 📜 View history

```bash
git log
```

---

## 🌿 Branches

### Create new branch
```bash
git checkout -b feature/login
```

### Switch branch
```bash
git checkout main
```

---

## 🔄 Pull changes from GitHub

```bash
git pull
```

👉 Downloads latest changes

---

## ⚠️ Common mistakes

### ❌ Forgot to add files
```bash
git commit -m "msg"
```
👉 nothing happens

✔️ Fix:
```bash
git add -A
git commit -m "msg"
```

---

### ❌ Changes not on GitHub
👉 you forgot:

```bash
git push
```

---

## 💡 Pro Tips

- Always check:
```bash
git status
```

- Use clear commit messages:
```bash
git commit -m "add login test"
```

---

## 🧠 TL;DR

```bash
git add -A
git commit -m "message"
git push
```