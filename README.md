# Introduction to Git

Git is a distributed version control system used for tracking changes in source code during software development. It enables collaboration, manages versions, and provides powerful tools to review and roll back changes.

## Installation
To get started with Git, download and install it from [Git's official site](https://git-scm.com/). After installation, configure your username and email:

```bash
git config --global user.name "Muhammad Auwal Yahaya"
git config --global user.email "muhammad.auwal@gmail.com"
```

## Git Basics
### Initializing a Repository
To create a new Git repository:
```bash
git init
```
This creates a `.git` directory to track changes.

### Checking the Status
To check the current status of your repository:
```bash
git status
```

## Committing
### Adding Changes
To add files to the staging area:
```bash
git add <file_name>
```
Or add all files:
```bash
git add .
```

### Committing Changes
To save changes to the repository:
```bash
git commit -m "Commit message"
```

## Branching
### Creating a Branch
```bash
git branch <branch_name>
```

### Switching Branches
```bash
git checkout <branch_name>
```
Or using:
```bash
git switch <branch_name>
```

## Merging
To merge branches:
```bash
git merge <branch_name>
```

## Diffing
To view changes:
```bash
git diff
```

## Stashing
To save changes without committing:
```bash
git stash
```
To apply stashed changes:
```bash
git stash apply
```

## Undoing Changes
To undo changes in the working directory:
```bash
git checkout -- <file_name>
```

## Fetching and Pushing
### Fetching Changes
To download changes from a remote repository:
```bash
git fetch
```

### Pushing Changes
To upload local changes to a remote repository:
```bash
git push
```

## Upstreams and Downstreams
### Setting Upstream Branch
To set an upstream branch for tracking:
```bash
git branch --set-upstream-to=<remote>/<branch>
```

### Pulling Changes
To pull changes from the upstream branch:
```bash
git pull
```

## GitHub Introduction
GitHub is a platform for hosting Git repositories. It provides tools for collaboration, pull requests, and issue tracking.

### Cloning a Repository
To clone a repository from GitHub:
```bash
git clone <repository_url>
```

### Working with Pull Requests
1. Push your changes to a branch on GitHub.
2. Open a pull request to merge the changes into the main branch.

## Git Tag
To create a tag:
```bash
git tag <tag_name>
```
To push tags to a remote repository:
```bash
git push --tags
```

## Reflogs
To view reference logs:
```bash
git reflog
```

## Custom Aliases
To create custom Git commands:
```bash
git config --global alias.<alias_name> '<git_command>'
```
Example:
```bash
git config --global alias.co checkout
```

## Additional Resources
For more information, visit the [official Git documentation](https://git-scm.com/doc).

---
This guide provides a comprehensive overview of Git commands, GitHub usage, and advanced topics like upstreams and downstreams to enhance your Git workflow.
