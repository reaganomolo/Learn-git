# Git & GitHub Learning Journey

Welcome to my Git and GitHub learning documentation. This repository serves as my personal learning log, cheat sheet, and reference as I build solid Git skills for software development and DevOps.

---

## Objectives

- Understand version control and why Git is important
- Learn core Git commands and workflows
- Document practical examples and use cases
- Track daily learning progress

---

## My Learning Plan

| Topic                                |
|--------------------------------------|
| What is Git? Installation & Setup    |
| Git init, add, commit, status        |
| Git branches and merging             |
| Pushing to GitHub and remotes        |
| Git clone, pull, and fetch           |
| Resolving merge conflicts            |
| Real-world practice & project workflow |


---

## Key Git Commands

```bash
# Set global username and email
git config --global user.name "username"
git config --global user.email "your@email.com"

# Initialize a repository
git init

# Add files to staging
git add .

# Commit changes
git commit -m "Initial commit"

# Link to remote GitHub repo
git remote add origin https://github.com/username/repo-name.git

# clone/pull repo to local machine using SSH key
git clone git@github.com.username/repo-name.git

# Push to GitHub
git push -u origin main
