# Git Commands Cheat Sheet

A quick reference guide for commonly used Git commands.

## Configuring Git

-   `git config --global user.name "Your Name"`: Set your name for commits.
-   `git config --global user.email "youremail@example.com"`: Set your email for commits.

## Creating Repositories

-   `git init`: Initialize a new Git repository in the current directory.
-   `git clone <repository_url>`: Clone a remote repository to your local machine.

## Making Changes

-   `git status`: Check the status of your working directory and staged changes.
-   `git add <file>`: Stage changes of a specific file for the next commit.
-   `git add .`: Stage all changes in the working directory for the next commit.
-   `git commit -m "Commit message"`: Commit staged changes with a descriptive message.
-   `git commit -am "Commit message"`: Stage and commit all changes in one command.

## Branches

-   `git branch`: List all branches in the repository.
-   `git branch <branch_name>`: Create a new branch with the specified name.
-   `git checkout <branch_name>`: Switch to an existing branch.
-   `git checkout -b <branch_name>`: Create a new branch and switch to it.
-   `git merge <branch_name>`: Merge changes from the specified branch into the current branch.

## Remote Repository

-   `git remote add origin <repository_url>`: Link your local repository to a remote repository.
-   `git push -u origin <branch_name>`: Push your branch to the remote repository.
-   `git pull`: Fetch and merge changes from the remote repository.
-   `git fetch`: Download changes from the remote repository without merging.

## History

-   `git log`: View the commit history.
-   `git log --oneline`: View a concise commit history.
-   `git log --author="Your Name"`: View commits by a specific author.
-   `git show <commit_hash>`: View detailed information about a specific commit.

## Undoing Changes

-   `git reset HEAD <file>`: Unstage changes of a specific file.
-   `git checkout -- <file>`: Discard changes of a specific file in the working directory.
-   `git revert <commit_hash>`: Create a new commit that undoes changes introduced by a specific commit.
