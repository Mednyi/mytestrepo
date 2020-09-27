## How to use git?
### How to initialize local repo
* Move to newly created folder 
(use cd command in Git Bash terminal and drag'n'drop folder to terminal from explorer)
* Use ```git init``` in Git Bash terminal
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
* Add origin repo to your local repo settings
```git remote add origin git@github.com:Mednyi/mytestrepo.git```
* Set local branches to track remote and push changes
```git push -u origin master```
or
```git push [origin] [<branch name>]``` if branch is already tracked

### How to change current branch
```git checkout <branch name>```

### How to get (pull) changes from remote repo
* Check status remote repo status using
```git fetch```
* Pull changes from remote repo if any.
```git pull```

### How to make pull-requests
* Make, commit and push some changes per "How to make and save changes"
* Create pull-request on github (any other VCS) from branch you're on to
branch you want the changes to be transferred
1. Go to "Pull requests page"
2. Create pull request
3. Specify from which branch you want to make pull request and to which one 
(Warning: Arabic people created this feature)
4. Go through pull-request (Merging, commit pull request ...) phases
