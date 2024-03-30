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

git long -n 5 -> git log limit to last 5 lines

to keep a main branch pointing to a main repo, instead of your own forked repo
`git remote add upstream <url.com>`
`git fetch upstream`
`git branch --set-upstream-to=upstream/main main`


hint: if you have a local commit that's causing a merge conflict, you can use this command to 
deleted your commit without destroying your progress.
`git reset --soft HEAD~1`

git rebase -i is great for rewriting commit history.
 - if you rewrite the history, and the remote history is longer than yours, you might need to use a `git pull --force` to update it.

git reflog 
  - Helpful for dealing with messed up commit history, will bail you out.

also don't be afraid to create a new branch as a save point, then you can modify the commit history with a backup branch as an insurance policy





