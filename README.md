# :stop_sign: Basic commands
  ### list all the existing files(tracked/modified/untracked/committed...etc):-
    git status
  ## Staging area
   ### Add a file to the staging area:-
    git add FileName.exten
   ### Add all the untracked files:-
    git add *
   ### Unstage the files:-
    git restore --staged FileName.exten
    git reset head FileName.exten
   ### List all the untracked files to remove:-
    git clean -n
   ### Delete all the untracked files:-
    git clean -f
  ## local repo :arrow_right: remote repo
   ### Add the staged files to the local repo:-
    git commit -m "commit message"
   ### Add the committed files to the remote repo:-
    git push RemoteName(origin) BranchName(master)
   ### Know the RemoteName:-
    git remote -v
   ### know the BranchName:-
    git branch
   ### Pull the changes from the remote:-
     git pull RemoteName
   ### initialize a repo:-
     git init
  
 
## 📑Notes
  * if you work on multiple projects >>create a new repo for each project
  * if you are about to add new features >>create a new branch for each feature
  * you don't have to connect to the remote while you're working on the local >> Finish all the work on the local then commit all the changes at once
