# Implemeting the pull request automation for Mobiliya


#  Command implemented today

- git init: Intializes the git directory
- git add : Add changes to the staging area of git
- git config: do configuration related to git
- git status: Compare the status of various file in git staging area, working directory and currrent branch
- git commit: Commit the changes from Stagiung area to current branch
- git log: show the history (aka "log") of various commits.
- git checkout: final clarification what git checkout does. This descrition was added after adding descritpion about stash command in stahs branch.
- git merge: It merges the changes of 1 brabnch to another branch

# Commit messages
    - use default editor vim to tyope commit messagees and the esc+wq
    - alternatively you can use "git commit -m <"the message need to be wrotten here"> "

# What is merging?
Merging is combining code changes from one branch to another branch.

- A fats forward merge happenes when the target branch was taken out of the current branch. when it is merged with the current branch then current branch moves ahead of target branch when any further commits happen on current branch.

# what happens when different set of changes in 2 branches while merging?
    In that case changes of bith branches are incorporated while merging(If they are not conflicting)
