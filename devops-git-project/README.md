# DevOps Git Project

## 📌 Objective
This project demonstrates Git best practices for managing a DevOps workflow.

## 🚀 Tools Used
- Git & GitHub
- Docker
- Markdown Documentation

## 🗂 Branching Strategy
- **main** → Production-ready code
- **dev** → Development integration
- **feature/** → For new features or bug fixes

## 🔄 Workflow
1. Create a feature branch from `dev`.
2. Work on your changes.
3. Commit with clear messages.
4. Push branch and create a PR to merge into `dev`.
5. Merge `dev` into `main` for production.

## 📁 Docs
All task documentation is in the [`docs/`](docs/) folder.

## 🛠 Setup
```bash
# Clone the repository
git clone https://github.com/<your-username>/devops-git-project.git

# Go into project folder
cd devops-git-project

# Build and run the Docker container
docker build -t devops-git-app ./app
docker run -p 3000:3000 devops-git-app
```

## 📌 Versioning
We use Git tags for releases:
```bash
git tag -a v1.0 -m "First stable release"
git push origin v1.0
```
