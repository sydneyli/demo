

```

Informational
=============
git status                       Look at tracked files
git diff                         Looks at all un-committed changes
git diff --stat                  Look at a summary of un-committed changes
git diff master                  Look at the changes I've made on the current branch

Committing
==========
git add <filename>               Add file to be tracked by git
git commit                       Commit changes.

Branch management
=================
git checkout -b <branch name>    Create a new branch
git checkout <branch name>       Go to branch
git branch -D <branch name>      Delete branch

Remote management
=================
git pull                         Pull changes from remote
git push origin <branch name>    Push changes to remote branch

Advanced
========
git rebase master                "Rebase" my changes onto master branch

Other
=====
git grep <to find>               Look for <to find> in files
 - I use this a lot when navigating a new large codebase. It's faster than grep and
   is limited to files tracked by git.

For everything else, I just use google.


```
