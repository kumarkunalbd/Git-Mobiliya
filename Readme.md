# Implemeting the pull request automation for Mobiliya


#  Command implemented today

- git init: Intializes the git directory
- git add : Add changes to the staging area of git
- git config: do configuration related to git
- git status: Compare the status of various file in git staging area, working directory and currrent branch
- git commit: Commit the changes from Stagiung area to current branch
- git log: show the history of various commits.
- git branch: list all branches
- git checkout: this checout the branch name and switch to that branch. It also update the HEAD.
- git branch -b <branch_name>: create a new branch and then switch to it.

## what is a branch?
    A branch is ref(ence) to commit id. when HEAD point to a branch then we say that we are on that branch.
    When a commit is done whike we are on that branch, then that branch is updated to ref(er) to new commit id.

## what is HEAD?
    It is just a ref(erence) to the current branch. "git checkout <branch_name>"  uodate the HEAD to ref(er) to a new branch or say the commit id.

# Commit messages
    - use default editor vim to tyope commit messagees and the esc+wq
    - alternatively you can use "git commit -m <"the message need to be wrotten here"> "