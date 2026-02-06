# Git and GitHub – Beginner Summary

---

## 1. What is Git?
- Git is a **version control system**.
- Tracks changes to files over time (like a “time machine”).
- Lets you **revert changes**, create copies of files, and merge changes.
- Useful for **code, text files, images, etc.**

---

## 2. Installing & Configuring Git
- **Download Git:** [https://git-scm.com/downloads](https://git-scm.com/downloads)
- Verify installation:
  ```bash
  git --version
  ```
- Configure your username and email:
  ```bash
  git config --global user.name "YOUR_USERNAME"
  git config --global user.email "YOUR_EMAIL"
  ```

---

## 3. Creating and Initializing a Git Project
- Navigate to your project folder:
  ```bash
  cd path/to/project
  ```
- Initialize Git:
  ```bash
  git init
  ```
- A **repository (repo)** is a project being tracked by Git.

---

## 4. GitHub Basics
- **GitHub:** online platform to **host Git repositories**.
- Benefits: access projects from anywhere, collaborate with others.
- **Create an account:** [https://github.com/join](https://github.com/join)
- Push a local project to GitHub:
  ```bash
  git remote add origin YOUR_REPO_URL
  git branch -M main
  git push -u origin main
  ```

---

## 5. Git File States
1. **Modified** – file has changes but not staged.
2. **Staged** – file is ready to commit.
3. **Committed** – file changes saved in local repository.

**Commands:**
- Stage files: `git add .` or `git add filename`
- Commit files: `git commit -m "message"`
- Check status: `git status`

> Think of Git like a camera: snapshots are taken at the **commit stage**, and modifications are compared to the last snapshot.

---

## 6. Updating Files
- Modify your files.
- Repeat: **Stage → Commit → Push**.
- Always push updates to GitHub for backup and collaboration.

---

## 7. Branches
- Branches let you **work on changes separately** without affecting main project.
- Create a branch:
  ```bash
  git checkout -b branch_name
  ```
- Switch to an existing branch:
  ```bash
  git checkout branch_name
  ```
- Merge changes into main:
  ```bash
  git merge branch_name
  ```

---

## 8. Pulling a Repository
- Pull a remote repository to your computer:
  ```bash
  git clone REPO_URL
  ```
- Useful when working on a project from another computer or collaborating.

---

## 9. Key Git Commands

| Command | Purpose |
|---------|---------|
| `git init` | Initialize a local repository |
| `git add .` | Stage all files for commit |
| `git commit -m "msg"` | Commit staged files with a message |
| `git status` | Check the state of files |
| `git push -u origin main` | Push changes to GitHub |
| `git branch` | List branches |
| `git checkout -b branch_name` | Create and switch to new branch |
| `git checkout branch_name` | Switch to existing branch |
| `git merge branch_name` | Merge changes from branch |
| `git clone REPO_URL` | Download repo from GitHub |

---

## 10. Teaching Tips
- Use a simple **text file (like todo.txt)** to demonstrate Git commands.
- Emphasize the **workflow**: modify → stage → commit → push.
- Show **branches** as a safe way to test changes before merging.
- Reinforce that **Git is useful beyond coding**—for text, projects, or images.

---

## Useful Links
- Download Git: [https://git-scm.com/downloads](https://git-scm.com/downloads)  
- Create GitHub account: [https://github.com/join](https://github.com/join)
