#我的github上传

#my first time to modify this file.

#generate ssh-key, xxxx is your mail address
# ssh-keygen -t rsa -C "xxxx@xxxxx.com"

#check your local connected to GitHub server
# ssh -T git@github.com

#config email
# $ git config --global user.email "mihooke@hotmail.com"

#check user email
# $ git config user.email

#new branch
# git branch moery_branch

#switch moery_branch
# git checkout moery_branch

#delete branch from local
# git branch -D moery_branch

#delete branch from remote
# git push origin --delete moery_branch

#add modifid-file to local
# git add READNE.md

#commit modifid-file to local
# git commit -m "add some command with comment"

#see files status
# git status

#add&commit
# git commit -a -m "add some command with comment"

#merge branch code
# git merge moery_branch

#git stash, stash current modify, continue other modify, then you can continue stash modify
# git stash

#stash pop/clear
# git stash pop
# git stash clear

#recovery history version
#first look for the version you want to recovery
# git reflog
#then recovery, for example a commit-id is ba4f4e0
# git reset --hard ba4f4e0