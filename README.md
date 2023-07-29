`THE COMPLETE GUIDE TO GIT AND GITHUB`


`git init` -> Initialises an empty repository.It also creates a .git folder that
 that has all the relevant logic to manage versions of your project.This .git
 folder is a hidden folder.

`Working Area` -> Files that are not currently monitored by git.It means that changes done or future changes will not be tracked by git.
  A file present in working area is considered not to be present in the staging area.
  When we do `git status ` we see a bunch of untracked files.

`Staging Area` -> Files that will be part of the next version of the software/product.The staging area 
   is the place where git will come to know what changes will be done from last version to the next version.

`Repository Area` -> this area contains all details about previous
 registered versions.

`git add <file>` ->moves file from working area to the staging area.

`git rm--cached <file>` moves file back from staging area to working area.

`commit` -> Commit is a particular version of  a project.It takes a snapshot of the staged changes and creates a version out of it.

`git log` -> We will able to see all commits.Press q to exit from git log.

`git restore <file>` -> removes all file changes from staging area to be commited.Can be useful,If we did some wrong code and dont need it anymmore.

`git  restore --staged <file>`-> removes file changes from staging to working area 

Difference between git rm and restore
ans:If we want to move the whole file back to untracked state then we do git rm,else if we just want changes to be moved in working area or staging area then we use 
git restore.

`git commit -m "message here "` -> If we want to avoid opening a text editor while commiting then we can do the needful.

`git remote` -> list down all remote connections.

`git remote add <name of remote> <link of repo>`-> adds new link to remote repo and give a name to it.

`git remote rm <name>` -> deletes remote connection.














