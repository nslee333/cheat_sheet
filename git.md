## Git commands

git init

git status -> view local / remote git status

git add . -> stage all current changes for commit

git commit -m "<commit message>" -> commit changes with git message

git push -> push changes to remote

git branch <branch_name> -> make a new branch

git checkout <branch_name> -> switch to branch

git branch -d <branch_name> -> delete branch





to keep a main branch pointing to a main repo, instead of your own forked repo
`git remote add upstream <url.com>`
`git fetch upstream`
`git branch --set-upstream-to=upstream/main main`
