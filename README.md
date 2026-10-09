# DevOps Winter Arc - Day 07: Git, GitHub & Production Challenge

## 📌 Project Overview
This repository demonstrates a production-style DevOps workflow combining version control with Git/GitHub, branching strategies, Pull Requests, and Nginx reverse proxy incident resolution[cite: 1, 4].

## 🛠️ Git & GitHub Workflow
1. **Branching Strategy:** Created feature branches (`feature/status-page`, `feature/health-check`, `feature/improve-readme`) to ensure direct pushes to `main` are avoided[cite: 2, 3, 6].
2. **Security & Cleanliness:** Configured `.gitignore` to prevent tracking runtime logs, environment variables, and dependencies.
3. **Peer Review:** All code changes were merged into `main` via GitHub Pull Requests.

## 🧪 Testing Instructions
1. Clone this repository:
   ```bash
   git clone [https://github.com/dhirajage/devops-winter-arc-day7.git](https://github.com/dhirajage/devops-winter-arc-day7.git)
   cd devops-winter-arc-day
