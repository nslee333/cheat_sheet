## Git commands

git init

git status -> view local / remote git status

git add . -> stage all current changes for commit

git commit -m "<commit message>" -> commit changes with git message

git push -> push changes to remote

git branch <branch_name> -> make a new branch

git checkout <branch_name> -> switch to branch

git branch -d <branch_name> -> delete branch

git stash -> stash changes locally

git stash pop -> unstash changes back to work environment

git restore . -> discard all unstaged changes



to keep a main branch pointing to a main repo, instead of your own forked repo
`git remote add upstream <url.com>`
`git fetch upstream`
`git branch --set-upstream-to=upstream/main main`


hint: if you have a local commit that's causing a merge conflict, you can use this command to 
deleted your commit without destroying your progress.
`git reset --soft HEAD~1`
