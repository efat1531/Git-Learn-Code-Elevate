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

## Git Environment

- `Working` Here the files looks like previous/last commit.
- `Staging` Here fhe files were moved to temporary location before commit.
- `Commit` A new log entry created with a new HEAD.

## Files State

- `Tracked` These are the files existed in previous commit.
  - `Unmodified` Files have not changed since last commit.
  - `Modified` Files have changed since last commit.
  - `Staged` Files have been moved to staging.
- `Untracked` These files are new files with no previous commit.

## Restore files

- > git restore -S `filename`

This command is used to restore the file from staging.

- > git restore .

This command is used to restore the directory to last commit. Note this cannot used to delete `Untracked Files`. We need to delete `Untracked Files` Manually.

## Git Ignore

- `.gitignore` file used to when we do not want to share some files to the repository.
- This files ignores everything that is listed in the file.

> If we use `.gitignore` file after few commits we might need to delete our cache. To delete cache we can use `git rm -r --cached .`. It will delete all the files added recursevily. If we still want to delete all the files from previous commits we can use this tool **[BFG Repo Cleanner](https://rtyley.github.io/bfg-repo-cleaner/)**.

