# Git 
---
## Git commands:

### comands for work with files

* \- cd - move to directory
* \- ls - show list of files and directories
* \- touch - create file
* \- mkdir - create directory
* \- rm - delete file
* \- rmdir - delete directory
* \- clip - copy file in buffer
* \- cp - copy file in other directory
* \- mv - mpve file in other directory
* \- vimtutor - tutorial for vim text redactor

### comands for work with local git 

* \- git init - create GIT repository
* \- git add - add file to GIT repository
* \- git rm - delete file from GIT repository
* \- git restore - return file to last state which saved
* \- git restore --staged - remove file from the stage
* \- git reset --hard - return to one of old commits
* \- git commit - create new commit
* \- git commit --amend - change the last commit, it will be calles text redactor(nano or vim)
* \- git commit --amend -m - change the message in the last commit
* \- git commit --amend --no-edit - change files in last commit without changing the message
* \- git diff - see difference in last commit and now file states
* \- git diff --staged - see difference in staged files too
* \- git diff hash1 hash2 - see difference in commits with hash1 and hash2

### comands for work with public repository

* \- ssh-keygen - generation ssh key for safety work
* \- ssh - connection public to repository
* \- git remote add - connection to public repository
* \- git push - upload local repository state to public repository
