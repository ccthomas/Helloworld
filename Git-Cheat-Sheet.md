# Git Cheet Sheet
- [Install Git](#install-git)
- [Configure Tool](#configure-tool)
- [Create Repositories](#create-repositories)
- [Make Changes](#make-changes)
- [Group Changes](#group-changes)
- [Refactor Filenames](#refactor-filenames)
- [Suppress Tracking](#suppress-tracking)
- [Save Fragments](#save-fragments)
- [Review History](#review-history)
- [Redo Commits](#redo-commits)
- [Synchronize Changes](#synchronize-changes)

## Summary
- Initialize a Github Repo
  - `git init`
- Or Clone Existing
  - `git clone <link>
- Links to GitHub Repo
  - `git remote add origin [url]`
  - Example: `git remote add origin git@github.com:CCThomas/Helloworld.git`
- Snapshots the file in preparation for versioning
  - `git add [file]`
- Pull from Remote Brach
  - `git pull origin <branch-name>`
  - Always 'pull' before 'push' to avoid merge conflicts
- Push to Remote Branch
  - `git push origin <branch-name>`
- Records file snapshots permanently in version history
  - `git commit -m [descriptive message]`

## Install Git
GUI Interfaces
- [Windows](https://windows.github.com)
- [Mac](https://mac.github.com)

## Configure Tool
Configure user information for all local repositories
- Sets the name you want attached to your commit transactions
  - `git config --global user.name "[name]"`
- Sets the email you want attached to your commit transactions
  - `git config --global user.email "[email address]"`
- Enables helpful colorization of command line output
  - `git config --global color.ui auto`
  
## Create Repositories
Start a new repository to obtain one from an existing URL
- Creates a new local repository with the specified name
  - `git init [project name]`
- Downloads a projectand its entire version history
  - `git clone [url]

## Make Changes
Review edits and craft a commit transaction
- Lists all new or modified files to be committed
  - `git status`
- Shows file differences not yet staged
  - `git diff`
- Snapshots the file in preparation for versioning
  - `git add [file]`
- Shows file differences between staging and the last file version
  - `git diff --staged`
- Unstages the file, but preserve its contents
  - `git reset [file]`
- Records file snapshots permanently in version history
  - `git commit -m [descriptive message]`

## Group Changes
Name a series of commits and combine completed efforts
- Lists all local branches in the current repository
  - `git branch`
- Creates a new branch
  - `git branch [branch-name]`
- Switches to the specified branch and updates the working directory
  - `git checkout [branch-name]`
- Combines the specified branch's history into the current branch
  - `git merge [branch]`
- Deletes the specified branch
  - `git branch -d [branch-name]`

## Refactor Filenames
Relocate and remove versioned files
- Deletes the file from the working directory and stages the deletion
  - `git rm [file]`
- Removes the file from version control but preserves the file locally
  - `git rm --cashed [file]`
- Removes the directory from version control but preserves the file locally
  - `git rm --cashed -r [directory]`
- Changes the file name and prepares it for commit
  - `git mv [file-original] [file-renamed]`


## Suppress Tracking
Exclude temporary files and paths
- A text file named .gitnore suppresses accidental versioning of files and paths matching the specified patterns
  - ```
    *.log
    build/
    temp-*
    ```
- Lists all ignored files in this project
  - `git ls-files --other --ignored --exclude-standard`

## Save Fragments
Shelve and restore imcomplete changes
- Temporarily stores all modified tracked files
  - `git stash`
- Restores the most recently stashed files
  - `git stash pop`
- Lists all stashed changesets
  - `git stash list`
- Discards the most recently stashed changeset
  - `git stash drop`

## Review History
Browse and inspect the evolution of project files
- Lists version history for the current Branch
  - `git log`
- Lists version history for a file, including renames
  - `git log --follow [file]`
- Shows content differences between two branches
  - `git diff [first-branch]...[second-branch]`
- Outputs medadata and contentchanges of the specified commit
  - `git show [commit]`

## Redo Commits
Erase mistakes and craft replacement history
- Undoes all commits after [commit], preserving changes locally
  - `git reset [commit]`
- Discards all history and changes back to the specified commit
  - `git reset --head [commit]`

## Synchronize Changes
Register a repository bookmark and exchange verison history
- Downloads all history from the repositorybookmark
  - `git fetch [bookmark]`
- Combines bookmark's branch into current local branch
  - `git merge [bookmark]/[branch]`
- Uploads all local branch commits to GitHub
  - `git push [alias] [branch]`
- Downloads bookmark history and incorporates changes
  - `git pull`
