# Git_basics
Basics of Git and GitHub necessary to get started

## Why use Git and GitHub

Git provides useful local tools to manage version history and branching allowing for easier code management and collaboration. GitHub provides an online repository to share modifcations recorded locally by Git. 

## Basic commands

git init

git clone &lt;repo url&gt;

git status

git add

git commit -m '<insert mesage here>'

git log

git branch (list branches)

git branch <name-of-new-branch>

git checkout <name-of-branch>
  
git diff FIRST-BRANCH..SECOND-BRANCH (compare differences between branches)

git branch -D BRANCH-TO-DELETE

git merge NAME-OF-BRANCH-TO-MERGE-WITH
  
git remote add origin <repo URL> (link local directory to remote GitHub location)
  
git remote -v

git fetch <remote-repo> <remote-branch>:<local-branch> (retrieve remote branch and store it in new local branch)

git push -f origin master (upload local files to "origin" repo master branch)

git push -u origin feature_branch_name

git push origin --delete <branch_name>

## useful websites

[cheetsheets from someone called "Rico"](https://devhints.io/), eg. [git log](https://devhints.io/git-log)



