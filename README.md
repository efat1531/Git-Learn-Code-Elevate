
# Code Elevate Workspace

## What is git

Git is a open source version control system.

## Global Config Commands

### User Name

 > git config --global user.name "your name"

This command is used to setup your workspace user name globally for all of your git repositories.

### User Email

 > git config --global user.email "your email"
  
This command is used to setup your workspace user email globally for all of your git repositories.

## Git initialize

> git init

This command is used to initialize your git repository.

## Git status

> git status

This command is used to check the status of your git repository.

## Git Staging

### Stage the changes in the filename file for commit

> git add `filename`

This command is used to stage the changes in the filename file for commit.

### Stage all changes in the directory

- > git add --all
- > git add -A
- > git add .

Those commands are for staging changes for commit

## Git Commit

> git commit -m "Commit Message"

This command is used to commit the changes into git local repository.

### Special

> git commit -am "Commit Message"

This command stages all the changes and commit the changes into local repository.

# Git-Learn-Code-Elavate
This reposotory is only to see git commands


# CodeElevates first day
Learning how to work with git & github with my team. Wants to learn some advance topic together. I Will know about how to resolve conflict, open new branch. I know the daily use git commands. 


# Key Topics Covered

## Resolving Git Conflicts

1. Manually resolve the conflict in the file (e.g., `README.md`)
2. Stage the resolved file using `git add README.md`
3. Commit the resolved conflict with a descriptive message using `git commit -m "Resolve merge conflict in README.md"`
4. Push the resolved conflict to the repository using `git push`

## Git Stash

1. Stashing allows you to store your current work in a temporary place, without committing it.
2. This is useful when you need to switch to a different branch but don't want to commit your current changes.

## Git Reset

1. `git reset --hard <paste_your_head_value>` allows you to go back to a specific commit, discarding all the changes since that commit.
2. The `<paste_your_head_value>` represents the commit hash or reference (e.g., `HEAD`, branch name) that you want to reset to.

These are the main topics covered in the provided information, which includes:

- Resolving Git conflicts
- Using Git Stash
- Resetting Git to a specific commit using `git reset --hard`


