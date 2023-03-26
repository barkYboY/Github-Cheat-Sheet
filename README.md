# Hi barKys :-)
Remember your git sh!t.

## To clone:
```
git clone https://github.com/barkYboY/Hello-world
```
## To authenticate or login:
```
gh auth login
```

## To push and then some:

###  1: add files to your up load list:
```
git add <files>
```
##### or add all files under current directroy
```
git add .
```
### 1a:To check <files> to push status with:
```
git status
```

### 2: Add message and generate commit file
```
git commit -m "message for this <files> change "
```
##### or update only changed files(no new files added)
```
git commit -m "message for this update to <files>" -a
```
### 3: Pusblish local changes with remote server
```
git push origin master
```
##### or in lazy fasion
```
git push
```
### 4: pull changes that you didn't put there
```
git pull
```

### 5: Setup new repo from existing project like TopPage
```
rm -rf .git
git init
gh repo create  #push local repository . and answer interactive questions
git branch -M main
git add .
git commit -m "Initial setup of repo"
git push --set-upstream origin main
```
### 6: Updating a branch
```
git checkout [branchname]
git merge [main]
#resolve any conflict diversions of branch
git push
```
### 7: Noteworthy commands
##### Program that shows difs well
```
git diff
gitk
```
###### note when you say clone locally it creates the project dir.

### 8: Other useful stuff related to branches and such
```
git fetch    #updates listings with remote
git checkout <branch_name>  #checkout a branch
git config --list  #show you what's in config
git switch <branch_name> #use - to flip through used list
```
### 9: Check out the tutorial for what's past this
```
info gitturtorial
```

##And always remember to breath when you push, cause, you know why!
