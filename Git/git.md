# Git Documentation

## 1. Introduction

Git is a distributed version control system used to track changes in source code and files.

## 2. Important Git Commands

### Check Git Version

```bash
git --version
```
Displays the installed Git version.

### Configure Username and Email

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@gmail.com"
```

### Initialize Repository

```bash
git init
```
Initializes a new Git repository.

### Check Repository Status

```bash
git status
```
Shows modified, untracked and staged files.

### Add Files

```bash
git add .
```
Adds all changes to the staging area.

```bash
git add filename
```
Adds a specific file.

### Commit Changes

```bash
git commit -m "First commit"
```
Saves a snapshot of staged changes.

### View Commit History

```bash
git log
```

```bash
git log --oneline
```

### View Changes

```bash
git diff
```
Shows unstaged changes.

```bash
git diff --staged
```
Shows staged changes.

### Branch Commands

```bash
git branch
git branch new-branch
git switch new-branch
git switch main
git branch -d new-branch
```

### Merge Branch

```bash
git merge new-branch
```
Merges another branch into the current branch.

### Remote Repository

```bash
git remote -v
git remote add origin REPOSITORY_URL
git remote remove origin
```

### Push and Pull

```bash
git push origin main
git pull origin main
```

### Clone Repository

```bash
git clone REPOSITORY_URL
```

### Rename Branch

```bash
git branch -M main
```

## 3. Git Workflow

1. Initialize repository using git init.
2. Create or modify files.
3. Check changes using git status.
4. Add files using git add.
5. Commit changes using git commit.
6. Upload changes using git push.

## 4. Git vs GitHub

| Git | GitHub |
|---|---|
| Version control system | Online hosting platform |
| Works locally | Works online |
| Tracks file changes | Hosts repositories |
| Uses terminal commands | Provides collaboration tools |

## 5. Advantages of Git

- Tracks project history.
- Supports branching.
- Helps collaborate with developers.
- Allows restoring previous versions.

## 6. Conclusion

Git is an important tool for version control and GitHub makes it easy to host and share Git repositories.