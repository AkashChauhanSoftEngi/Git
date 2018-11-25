# GIT

### Git
```text
* Reference
  - https://www.youtube.com/watch?v=HVsySz-h9r4
  - https://git-scm.com/videos

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

## Create new local & Remote branch
* 

## Create new local & Remote repository

## To see, all the local & remote branches
* git branche -a

## Add changes to stage
* git add -A

## Commit changes to local
* Add changes to stage
* git commit -m "Message here!"

## Delete local & remote branch
* git -d

## Revert changes in local & remote repository
* got --delete

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
