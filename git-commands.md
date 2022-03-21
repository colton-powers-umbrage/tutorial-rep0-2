`git init` - Creates an empty repository or reinitializing an existing one

`git clone` - Clones a repository to a new directory

`git remote` - Manage set of tracked repository

1. `git remote add origin` - Adds remote repository to local one.

`git checkout` - Switch branches or restore working tree files

1. `git checkout -b <branch-name>` - create and switch to a new branch

`git branch` - list all of your current local branches

1. `git branch -D <branch-name>` - deletes a branch

`git status` - lists information about your branch

1. If your local branch is up to date with your remote branch
2. Which files are not staged for a commit. Colored red
3. Which files are ready to for a commit. Colored green
4. Which files are untracked

`git add` - Add file contents to the index

1. `git add .` - adds all files that have been changed to your staged changes list. These files are now ready to be committed.
2. `git add <file-name>` - adds specific file to your staged changes list.

`git commit` - Create a new commit containing the current contents of the index and the given log message describing the changes. 

1) `git commit -m "Commit Message"` - creates a commit and a message to go along with it 

2) `git commit -m "Header" -m "Description" -m "Footer"` - formatting a commit message by header, description, and footer.

`git pull` - Fetch from and integrate with another repository or a local branch

 1. `git pull origin <branch-name>` - fetches latest changes from remote branch to local branch.

`git push` - pushes your local changes upstream to your remote repository.

 1. `git push --set-upstream origin <branch-name>` - creates a new remote branch and pushes it upstream.

`git pull` - retrieves the latest changes from a remote branch.

`git commit -am` - adds and commits all your untracked files to your staged changes

`git checkout -` - navigates you to previous branch.

`git config --global alias.ac "commit -am"` - this creates an alias for any command you write a lot that you would want to shorten. ac represents the alias you choose and the command you want to use will be placed inside the quotes.

`git commit --amend -m` - changes your last commit message.

`git commit --amend --no-edit` - add files to last commit without changing the commit message.

`git revert c675693` - undo a commit with a new commit.

`git stash` - remove all changes from your current directory to use at a later time

`git stash save <name>` - saves your stash under a given alias.

`git stash pop` - adds changes back to the current working directory and removes it from the stash list

`git stash list` - see a list of all your stashes

`git stash apply "stash@{n}"` - applys a certain stash from your list. n represents the number in the list.

`git log --graph --decorate` - visualizes your codes history as a DAG graph in the cli.

`git commit --squash` - this lets git know that this commit will be squashed with another commit sometime in the future

`git rebase -i --autosquash` - after rebasing all your commits flagged with `--squash` will automatically be squashed.



made changes 


made more changes on new branch 