

Follow this process if you want to push changes, but you need to pull remote changes first.

1. Check if there's changes from remote (repo)
	- `git status`
2. If changes to be pulled, stash your changes.
	- `git stash`
3. Pull changes from remote.
	- `git pull`
4. Apply your stashed changes.
	- `git stash apply`
5. Add, commit and push your changes.
	- `git add .`
	- 'git commit -m "commit message"
	- `git push`
6. All done :)
