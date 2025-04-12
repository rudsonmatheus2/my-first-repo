# 🚀 GitHub Repository Setup Guide
This script demonstrates how to initialize a local Git repository and push your project to GitHub.

## 📜 Git Commands Explained
``` bash
# Add all files to Git's staging area
git add .
```
Adds all files in the current directory to the staging area, preparing them to be committed.
``` bash
# Commit the files with a message
git commit -m "Initial commit"
```
Commits the staged changes with a message "Initial commit".
```bash
# Connect the local repository to GitHub (Replace with your actual repository URL)
git remote add origin https://github.com/your-username/my-first-repo.git
```
Adds a remote named `origin` that points to your GitHub repository.
> 🔁 Replace https://github.com/your-username/my-first-repo.git with your actual repository URL
``` bash
# Set the main branch (default branch)
git branch -M main
```
Renames the current branch to main, which is the standard default branch name on GitHub.
```bash
# Push the changes to GitHub
git push -u origin main
```
Pushes the committed code to the main branch on GitHub and sets it as the upstream for future pushes.
## ✅ Result
After running these commands, your local project will be available on GitHub and ready for collaboration or deployment.

