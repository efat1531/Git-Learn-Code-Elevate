# Code Elevate Workspace

## What is git

Git is a open source version control system.

## Global Config Commands

### User Name

 > `git config --global user.name "your name"`

This command is used to setup your workspace user name globally for all of your git repositories.

### User Email

 > `git config --global user.email "your email"`
  
This command is used to setup your workspace user email globally for all of your git repositories.

## Git initialize

> `git init`

This command is used to initialize your git repository.

## Git status

> `git status`

This command is used to check the status of your git repository.

## Git Staging

### Stage the changes in the filename file for commit

> `git add filename`

This command is used to stage the changes in the filename file for commit.

### Stage all changes in the directory

- > `git add --all`
- > `git add -A`
- > `git add .`

Those commands are for staging changes for commit

## Git Commit

> `git commit -m "Commit Message"`

This command is used to commit the changes into git local repository.

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

- > `git restore -S filename`

This command is used to restore the file from staging.

- > `git restore .`

This command is used to restore the directory to last commit. Note this cannot used to delete `Untracked Files`. We need to delete `Untracked Files` Manually.

## Git Ignore

- `.gitignore` file used to when we do not want to share some files to the repository.
- This files ignores everything that is listed in the file.

>***Note***: If we use `.gitignore` file after few commits we might need to delete our cache. To delete cache we can use `git rm -r --cached .`. It will delete all the files added recursevily. If we still want to delete all the files from previous commits we can use this tool **[BFG Repo Cleanner](https://rtyley.github.io/bfg-repo-cleaner/)**.

## Git Logs

- > `git log`

This command is used to check the git logs. But if there are many logs it will be a mess. So a better command is

- > `git log --oneline`

This command is used to check the git logs but there is only 1 log per line, so it is easy to read.

- > `git log --oneline --graph`

This command is used to check the git logs in one line with graph.

## Change History of git

### Amending

- > `git commit --amend -m "Commit Message"`

This command is used to ammend the last commit with new message.

- > `git commit --amend --no-edit`

This command is used to ammend the last commit without editing the commit message.

### Hard Reset

- > `git reset --hard HEAD`

This command is used to hard reset the git repository.

- > `git reset --hard filename`

This command is used to hard reset the git repository with filename.

### Soft Reset

- > `git reset --soft HEAD`

This command is used to soft reset the git repository.

- > `git reset --soft filename`

This command is used to soft reset the git repository with filename.

## Branches

Branches is the most powerful tool of git. It can use to create different version of code. Also many people can work on different features without any disturbance.

- > `git branches`

This allow us to see all the branches in the repository and at which branch I am working now with a star mark.

### Copy a branch

- > `git switch -c NAME`

This command is used to copy a branch.

### Create a branch

- > `git checkout -b NAME`

This command is used to create a branch.

### Switch a branch

- > `git checkout NAME`

This command is used to switch a branch.

### Delete a branch

- > `git branch -d NAME`

This command is used to delete a branch.
