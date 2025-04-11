Devops Internship

TASK-4

# DevOps Git Project - Version Control Workflow

## 📌 Project Overview
This project demonstrates Git best practices in a DevOps environment. It showcases a version-controlled setup using Git and GitHub with proper branching strategies, pull requests, documentation, and tagging.

---

## 🚀 Objectives
- Initialize a Git project and push it to GitHub
- Use standard branching strategies: `main`, `dev`, `feature/*`
- Collaborate using pull requests and proper commit history
- Document tasks using Markdown
- Apply `.gitignore` and tagging for clean version control

---

## 🌿 Branching Strategy

| Branch       | Purpose                          |
|--------------|----------------------------------|
| `main`       | Stable production-ready code     |
| `dev`        | Integration of features for testing |
| `feature/*`  | Development of new individual features |

---

## 🔀 Pull Request Workflow
1. Feature branch is created from `dev`.
2. Work is committed and pushed to GitHub.
3. Pull Request (PR) is created from `feature/*` → `dev`.
4. After review, `dev` is merged into `main` for release.

