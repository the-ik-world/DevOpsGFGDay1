#Git Commands

`git init`
Initialize git repo 

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
set origin url of git repo if want to reset


`git branch b1`
- create new branch with name b1

`git branch`
-list of branches available  in git repo

`git checkout b1`
-switch to newly created branch b1


`git log --oneline`
- git logs will be in one line output

`git merge`
- merge two branches
i.e you are in main
 `git merge b1`
 b1 will merge in main
if it is b1 branch
 `git merge main`
 main branch will merge in b1
 
 
 
`vim editor`
 esacpe   :wq
 ESC + :wq + Enter
 
 save and quite 

  git  rebase b1 ??
 
 
 
 
`git branch -M b1`
 - change master branch name (wheare are you it rename branch name)


`git branch b1`

`git checkout b1`

instead we can use
`git checkout -b b1`

new Command =>
`git switch -c b1`
create and switch branch

`git branch -d b1`
- delete branch


`git branch -D b1`
- delete branch forcefully


---------------------------------------

revert upto perticualar commit

`git revert <commitId>`


git revert vs reset

revert maintain commit history back/forward
reset -> not maintant commit history

`git rest  --hard  <commit id>`
commit parrally -> --hard