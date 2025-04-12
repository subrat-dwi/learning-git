>intialize git within the new project folder
`git init`

>make changes

>to check the status of files
`git status`

>to put *untraced files* on stage
1. `git add .` for all untraced files
2. `git add <filename>` for particular

>to commit the  changes
`git commit -m "message"`

>to remove a staged file
`git restore --staged <filename>`

>to see the history of commits
`git log`

>to go reset back to an older state
`git reset <hash>`

>to put traced files backstage i.e. on waiting
`git stash`

> to connect local project to GitHub repo
`git remote add origin <repo-url.git>`

> to push the project to github.
`git push -u origin master` for first time to set upstream
`git push` afterwards

---

>to clone a forked repo `git clone <forked-url>`

> to add upstream url
`git remote add upstream <upstream-url>`

>to create a new branch
`git branch <branch>`

>to put head on the branch
`git checkout <branch>`

> to sync fork main with upstream main
`git pull upstream main`