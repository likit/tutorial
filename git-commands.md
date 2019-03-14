# Git commands

- git clone <repo> # copy/download from remote repo(origin)
- git status # view status of a file with changes
- git log # view log messages/commit history
- git add <filename> # stage/add modified file
- git commit -m <message> # commit a change
- git diff <filename> # view difference between versions/files
- git push origin <branch> # upload/sync with the remote repo
- git fetch origin # download from the remote repo
- git merge origin/master # merge/sync with the remote repo

## Create project repo on github

- Create a project repo on github.com
- Make a copy of the project
- cd project
- git init
- git add .
- git commit -m 'first commit'
- git remote add origin <repo url>
- git push
