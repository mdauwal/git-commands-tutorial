# Introduction to Git
Git is a distributed version control system used for tracking changes in source code during software development. It enables collaboration, manages versions, and provides powerful tools to review and roll back changes.

# Installation: 
Download Git:

For Windows: git-scm.com
For macOS: brew install git
For Linux: sudo apt-get install git (Ubuntu/Debian)

# Verify installation:
git --version

# Configure Git
git config --global user.name "Muhammad Auwal"
git config --global user.email "muhammad.email@gmail.com"

(These commands set your identity for commits)

# Check configuration
git config --list

# Committing
1. Initialize a repository:
git init (Creates a new Git repository in your project directory.)

2. Add files to the staging area
git add <file-name>
git add . (Add all files)

3. Commit changes
git commit -m "Commit message"

# Branching
1. Create a new branch: 
git branch <branch-name>

2. Swicth to a branch
git checkout <branch-name>

3. Create and switch to a branch
git checkout -b <branch-name>

# Merging
Merge a branch into the current branch:
git merge <branch-name>

# Diffing
1. View changes:
git diff

2. View staged changes:
git diff --staged

# Stashing
1. Save uncommitted changes:
git stash

2. Apply the committed stash:
git stash apply

# Undoing changes:
1. Undo the last commit (keep changes):
git reset --soft HEAD~1

2. Undo changes in a file:
git checkout -- <file-name>

# Fetching and Pushing
1. Fetch changes from the remote repository:
git fetch

2. Push changes to the remote repository:
git push origin <branch-name>

# GitHub Odds and Ends
1. Clone a repository:
git clone <repo-url>

2. Link a local repository to GitHub:
git remote add origin <repo-url>

3. Push a new repository to GitHub:
git push -u origin main

# Rebasing
Rebase a branch:
git rebase <branch-name>

# Git Tag
1. Create a tag:
git tag <tag-name>

2. Push a tag:
git push origin <tag-name>

# Reflogs
View reflog:
git reflog

# Custom Aliases
1. Create aliases for common commands:
git config --global alias.st status
git config --global alias.co checkout
git config --global alias.br branch
git config --global alias.cm commit

2. Use the alias:
git st # For status



