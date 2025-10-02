# DevOps Versioned Project# DevOps Version-Controlled Project

## 📌 Purpose
This repository demonstrates **Git best practices** for a DevOps project.  
It shows how to:
- Initialize a Git repository
- Create and manage branches (`main`, `dev`, `feature/*`)
- Use pull requests for collaboration
- Add proper commit messages and tags
- Document tasks using Markdown

---

## 🛠️ Tools Used
- Git
- GitHub

---

## 🌳 Branching Strategy
- **main** → Stable, production-ready code  
- **dev** → Integration branch (all features merged here before release)  
- **feature/** → Short-lived branches for individual tasks  

---

## 🔄 Workflow
1. Create a new feature branch:

   git checkout dev
   git checkout -b feature/your-feature
Make changes, commit, and push:

---
git add .
git commit -m "feat: describe your change"
git push origin feature/your-feature

---

Open a Pull Request:

Base branch → dev

Compare branch → feature/your-feature

After testing & review, merge into dev.

When stable, merge dev → main.

Tag releases on main:

---
git tag -a v1.0.0 -m "Release v1.0.0"
git push origin v1.0.0
✅ Commit Message Convention
feat: → New feature

fix: → Bug fix

chore: → Maintenance, docs, config updates

Example:

scss
Copy code
feat(ci): add GitHub Actions workflow
fix(docker): correct Dockerfile path
chore(docs): update README instructions
## 🔄 Workflow
1. Clone the repository:
   ```bash
   git clone https://github.com/PavaniKumbam/devops-versioned-project.git
   cd devops-versioned-project

