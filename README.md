# Git_basics
Basics of Git and GitHub necessary to get started

## Why use Git and GitHub

Git provides useful local tools to manage version history and branching allowing for easier code management and collaboration. GitHub provides an online repository to share modifcations recorded locally by Git. 

## Basic commands for Git

git init

git clone &lt;repo url&gt;

git status

git add

git commit -m '&lt;insert message here&gt;'

git log

git branch (list branches)

git branch &lt;name-of-new-branch&gt;

git branch -a (see all branches on GitHub)

git checkout &lt;name-of-branch&gt;
  
git diff FIRST-BRANCH..SECOND-BRANCH (compare differences between branches)

git branch -D BRANCH-TO-DELETE

git merge NAME-OF-BRANCH-TO-MERGE-WITH
  
git remote add origin &lt;repo URL&gt; (link local directory to remote GitHub location)
  
git remote -v

git fetch &lt;remote-repo&gt; &lt;remote-branch&gt;:&lt;local-branch&gt; (retrieve remote branch and store it in new local branch)

git pull (retrieve pushed changes from GitHub repo)

git push (upload committed changes to GitHub)

git push -f origin master (upload local files to "origin" repo master branch)

git push -u origin feature_branch_name

git push origin --delete &lt;branch_name&gt;

To clone all branches:

git clone --mirror URL(including .git) .git

git config --bool core.bare false

git reset --hard

To clone specific branch:

git clone -b name_of_branch URL

To start fresh git log, you need to remove the old .git file:

WARNING: following cannot be undone

rm -dfr .git

git init 

## .gitignore file

This is a hidden file (hence the full stop at the start of the file name) that informs Git about what it should exclude from its tracking. This is useful because there may be large files, such as images, or hidden files in your directory with sensitive information that you may not want uploaded onto GitHub

## Basic commands for command line

[List of Command Line Commands](https://www.codecademy.com/articles/command-line-commands)

## Useful websites

[Git docs](https://git-scm.com/doc)

[How to write a commit message](https://chris.beams.io/posts/git-commit/)

[cheetsheets from someone called "Rico"](https://devhints.io/), eg. [git log](https://devhints.io/git-log)



