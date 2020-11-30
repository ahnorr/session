# Git
# NEW BRANCH
 - Git is officially defined as a distributed version control system (VCS).
 - It's a system that tracks changes to our project files over time. It enables us to record project changes and go back to a specific version of the tracked files, at any given point in time.

## How to Download Git

 -  Download git from this [url](https://git-scm.com/downloads)
 - Check if git is downloaded by using ` git --version`
 
## Config Email ID and Name 

 - git config --global user.name "Your Name" 
 - git config --global user.email "your@email.com"
```
 Note :- 
    - Git is seperate from github and gitlab
    - Git is the program that supports github and gitlab
    - You can use git without either of those
 ```

## Repositories
   To create a new repository and start tracking your project with Git, use your terminal software and navigate to the main folder of your project, then type the following command:
```bash
    git init
```
Check the changes that are made:- 
```bash
    git status
```
 Add files that you want to change:- 
```bash
    git add <filename>
    git add .
```
Commi the changes:-
```bash
    git commit -m "<message>"
    git commit 
```

Add the repo URL:
```bash
    git remote add origin <url>        
    git push --set-upstream origin master
```


## Commit History
Check the commit history using:-
```bash
    git log
```
Go the to necessary commit by using:-
```bash
    git checkout <commit-hash>    
```
To go back to the latest commit use:-
```bash
    git checkout master
```
## Branches
See all branches by using 
```bash
    git branch
```
Create a new branch
```bash
    git branch <branch_name>
```
Go to the new branch
```bash
    git checkout <branch_name>
```
Commit changes in branch
```bash
    git push origin <branch_name>
```

Now to update the merge the changes in the new branch to master go to master branch using
```bash
    git checkout master
```
Then merge the changes using
```bash
    git merge <branch_name>
```

Then commit the changes

## Clone Project 
If u want to create a local copy of the repo then use the clone command
```bash
    git clone <url>
```
