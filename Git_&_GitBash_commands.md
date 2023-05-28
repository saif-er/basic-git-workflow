/////////////////////////////////////////////////////////////////////////////////////////////////////////////////

# BASH COMMANDS

## `cd folderName`

- change directory.

## `cd ..`

- move one folder up.

## `del fileName`

- delete file or folder.

## `rm fileName`

- delete file or folder.

## `mv fileName ../folederName`

- move file up the current folder.

## `mv fileName ./folederName`

- move file down the current folder.

## `rmdir directoryName`

- removes directory.

## `rm -R folderName`

- removes folder without warning.

## `cd folderName`

- change directory.

## `new-item`

– create a new file of any type.

## `touch 'filename_withouth_quotes'`

- this will create new file.

## `vim 'file name'`

- to edit the file.
- Once Vim is open, you will be in "Normal" mode. To switch to "Insert" mode and start editing the file, press the `i` key. You will see -- INSERT -- at the bottom of the screen. When you're done editing, press the `Esc` key to return to "Normal" mode. To save the changes and exit Vim, type the this command `:wq`

## `cat fileName`

- to look into the content of the file.

## `echo "todolist.txt" > .gitignore`

- this command will write the passed text into the file.

## `ls`

- list all files

## `ls -la`

- list all the files along with hidden files.

/////////////////////////////////////////////////////////////////////////////////////////////////////////////////

# NPM COMMANDS

## `npm install -g packageName`

- this will install the package globally.

## `npm install packageName` or `npm i packageName`

- this will install the package locally in the project folder.

## `npm uninstall <package-name>` or `npm uninstall -g <package-name>`

- To uninstall the package locally or globally.

## `npm list --depth=0`

– this will list all the installed packages in the current directory.

/////////////////////////////////////////////////////////////////////////////////////////////////////////////////

# GIT COMMANDS

## Confuguring Git -

## `git config --global core.autocrlf true`

## `git config --global core.safecrlf true`

- Git will check every single character of the file. This command is for line endimgs, so line engings made on different platforms will be picked up, this will eliminate any conflicts.

## `cat ~/.gitconfig`

-Now check the config file, by using this command

## `ssh-keygen -t RSA`

- Creating an SSH key

## `cat ~/.ssh/id_rsa.pub`

- Now print the public version of this key.

## `git tag`

- to list the tags available.

## `git tag -a v1.0 -m 'added first tag`

- this will create a tag and associate this tag to the last commit. And tag the first production release

## `git show`

- this will show all the details which are in this perticuler tag.

## `git push --tags`

- this will push the tags to the main remote repo.

## `git init`

– initialize an empty git repository (local)

## `git config --global user.name gitHubUserName`

- this will be used to connect the local repository to github remote repository.

## `git config --global user.email gitHubEmail`

- this will be used to connect the local repository to github remote repository.

## `git status`

– returns the list of untracked files.

## `git add -A` or `git add .`

– add all the files to the staging area and are tracked, to make them part of the repository.

## `git commit -m ‘commit message’`

– a commit is a snapshot of the code at a certain point of time, at every significant change in the code we usually commit. -m stands for message and the commit message is in the quotes.

## `git reset --hard HEAD`

– if we want to go the previous commit after some modification, this command will take back to previous commit.

## `git log`

– log of all the commits.

## `git log --oneline --decorate --graph --all`

- this will show all the commits in a nice representable way.

- commit id - a5a0e9921249665d80ed32d3a73938905d2c4de6.

## `git branch`

– list all the branches.

## `git branch nameOfTheNewBranch`

– creates a new branch.

## `git checkout nameOfTheBranch`

– to switch to the desired branch.

## `git merge nameOfTheBranch`

– this will merge the passed name branch to the current branch into which we are currently working.

## `git remote add origin gitHub_repo_url`

- this will let our local repository know about the GitHub remote repository and connect them both. Here 'origin' is the name which we are assigning to the remote repo, we can use any name apart from 'origin'.

## `git push remote_repo_name branchName` (e.g. `git push origin main`)

# MIT LICENSE

- This will push all the local changes in the repo to the remote repo on the gitHub.

Copyright 2023 Mohammad Saifuddin

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

# Some more common Git commands

## `q`

- to quit out of `git log` command.

## `cd /d`

- change the root directory

## `git init`

– initialize an empty git repository (local)

## `git config --global user.name gitHubUserName`

- this will be used to connect the local repository to github

## `git config --global user.email gitHubEmail`

- this will be used to connect the local repository to github

## `git status`

– returns the list of untracked and changed files

## `git add -A`

– add all the files to the staging area and are tracked, to make them part of the repository

## `git add`

– add the files to the staging area and are tracked, to make them part of the repository

## `git commit -m ‘Initial_commit_message’`

– a commit is a snapshot of the code at a certain point of time, at every significant change in the code we usually commit. -m stands for message and the commit message is in the quotes.

## `git reset --hard HEAD`

– it will go back to previous commit (if we want to go the previous commit after some modification)

## `git log`

– log of all the commits

commit id - a5a0e9921249665d80ed32d3a73938905d2c4de6

## `git branch`

– list all the branches

## `git branch nameOfTheNewBranch`

– creates a new branch

## `git checkout nameOfTheBranch`

– to switch to the desired branch

## `git merge nameOfTheBranch`

– this will merge the passed name branch to the current branch into which we are currently

## `git remote add origin https://github.com/saif-er/forkify.git`

- this will let our local repository know about the GitHub repository and connect them both

## `git push github_branchNametoPushTO branchNameToPush`

- (e.g. git push origin master) this will push the local branch to the github repository.

## `git clone github_repository_link`

- this will create a clone of the online github repository in your local folder. And then we can put all the files in that folder to connect our local project to the github repo.

## `git add .`

- add multimple files to the staging area.

## `git push`

- to push the latest changes to the github repo.

## `git pull`

- to pull the latest changes from the github repo.

## `git pull origin main`

- to pull the latest changes from the github repo.

## `git branch -m master main`

- change the branch name from master to main on the local repository.

## `git push origin --delete master`

- delete the branch name master from the github repository.

## `git clone --branch <branchname> --single-branch <remote-repo-url>`

    or

`git clone -b <branchname> --single-branch <remote-repo-url>`

- to only fetch files from the specified branch without fetching other branches.

## `git branch -D <branchname>`

- to delete a branch locally.

## `git push -u origin <branch>`

- push a new local branch to a remote Git repository and track it too.

# - Git pulling a branch from another repository.

## `git remote add fork <url of fork>`

## `git fetch fork <branch>`

## `git checkout -b fork_branch fork/<branch>`

## `git remote remove fork`

- If you do not need to track the fork

# Cloning a git repository into a new git repository

## `git remote rm <origin>`

## `git remote add origin <url>`

## `git push -u origin main`

## `git push --mirror`

- to push all branches to remote

## `git push -u origin <branch>`

- to push only the selected branch
