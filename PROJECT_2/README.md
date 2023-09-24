# INITIALIZING A GIT REPO

Create a local folder on your PC , then on your terminal i.e gitbash, use the command below;

`git init`

![Alt text](<images/Initializing Git Repo.png>)

# MAKING COMMITS

Making commits means saving your changes. This can be done using the command below;

`git commit -m "commit message"`

![Alt text](<images/Committing your channges.png>)

# WORKING WITH BRANCHES

## CREATE AND LIST BRANCHES

Branches come in  handy when you want to work on a source code, create a new branch , so that all the changes can be made on that branch, after all the changes are made and are acceptable you can now merge the source code of the new branch to the main branch.

Command is `git checkout -b "newbranch"`

## LIST BRANCH

You can use the `git branch` command to list all the branches

![Alt text](<images/Create and list git branches.png>)

# SWITCH BRANCH

You can switch between branches by using the command `git switch "name of branch"` or by using `git checkout "name of branch"`

![Alt text](<images/Swiching branch using_git checkout command.png>)


# MERGING BRANCH

After edits have been made on the new branch, it can be merged with the main branch using the `git merge "branch name"` command.

Here a new branch "modification1"was created and the txt file was edited.
After we go back into the main branch to merge the txt file in the "modification1 branch" into the txt file in the "main branch".

![Alt text](<images/Merging branches.png>)


# DELETE BRANCH

After merging the new branch with the existing one , you can decide to delete the new branch.

use the `git branch -d "name of branch"` command to achieve this.

![Alt text](<images/Deleting Branch.png>)


