# Git for Web Development Project
In this project you will be using the concepts learned in the Git for Web Development lesson to fork/clone/push/and submit a PR for each project during this sprint.

This project consists of two parts:

## Part One:
You will need to follow the Lambda School Git Workflow to add a file to this project follow the steps below:

- [x] Create your own version of this repo - Fork
- [x] Add your PM as a collaborator
- [x] Clone this repo
- [x] Create a branch `git checkout -b 'firstName-lastName'`
  - [x] Add a file to the project called `yourFirstName-yourLastName`.txt. This file can contain anything.
  - [x] Run your usual git commands for adding/commiting and pushing **Be sure to push to your branch!**
- [x] Create a Pull-Request to submit your work
  - [x] Use your own student fork as the base (compare across forks, base-fork -> master).
  - [x] Add your PM as a reviewer on the Pull-Request
- [x] PM then will count the Assignment as done by merging the HW back into master "STUDENT FORK".

## Part Two:
Go back and follow the same steps for your [UI-III-Flexbox project](https://github.com/LambdaSchool/UI-III-Flexbox) and your [User Interface - Great Idea Project](https://github.com/LambdaSchool/User-Interface).

In order to do this, you **do not** need to create new forks of these projects. Follow the steps below for each project:

- [x] ***Add your PM as a collaborator to your fork. 
- [x] Go into your project folder, make a new branch `firstname-lastname`
- [x] ***Add your first and last name to the README.md file in the project and save.
- [x] add/commit/and push to your own branch  **Be sure to push to your branch!**
- [x] Create a Pull-Request to submit your work
  - [x] Use your own student fork as the base (compare across forks, base-fork -> master).
  - [x] ***Add your PM as a reviewer on the Pull-Request
- [x] PM then will count the Assignment as done by merging the HW back into master "STUDENT FORK".

## Stretch
- [x] While the processes learned here will set you up to be successful in most situations, they are just the tip of the iceberg in learning Git. Independantly research the following topics to learn more about Git.
  - [x] Research and understand what a `merge conflict` is and how to resolve it.
          - https://help.github.com/en/articles/about-merge-conflicts
            - Merge conflicts happen when you merge branches that have competing commits, and Git needs your help to decide which changes to incorporate in the final merge.
            - To resolve a merge conflict, you must manually edit the conflicted file to select the changes that you want to keep in the final merge.

  - [x] Reseach the Git commands `pull`, `rebase`, `merge`. These commands will allow you to bring in changes that other developers push to the master branch.
          - git *pull* fetches the latest changes of the current branch from a remote and applies those changes to your local copy of the branch. Generally this is done by merging, i.e. the local changes are merged    into the remote changes. So git pull is similar to git fetch & git merge.
          - git *merge* layers the changes on top of one another
          - git *rebase* - Rebasing is an alternative to merging. Instead of creating a new commit that combines the two branches, it moves the commits of one of the branches on top of the other.
  
  - [x] Reseach the Git commands `reset `, `revert`, `clean`. These commands will allow you to go back and ammends previous commits you have made.
          - https://www.atlassian.com/git/tutorials/undoing-changes/git-clean
          - RESET: resetting completely removes a changeset, whereas 
          - REVERT: reverting maintains the original changeset and uses a new commit to apply the undo.
          - CLEAN: is to some extent an 'undo' command. Git clean can be considered complementary to other commands like git reset and git checkout. Whereas these other commands operate on files previously added to  the Git tracking index, the git clean command operates on untracked files.
- [ ] Research and set up a Graphical User Interface (GUI) Git console. 
        -https://git-scm.com/book/en/v2/Appendix-A%3A-Git-in-Other-Environments-Graphical-Interfaces


- [ ] Research and setup SSH keys with Github, so that you do not need to input your username/password each time you push. 
        - https://help.github.com/en/enterprise/2.15/user/articles/adding-a-new-ssh-key-to-your-github-account

