# my-first-repo
My first GitHub repository with basic Python projects.
# Navigate to the directory where you want to create the repository
cd path/to/your/folder

# Create a new folder for the repository and move into it
mkdir my-first-repo && cd my-first-repo

# Initialize Git in the folder
git init

# Create a README file with a project title
echo "# My First Repository" > README.md

# Add all files to Git's staging area
git add .

# Commit the files with a message
git commit -m "Initial commit"

# Connect the local repository to GitHub (Replace with your actual repository URL)
git remote add origin https://github.com/your-username/my-first-repo.git

# Set the main branch (default branch)
git branch -M main

# Push the changes to GitHub
git push -u origin main
