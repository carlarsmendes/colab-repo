# Collaboration & Collaborative Repo (In construction)

## Objective of this repo

This repo was created in order to add practice some collaboration strategies for project 2.
It will be a simulation for your real working environment where you will be working with other developers.

## How to start with a colab repo?

* One person from the team should create a new repo
* On Settings, add the other team members as collaborators
* You can either git clone or fork the project *(clone is more common for smaller projects)*
* Link your local repo to your remote repo and immediately do a succession of add-> commit-> push to see if everything is OK

## Some golden rules

* Write good commit messages!
* Decide earlier on on the divisions of tasks so that you avoid working on the same files
* Have a trello board (or similar) to divide your tasks
* Always have antoher team member as a reviewer of your Pull Request (PR)
* Commit often and as soon as an individual feature (or fix) is working
* Test your code before opening a PR and/or merging
* Make sure your branches are coming from your master branch
* Pull the most recent code and fix your conflicts before merging your PR
* Always make sure you're working with the most recent codebase
* Delete your branch onde you're done with it - Keep your branches tree clean!
* Decide on code formatting rules from the start, *Eg.: Everyone uses Prettier, or no one uses it*
* Version control DOES NOT replace communication. Keep your team updated on your current work tasks

## Useful Git commands

* ```git branch``` See all the created branches
* ```git branch first_branch``` Create a new branch called first_branch
* ```git checkout first_branch``` Start working from the first_branch branch
* ```git checkout - myCode``` Reset directory "myCode" to its original state (undo local changes)
* ```git log``` To see all your commits on the terminal
* ```git add .``` Add your latest changes to your current stream
* ```git commit -m "Your commit message here"``` Commit with a commit message
* ```git push --set-upstream origin first_branch``` First time pushing your changes to your first_branch remote branch
* ```git fetch``` Downloads the new changes from the remote repository but does not change your local repository. Think of it as checking the state of the remote repository.
* ```git pull``` Downloads the new changes from the remote repositories and update your local repository
* ```git commit --amend -m "New message"```  Edits a commit message. This creates a new commit
* ```git reset HEAD-2``` Undo last 2 commits (locally) and keep changes
* ```git reset --hard HEAD-2``` Undo last 2 commits (locally) and discard changes
* ```git reset filename``` Remove a file from the staging area
* ```echo filename >> .gitignore``` Adds file to .gitignore file
* ```git revert c856893c ``` Revert pushed commit c856893c
* 
