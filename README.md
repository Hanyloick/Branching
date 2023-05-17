# Git Cheat Sheet

A list of common git commands.

## Basic Commands
* 'git init' - initializes local repository.
* 'git add .' - add (stage) current working folder content
to local repo index.
* 'git commit -m' "message" - commit staged work to local repo with commit message.

## Info Commands
* 'git status' - show commit status of cuttent local folder
* 'git log' - list commit history of local repo
* 'git log --oneline' - list commit history 'compact format'


## Branch Commands
* 'git branch' - list local branches.
* 'git branch -m newName' - rename current local branch.
* 'git branch newName' - create new local branch.
* 'git checkout branchName' - move to local branches.
* 'git branch' - list local branches
* 'git branch -m newName' - rename current local branch.

## Remote Commands
* 'git remote add remName remoteUrl' - commit local repo to remote repository.
'remoteUrl' with shortcut 'remName' for the remote URL.
* 'git push remName branchName' push local commits to remote branch.
* 'git pull origin main' - pull remote main into local branch