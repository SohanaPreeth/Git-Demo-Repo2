# Header - Demo 2

Creating file in local machine and sending it to remote repo
intially it was not in GIT repo later we use 'GIT init' to send it to GIT repo

First create a empty repo in the remote machine, later use 'git remote add origin path'
'git remote -v' will shows the remote repos that are connected to the local repo.

## Sub Header - Branches 
get inside the Git-DEmo-Repo2 by using 'cd Git-DEmo-Repo2'.
'git branch' will give the branches that are present in the repo and the highlighted will be the current branch that we are working at.
'git checkout -b feature_branch-name' helps to shift from branch to branch and -b is for creating a new branch.
These are the changes thata are done in feature branch, we are saving these changes in the feature branch, so these changes will not reflect in master file, untill and unless we merge the files.
we use 'git commit -am "message"' directly to track and save the changes and push this changes in the remote repo.