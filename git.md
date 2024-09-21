## Git commands

git init

git status -> view local / remote git status

git add . -> stage all current changes for commit

git commit -m "<commit message>" -> commit changes with git message

git push -> push changes to remote

git branch <branch_name> -> make a new branch

git checkout <branch_name> -> switch to branch

git branch -d <branch_name> -> delete branch

git branch -u or --set-upstream-to=origin/<branch_name> <local_branch>
  - this is useful for setting the upstream of a branch.

git stash -> stash your changes.

git stash apply -> apply stashed changes into the current working tree state.

git stash pop -> unstash changes back to work environment, ** WILL DELETE STASH CONTENTS **

git restore . -> discard all unstaged changes

git reset --soft HEAD~1 -> undo the latest commit and save change

  - you can also use git reflog to look at the history, and go back and reset any changes you made
  - by doing git reset HEAD@{n of changes ago, 0 being current}

git log -n 5 -> git log limit to last 5 lines
git log --oneline -> oneline commit msgs


git diff [branch] [remote]/[branch] view differences between remote and local

git diff origin/branch..origin/branch -> view differences between two upstreams

git reflog -> view all ref updates, super helpful.



to keep a main branch pointing to a main repo, instead of your own forked repo
`git remote add upstream <url.com>`
`git fetch upstream`
`git branch --set-upstream-to=upstream/main main`


hint: if you have a local commit that's causing a merge conflict, you can use this command to 
deleted your commit without destroying your progress.
`git reset --soft HEAD~1`

git rebase -i is great for rewriting commit history.
 - if you rewrite the history, and the remote history is longer than yours, you might need to use a `git push --force` to update it.
 - git rebase -i HEAD~5
    - rebase 5 commits in log.
    - `squash` to combine squashed commit into previous commit.
git reflog 
  - Helpful for dealing with messed up commit history, will bail you out.

also don't be afraid to create a new branch as a save point, then you can modify the commit history with a backup branch as an insurance policy

resolving merge conflicts:
- timeline:

- pull changes down, merge conflict with files.

- resolve merge conflicts by pulling it down and opening up vscode and resolving one-by-one

- after you get it all done git will generate a git merge commit, you can get rid of this commit by using `git rebase -i` which will simply drop the merge commits, that way you don't have a silly merge commit that gets pushed up.

- then simply continue with regular programming


