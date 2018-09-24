Pull Request Instructions
=========================
These are the instructions to perform a pull request. It is most often used to contribute to open source projects that you do not have access to.

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

## Push your changes to the remote repository
```
git push origin feature/your_branch
```
then use the Github website to finish up the pull request.

## Done
Congratulations, you have just contributed to an open source repository using a pull request! :)

Feel free to add more changes using more pull requests.
