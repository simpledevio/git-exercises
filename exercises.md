# Git Exercises

## Steps



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
