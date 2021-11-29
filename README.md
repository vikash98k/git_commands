# GIT_commands
* git add -A
* git status 
* git init
* git clone project-link
* git push 
* git checkout
* git log
* git commit -m "message"
## Before commit
* git checkout -- filename `undo for last change in perticular file`
* git checkout -- . `undo for all file changes`
## After commit
* git revert commit_id `find git commit_id using git log` [:q for close] 
* git revert -n commit_id  `same as above line command`
* git reset --hard commit_id 
### Branches
* git branch branch_name `[git checkout -b branch_name]`
* git checkout branch_name `switch the branch`
## merge
* git merge branch_name
* git push --set-upstream origin branch_name `push in anohter branch`
## delete 
* git branch -d branch_name
# difference between two commit
* git difftool commit_id_1 commid_id_2  `git difftool HEAD~2 HEAD~1`
## git commands for exists repo
* git init
* git add -A
* git commit -m
* git remote add origin `url `
* git push -f origin master/main
* git pull `depands of git requirements`
* git fetch `fetch data`
### change master to main vice versa also
* git branch -m master main
* git branch -m main master 

######## contribute 
* fork
* clone
* create branch
* changes and commit
* pull
* git remote add upstream `git url link`
* git checkout main branch
* git fetch upstream
* git merge upstream
## Resource
  [Article](https://www.c-sharpcorner.com/article/top-15-git-commands-with-examples-for-every-developers/)
