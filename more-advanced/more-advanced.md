1. The git revert command is a forward-moving undo operation that offers a safe method of undoing changes. Instead of deleting or orphaning commits in the commit history, a revert will create a new commit that inverses the changes specified.
The git reset is a command that is used to undo local changes to the state of a Git repo.

2. The git merge command lets you take the independent lines of development created by git branch and integrate them into a single branch. Note that all of the commands presented below merge into the current branch.
The git rebase is a branch updates one branch with another by applying the commits of one branch on top of the commits of another branch. For example, if working on a feature branch that is out of date with a dev branch, rebasing the feature branch onto dev will allow all the new commits from dev to be included in feature .
Merging is a safe option that preserves the entire history of your repository, while rebasing creates a linear history by moving your feature branch onto the tip of main .

3. git stash temporarily shelves (or stashes) changes you've made to your working copy so you can work on something else, and then come back and re-apply them later on.
git stash pop applies the top stashed element and removes it from the stack. git stash apply does the same, but leaves it in the stash stack.

4. Interactive rebase in Git is a tool that provides more manual control of your history revision process. When using interactive rebase, you will specify a point on your branch's history, and then you will be presented with a list of commits up until that point. With the interactive rebase tool, you can then stop after each commit you want to modify and change the message, add files, or do whatever you wish
