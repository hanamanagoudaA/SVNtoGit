# Cloning a repository:
``git clone <link from GitHub>``<br/>
``git flow init`` 
<br/>
<br/>
---
# Get current status (what branch are we on, what files have changed):
``git status``
<br/>
<br/>
---
# See local branches:
``git branch``
<br/>
<br/>
---
# Change/set the current branch:
``git checkout  <branch_name>``
<br/>
<br/>
---
# See remote branches:
``git branch -r``
<br/>
<br/>
---
# Update local copy with changes from remote:
``git pull``
<br/>
<br/>
---
# Creating a feature branch from develop:
``git checkout develop``<br/>
``git pull``<br/>
``git flow feature start  <branch_name>``
<br/>
<br/>
---
# Creating a bugfix branch from develop:
``git checkout develop``<br/>
``git pull``<br/>
``git flow bugfix start   <branch_name>``
<br/>
<br/>
---
# Pushing a branch to the server:
``git status``&nbsp;&nbsp;&nbsp;*Verify you are on the branch to be pushed.*<br/>
``git push --set-upstream origin  <branch name>``
<br/>
<br/>
---
# Commit changes to local branch
``git status``               *# See what changes are available to commit*<br/>
``git add <file>``        *# add a single file or directory to the changes to be committed*<br/>
``git add .``               *# add all unstaged changes under the current directory*<br/>
``git commit m “this is a commit message”``        *# do the commit*
<br/>
<br/>
---
# Push committed changes from local to remote:
``git push``
<br/>
<br/>
---
# Merge completed branch to develop and remove the completed branch:
``git status``&nbsp;&nbsp;&nbsp;*verify all changes are committed and pushed.*<br/><br/>
*If necessary git add, git commit, and git push:*<br/>
-``git add .``<br/>
-``git commit -m “commit message goes here”``<br/>
-``git push``<br/><br/>
*Merge branch to develop and delete it:*<br/>
``git checkout develop``<br/>
``git pull``<br/>
*If a feature branch:*<br/>
``git flow feature finish  <branch_name>``<br/>
*If a bugfix branch:*<br/>
``git flow bugfix finish  <branch_name>``   
<br/>
<br/>
---
# If your branch is out of date with develop, use rebase to apply the develop changes into your branch:
``git status``<br/>
``git pull --rebase origin develop``<br/>
*if you get merge conflicts at this point, fix the file that has the conflict:*<br/>
``git add <fixed file>``<br/>
``git rebase --continue``<br/>
*if the rebase failed and you want to back up to where you were:*<br/>
``git rebase --abort``
<br/>
<br/>
---