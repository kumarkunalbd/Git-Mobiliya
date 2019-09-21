# Implemeting the pull request automation for Mobiliya


#  Command implemented today

- git init: Intializes the git (new) directory.(Adding changes to test different set of changes on 2 branches)
- git add : Add changes to the staging area of git
- git config: do configuration related to git
- git status: Compare the status of various file in git staging area, working directory and currrent branch
- git commit: Commit the changes from Stagiung area to current branch
- git log: show the history (aka "log") of various commits.
- git show: show the differences in a single commit
- git diff: show the differenecs between working direcotry, staging area and  commits.
- git checkout: final clarification what git checkout does. This descrition was added after adding descritpion about stash command in stahs branch. this checout the branch name and switch to that branch. It also update the HEAD.
- git stash: stash all changes from working directory by creating a stash pointer in .git
- git stash list: list all stashes 
- git stash pop: apply stahs changes to working directory on that branch from where it was stahed. need to checkout that branch before popping up. 
- git branch -c: Create a new branch. But remain on previous branch. Dint switch to new branch.
- git merge: It merges the changes of 1 brabnch to another branch
- git branch: list all branches
- git branch -b <branch_name>: create a new branch and then switch to it.

## what is a branch?
    A branch is ref(ence) to commit id. when HEAD point to a branch then we say that we are on that branch.
    When a commit is done whike we are on that branch, then that branch is updated to ref(er) to new commit id.

## what is HEAD?
    It is just a ref(erence) to the current branch. "git checkout <branch_name>"  uodate the HEAD to ref(er) to a new branch or say the commit id.



# Commit messages
    - use default editor vim to tyope commit messagees and the esc+wq
    - alternatively you can use "git commit -m <"the message need to be wrotten here"> "

# What is merging?
Merging is combining code changes from one branch to another branch.

- A fats forward merge happenes when the target branch was taken out of the current branch. when it is merged with the current branch then current branch moves ahead of target branch when any further commits happen on current branch.

- an automatic merge happens when 2 logs or history diverged or get branched themselves. However, noth of them can be brought together or reconciled with help of merge command give that they dont hasve conflict. this reconciled into 1 set of cnages and changes are committed on current branch.

# what happens when different set of changes in 2 branches while merging?
    In that case changes of bith branches are incorporated while merging(If they are not conflicting)
