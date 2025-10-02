# DevOps Versioned Project# DevOps Version-Controlled Project

## 📌 Objective
This project is created to practice **Git version control best practices** as part of a DevOps workflow.  
It demonstrates repository initialization, branching, pull requests, tagging, and documentation.

---

## 🛠️ Tools Used
- **Git** (for version control)
- **GitHub** (for remote repository hosting)

---

## 🌳 Branching Strategy
- `main` → **Production-ready branch**  
- `dev` → **Integration branch** (all features are merged here first)  
- `feature/*` → **Feature branches** created from `dev` for individual tasks  

👉 Example feature branch names:
- `feature/add-ci`
- `feature/update-readme`
- `feature/add-docker-support`

---

## 🔄 Workflow
1. Clone the repository:
   ```bash
   git clone https://github.com/PavaniKumbam/devops-versioned-project.git
   cd devops-versioned-project

