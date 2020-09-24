## How to use git?
### How to make and save changes
* Make changes in working directory.
* Check git status ``git status`` - all files that are not in staging area
are marked red.
* Add changes to the staging area.
``git add [.] [-A] [options]`` - add all changes to staging area.
* Check git status - all the files that are in staging area are marked green.
* If you've changed your mind about saving any of the files, just use 
```git rm --cached <file name>```
* Save(commit) files to you local Git repo.
```git commit [-am] ["message"]```
* Push changes to your remote repo.
```git push [origin] [<branch name>]```
