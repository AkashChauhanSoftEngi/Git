# GIT

### Git
```text
* Reference
  - https://www.youtube.com/watch?v=HVsySz-h9r4
  - https://git-scm.com

## Version Control
* Git is a distributed version control system(VCS)
* SVN (Subversion) is a Central version control system

## Set Config values
* git config user.name "XXX"
* git config user.email "YYY@gmail.com"
* git config --list

## Initialize directory as a git repository
* git init {add .git folder or make it a git repository}

## List all the files with all privileges
* ls -la

## Remove directory {ex: .git}
* rm -rf .git

## Current Branch
* git status {which branch + untracked files}

## Create a .gitignore file {to not store some files in our local repository}
* touch .gitignore {Add example *.ml in gitignore file}

## Add files to staging area
* git add .gitignore
* git add -A {to add all}

## Remove files from staging area
* git reset fileName.exe
* git reset {remove everything from staging area}
* git status

## Flow at local
* working Directory->Staging area->.git repository{git status(untracked files), git add -A, git commit}

## Commit flow
* git add -A
* git commit -m "Message here!"
* git status
* git log {commited id, author, date, message}

## Clone a remote repository
* git clone <URL> <Where to clone>{. means in present directory}

## To see, all the local & remote branches
* git branche -a

## Push changes
* git diff
* git status
* git add -A
* git commit -m "Message here!"
* git pull origin master {origin: remote repository, master: branch}
* git push origin master

## Working with a new branch
* git branch branchName
* git branch
* git checkout branchName
* git status
* git add -A
* git commit -m "Message here!"
* git push -u origin branchName
* git branche -a
* git checkout master {at local}
* git pull origin master {from remote}
* git branch --merged {branches merged so far}
* git merge branchName {merge branchName with checked out branch}
* git push origin master

## Delete branch
* git branch --merged
* git branch -d branchName {local}
* git branch -a
* git push origin --delete branchName {remote}

## Commit changes to local repository
* First add changes to stage area then, execute
* git commit -m "Message here!"

## Descard changes in a file
* git checkout -- filename.extention
* git checkout -- . {undo all the files}

## Revert changes in local & remote repository
* git log {copy the commitId}
* git revert -n commitId -> git status -> git commit -m "Message here!"
* git revert commitId {not explicit commit is required} -> :q + enter

## Clear terminal
* git clear

## Reset {to a particular commit & delete all the chages after that commit}
* git log
* git reset --hard commitId

## Tips
* Must pull before push to remote repository when many people are working on the same branch
```

### Git-Gui
```text
* Reference : https://www.youtube.com/watch?v=ov3_CkObQm8

## Commands to use git-gui at Mac/Terminal
* git gui

## Create a new local Repository
* Get to the location by terminal
* type git Gui, it will open up an Interface and create a .git folder inside
* Add file and make changes inside this folder
* Stage -> sign off -> commit

## Push to remote
* Remote-> add -> fetch from remote repository
* push -> choose remote repository

## Fetch from Remote
* Remote-> add -> fetch from remote repository


## Clone from Remote
* new folder -> git gui -> clone repository
* choose source{remote} and destination{local}
```

### Intellij + Git {Terminal + VCS}
```text
## Create new local & remote branch
* VCS-> Enable

```
