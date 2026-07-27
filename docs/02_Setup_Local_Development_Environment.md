# 🖥️ Step 3 – Setup Local Development Environment

## Objective

Set up a local development environment for building, testing, and version-controlling the Enterprise Retail Lakehouse project before deploying it to Databricks.

---

## Development Machine

- **Operating System:** Windows 11
- **IDE:** Visual Studio Code
- **Version Control:** Git
- **Source Code Repository:** GitHub

---

## Tasks Completed

- Installed Git.
- Configured Git with GitHub authentication.
- Cloned the GitHub repository to the local machine.
- Opened the project in Visual Studio Code.
- Verified Git connectivity.
- Configured Git Credential Manager for secure authentication.
- Successfully pushed the initial project structure to GitHub.

---

## Local Project Location

```text
D:\Retail-lakehouse\Enterprise-retail-lakehouse
```

---

## Verify Git Installation

```bash
git --version
```

Expected Output:

```text
git version 2.50.0.windows.1
```

---

## Verify Repository Status

```bash
git status
```

Expected Output:

```text
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
```

---

## Verify Remote Repository

```bash
git remote -v
```

Expected Output:

```text
origin  https://github.com/SuryaS03/Enterprise-retail-lakehouse.git (fetch)
origin  https://github.com/SuryaS03/Enterprise-retail-lakehouse.git (push)
```

---

## Development Workflow

1. Create or modify project files.
2. Stage changes using `git add .`.
3. Commit changes using `git commit`.
4. Push changes to GitHub using `git push`.
5. Pull the latest changes before starting new work using `git pull`.

---

## Deliverable

- Local development environment successfully configured.
- GitHub repository connected to the local machine.
- Visual Studio Code configured for development.
- Git authentication verified.
- Project ready for implementation.