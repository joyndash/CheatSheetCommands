# Ndanu's git cheatsheet 
 ![Git Repositories State](git\model.png)


## Configuration
### git config -1
Return a list of information about your git configuration including username and email.

## Status
### git status
Show the status of the current repository including staged,unstaged and untracked files.
### git log
Shows the commit history for the current repository.

## Manage Repository
### git init
Initialize a new git repo locally in your project root.
### git clone
Downloads an existing git repository to your local computer.
### git add .
Add all files in your project using a wildcard|.| to the staging area
### git add 'filename'
Add a file to the staging area.Replace filename with the name of the file.
### git commit -m 'your commit message'
Commits staged changes to the repository. A short summary for the commit message should be specified.
### git push
Saves the ready work on a remote repository.
### git push -f
Force a push request.Better for pull request branches because nobody else should have cloned.
### git pull
Retrieves the latest changes made to the remote repository.

