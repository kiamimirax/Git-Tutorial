# Overview

1. Click the fork button and create a fork of this repo
2. Goto VS CODE and clone the repo
3. Add a line to the `README.MD` saying who you are and something interesting about you


### Making your first changes
Use the `git add`, `git commit -m 'your message'` and `git push` to add your changes to GitHub
or
Use the Source Control in VS code to stage commit and push your changes


### Part 2
Your going to get grab someone elses fork and make another change to the `README.MD`.

Your going to write sentence saying another interesting fact about yourself (if there is only one interesting about you then lie)

To do so we are going to need to add a new remote using `git remote add` and then making a branch using `git checkout -b <branch name>` to add a new place for us to make our edits

Once we are done the owner of the repo will merge you changes into main


### Part 3 - Working Within the same branch

Depending on how much of the project is done on our own or in a group the odds of us having our own branch to work on at all times is unlikely

We are going to simulate that problem by having two people makes changes and to the `README.MD` and then having one pull down the changes of the other
