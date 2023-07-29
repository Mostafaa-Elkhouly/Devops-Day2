# DevOps Day2

# To Remove a Remote Branch
- git push origin :dev
- git push origin :test

# To Remove a local Branch
- git branch -d dev  or git branch -D dev
- git branch -D test or git branch -D test 

# To Checkout Another Branch Without Commit Changes
- git status
- git stash
- git checkout <branch-name>
- git stash apply --> To apply the stashed changes back to my working directory after switching to the new branch.

# To List Tags
- git tag

# To Delete Tag Locally
- git tag -d v1.7

# To Delete Tag Remotely 
- git push origin --delete v1.7

![Git Icon](images/git-icon.png)

