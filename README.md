git-practice-for-anyone
=======================
This is a repository that anyone can use to learn and practice git with.
You can use this repository to complete the exercise described here: https://zhaol.github.io/ee491f/#git-github-exercises

Before Starting
===============
Read through these tutorials:
1. https://medium.com/@zhao.li/how-to-create-a-new-git-project-8dbb293d4227
1. https://medium.com/@zhao.li/how-to-save-and-load-code-in-git-baa65d22231a
1. https://medium.com/@zhao.li/how-to-share-code-in-git-6aa9cc0eb063
1. https://medium.com/@zhao.li/how-to-collaborate-on-code-in-git-f15effebfb17

Sign up for a free GitHub account here: https://github.com/join

If you want to practice the feature branch method described in the tutorials, then request access to the repository so you have the ability to commit, merge, and push to the repository like you would if this was a team repository.

If you want to get practice contributing to an open source project, then you can treat this as an open source repository that you do not have privileges to. In order for your contributions to be made to the repository, you would need to use pull requests: https://help.github.com/articles/about-pull-requests/

Please follow the `README.pull-request.md` for pull request instructions: https://github.com/zhaol/git-practice-for-anyone/blob/master/README.pull-request.md

I recommend trying the feature branch method first and then giving the pull request a try afterwards.

Exercise Steps
==============

## Clone this repository
```
git clone https://github.com/zhaol/git-practice-for-anyone.git
```

## Create and jump to a new branch
```
git checkout -b feature/your_branch 
```

## Make changes by creating, modifying, or deleting files
For this exercise, the suggested change is to add a file with some general content like an introduction, quote, etc. Name the file with your name or alias/username or alter-ego.

Also, insert your name into the guest list, `guest-list.txt`. Preferably in alphbetical order.

### Stage your changes
```
git add .             #add all of your changes
git add your_name.txt #add certain files
```

### Commit your changes
```
git commit -m 'add your commit message description'
```

## Fetch latest changes from remote repository in case others have squeezed in their changes before you
```
git fetch origin
```

## Bring your local master branch up to date with the remote master branch
```
git checkout master
git rebase origin/master
```

## Merge your changes
```
git checkout master
git merge feature/new_branch --no-ff
```

## Push your changes to the remote repository
```
git push origin
```

## Done
Congratulations, you have just contributed to your team's repository using the feature branch workflow! :)

Feel free to add more changes using more feature branches.

other git commands
==================
```
git status
git branch
git pull
git reset
git rebase
git log
git revert
git diff
```

git GUI clients
===============
Using a GUI client is the best way to visualize what's going on when starting out
http://git-scm.com/downloads/guis

git references
==============
https://www.atlassian.com/git/tutorial
