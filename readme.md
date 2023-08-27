#Git Command
`git status`
Check status for files

`git add .`
add all files to staging area

`git restore --staged .`
to remove staged files from staging area
also we can give specific file names i.e test.html test1.html

`git commit -m "commit description"`
to make commit in local repository
-m stands for message

`git remote -v`
to check remote repository
-v stands for verbose (to show log)

`git log`
to show git logs

`git push`
push changes to remote repository

`git branch -M main`
change the master branch name with main

`git remote add origin https://github.com/the-ik-world/DevOpsGFGDay1.git`
add variable name origin and store git repo url

`git push -u origin main`
push main branch to origin url

`git clone git-repo-url`
clone repo from git


`git remote set-url origin git@github.com:username/your-repository.git`
set origin url of git repo