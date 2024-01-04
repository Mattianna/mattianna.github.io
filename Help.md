# Starting the Server
open a terminnal
cd Documents/mattianna.github.io/
make serve
navigate to http://127.0.0.1:4001/stephanie-website/ (or whatever it says on terminnal)

If config file is updated...
	Stop server: control-C in the terminal window that is running the server
	Then restart, type: make serve

# Git
Open a terminal
cd Documents/mattianna.github.io/
git status
	displays current state
git diff
	displays changes since last commit
git add FILE NAME
	includes FILE in next commit
git commit -m "notes"
	updates
	if -m is excluded opens vim...
		to esc type-- :wq 
			this saves commit message and returns to the terminal
git push
	pushes updates to github and eventually updates running cite
git pull david master
	pull changes from David's version
	if merging...
		successful: opens vim, :wq 
		unsuccessful: 2 options 
			resolve yourself and try and edit the files that conflict, then: git commit -a
			abort: git merge --abort
renaming things: git mv OLD FILE PATH NEW FILE PATH
