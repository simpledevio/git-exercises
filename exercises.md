# Git Exercises

## Steps
You can use this project for your first Git and GitHub repos. Use the index.html file to make changes.


### Initialize
Initialize your repository.
```
git init
```



### Stage
Stage your files.
```
git add .
```



### Commit
Commit your files.
```
git commit -m "Your message"
```



### Log
View your commit using git log.
```
git log
```

Repeat these steps at least 2 more times.



### Create branch
Create a branch called `dev-branch`.
```
git checkout -b dev-branch
```
Add some code to the index.html file and then stage and commit the changes.


### Merge branches
After adding new code and committing it, merge your changes back into the `master` or `main` branch (the name of your production branch may be different depending on how Git was set up on your computer).
```
git checkout master

git merge dev-branch
```
```
git checkout main

git merge dev-branch
```



### Delete branch
Use the following command to delete the `dev-branch`.
```
git branch -d dev-branch
```



### Discard changes
Write some code in `index.html`. Then use the following command to discard the changes.
```
git checkout -- index.html
```



### Unstage files
Practice unstaging files. First, add some code to `index.html`. Then stage the changes using `git add`. Then unstage them using `git reset`.
```
git add index.html

git reset HEAD index.html
```



### Edit last commit
Practice editing your last commit.
- First, add some code to `index.html`.
- Stage the changes using `git add`.
- Commit the changes. Then amend the message.
```
git add index.html

git commit -m "My commit message"

git commit --amend
```



### Undo your last commit
Use the following command to undo the commit from the previous exercise.
```
git reset --soft HEAD~1
```

# GitHub Exercises

## Sign up for GitHub
Sign up for an account on GitHub.

## Create a remote repository
Create a remote repository on GitHub.

## Add a remote repository to your project
Use the command from the tutorial to add the remote repository to your project.

## Push changes to your remote repository
Use the command from the tutorial to push your changes to GitHub.

## Create a pull request
This exercise requires that you have 2 branches. If you don't have 2 branches, you can create a 2nd one and make a commit on it. Then you can create the pull request. Then try merging the branches.

## Get changes from remote repository
Use the command from the tutorial to get the changes from your remote repository.
