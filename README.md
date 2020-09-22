# git-github
Some useful commands:

git init

git remote add origin "LINK"          .....# to get files from github to git

git pull origin master

git status .....# tells you which files are added to index and are ready to commit

################################################

git add NameFile.EXT  .....# lets you add files to your INDEX in order to be commited

git commit -m "adding first commit in local repo not to central repository"

################################################

git add -A .....# lets you add all files to your INDEX to be commited

git commit -a -m "adding three files toguether to local repository not to central"

################################################

git branch BranchName .....# To create a new branch 

git checkout BranchName .....# To switch to branch BranchName

################################################

(assuming we are in master branch)

git merge BranchName .....# to merge the branch BranchName to Master branch

################################################

git rm -f FILE.EXT .....# to force to remove a file from directory, index and the commited area

################################################

git push -u origin master .....# to push files from local master branch to central master branch

################################################

touch .gitignore .....# to create a file directly from Git Bash

################################################


