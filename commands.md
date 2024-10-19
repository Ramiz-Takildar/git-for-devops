# Git Commands

```bash
# Display current working directory
pwd

# Create a new directory
mkdir git-for-devops

# Change directory
cd git-for-devops/

# List files in the directory
ls

# Create files
touch rammiz.txt
touch shireen.txt

# List files to verify
ls

# Initialize a Git repository
git init

# Check the status of the repository
git status

# Add files to the staging area
git add rammiz.txt shireen.txt

# Commit files with a message
git commit -m "first file committing"

# Set Git username and email
git config --global user.name "Ramiz-Takildar"
git config --global user.email "ramiz.takildar@gmail.com"

# Check the status again
git status

# View commit history
git log

# Create and switch to a new branch
git checkout -b dev

# Create a new file on the 'dev' branch
touch jannat.txt

# Add the new file to staging
git add jannat.txt

# Commit the new file with a message
git commit -m "jannat added on dev branch"

# View the Git log
git log

# Switch back to the master branch
git checkout master

# View a condensed Git log
git log --oneline
