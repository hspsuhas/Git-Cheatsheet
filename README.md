# Git-Cheatsheet

## Introduction
This Git cheatsheet provides a quick reference for commonly used Git commands. Whether you're a beginner or an experienced developer, use this guide to help you navigate through various Git operations.

### Configuration
- Set your name: `git config --global user.name "Your Name"`
- Set your email: `git config --global user.email "your.email@example.com"`

## Basic Commands
- Initialize a new repository: `git init`
- Clone a repository: `git clone <repository_url>`
- Check the status: `git status`
- Add changes to the staging area: `git add <file>`
- Commit changes: `git commit -m "Commit message"`
- Push changes to a remote repository: `git push origin <branch>`
- Pull changes from a remote repository: `git pull origin <branch>`
- Create a new branch: `git branch <branch_name>`
- Switch to a branch: `git checkout <branch_name>`
- Create and switch to a new branch: `git checkout -b <branch_name>`

## Working with Branches
- List all branches: `git branch`
- Delete a local branch: `git branch -d <branch_name>`
- Delete a remote branch: `git push origin --delete <branch_name>`
- Merge a branch into the current branch: `git merge <branch_name>`
- Resolve merge conflicts: Manually edit files, then `git add` and `git commit`

## Viewing Changes
- Show changes between commits: `git diff <commit_hash1> <commit_hash2>`
- View commit history: `git log`
- View a specific file at a specific commit: `git show <commit_hash>:<file_path>`

## Undoing Changes
- Discard changes in the working directory: `git checkout -- <file>`
- Unstage changes: `git reset <file>`
- Amend the last commit: `git commit --amend`

## Remote Repositories
- Add a remote repository: `git remote add <name> <repository_url>`
- Rename a remote: `git remote rename <old_name> <new_name>`
- Show remote repositories: `git remote -v`
- Fetch changes from a remote repository: `git fetch <remote>`
- Set upstream branch: `git branch -u <remote>/<branch>`

## Tagging
- Create a lightweight tag: `git tag <tag_name>`
- Create an annotated tag: `git tag -a <tag_name> -m "Tag message"`
- Show tags: `git tag`
- Push tags to remote repository: `git push origin <tag_name>`

## Submodules
- Add a submodule: `git submodule add <repository_url> <path>`
- Clone a repository with submodules: `git clone --recursive <repository_url>`
- Update submodules: `git submodule update --init --recursive`

## Miscellaneous
- Ignore files globally: Add patterns to `.gitignore` or use global ignore file: `git config --global core.excludesFile ~/.gitignore_global`

## Conclusion
This cheatsheet covers essential Git commands for common workflows. Feel free to explore Git's extensive features and options as you become more comfortable with version control.
