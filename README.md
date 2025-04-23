# DevOps Assignment Submission

## 🔗 Links
- **GitHub Repository:** [Sharu0625/devops-assignment](https://github.com/Sharu0625/devops-assignment)
- **Docker Hub Repository:** [sharu0625/hello-docker](https://hub.docker.com/repository/docker/sharu0625)

---

## 📁 Question 1: Git & GitHub

### ✅ 1a. Initialize Git & Simple Web App
- Created `index.html`, `about.html`, and `contact.html` with basic HTML content.
- Initialized a Git repository.

📸 **Screenshot 1:** Shows folder structure and `git init` confirmation.

---

### ✅ 1b. Git Commands Demonstration

- `git status` — Shows untracked HTML files.
- `git add .` — Stages all files.
- `git commit -m "Initial commit with HTML files"` — Commits staged files.
- `git log` — Displays commit history.
- `git branch` — Shows current branch.
- `git branch new-feature` — Creates a new branch.
- `git switch new-feature` — Switches to new-feature branch.
- `git switch main` — Switches back to main branch.

📸 **Screenshot 2:** Terminal output showing all the commands and their result.

---

### ✅ 1c. GitHub Integration

- Created a GitHub repo and pushed code using:
  ```bash
  git remote add origin https://github.com/Sharu0625/devops-assignment.git
  git push -u origin main

---
📸 **Screenshot 3:** GitHub repository page.
📸 **Screenshot 4:** Terminal showing push success.

### 🐳 Question 2: Docker
## ✅ 2a. Dockerfile and Python App
    Created docker-app folder with:
    - app.py: prints "Hello, World from Docker!"
    - Dockerfile: uses python:3.9-slim, sets working dir, copies app.py, and runs it.

📸 **Screenshot 5:** Folder contents and Dockerfile.

## ✅ 2b. Build Docker Image
Built image with:
    `docker build -t sharu0625/hello-docker`
 
📸 **Screenshot 6:** Terminal output of successful build.

## ✅ 2c. Push to Docker Hub
Pushed image using:
    `docker push sharu0625/hello-docker`

📸 **Screenshot 7:** Push output.
📸 **Screenshot 8:** Docker Hub repository page.

## ✅ 2d. Run Docker Container
Ran the container with:
    `docker run sharu0625/hello-docker` 
📸 **Screenshot 9:** Terminal shows Hello, World from Docker!