# 🔧 Git DevOps Guide

A simple guide to Git workflows used in DevOps for version control and team collaboration.

---

## 📌 Key Concepts

- Version control with Git  
- Branching strategy  
- Collaboration using GitHub  
- Pull Requests & code review  

---

## 🌿 Branching Strategy

- `main` → production  
- `develop` → integration  
- `feature/*` → new features  

---

## ⚙️ Basic Commands

```bash
# clone repo
git clone <repo-url>

# create branch
git checkout -b feature/name

# add & commit
git add .
git commit -m "message"

# push
git push origin feature/name

# pull updates
git pull origin develop
```

---

## 🔄 Workflow

1. Create feature branch  
2. Make changes & commit  
3. Push to GitHub  
4. Open Pull Request  
5. Merge to develop/main  

---

## ✅ Best Practices

- Don’t work on `main`  
- Write clear commit messages  
- Pull before pushing  
- Keep commits small  

---

## 👩‍💻 Author

Furaha Justine
