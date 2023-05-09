CHAPTER 1: BASIC KNOWLEDGE
Lesson 1: Setting git
Checking git version: git –version
Config name & email: git config -g user.name yourname
git config -g user.email youremail
Checking name & email: git config user.name
git config user.email
Lesson 2: Git
Making a repository for project: git init
Checking status of project: git status
Checking and prepare to save change of project: git add – git add .(save all)
Cancel prepare save previous: git reset
Save change: git commit -m "message"
List all commit info: git log/git log --oneline
Roll back to specific commit: git checkout {git id}
Roll to the newest – the present commit: git checkout {branch name}
Checking branch name: git branch
Creat a new branch: git checkout -b {branch name}
File only appear in the branch where it was created
Merge branch: git merge {name of branch that will merge with the present branch}
Delete branch: git branch -d {branch name}
Lesson 3: Github
Up load repository on github: git push HTTPs
Update change for repo on github: git push HTTPs {branch name}
Set elias to reuse HTTPs faster: git remote add #name
Cloning project to local device: git clone HTTPs
Push local branch onto github: git push -u origin {branch name}
Pull branch from github: git fecth
Git checkout -b {branch name} origin(elias)/{branch name}
Pull change from github: git pull
