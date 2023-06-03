``` Fetch command
git fetch <remote> <branch>
Fetches a specific <branch>, from the repo. Leave off <branch> to fetch all remote refs.
git merge
it merges to current working directory

If your workspace has no uncommitted files, and you want to copy the latest changes from a remote repository directly into your working directory, then issue the git pull command.
//fetch just give the update status whether there are any changes or not.
If you want to pull down the latest changes from a remote repository without overwriting anything in your working directory, then use git fetch, and then do
 a git merge when the time is right.
 Working Directory/Workspace --------> Staging area --------> Local Repo --------> Remote Repo
                             git pull/git reset --hard <remote/branch>
   <---------------------------------------------------------------------------------
                         git merge/git rebash                         git fetch
   <-----------------------------------------------------------<---------------------- 