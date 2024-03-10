# :stop_sign: Basic commands
  ### list all the existing files(tracked/modified/untracked/committed...etc):-
    git status
  ## Staging area
   ### Add a file to the staging area:-
    git add FileName.exten
   ### Add all the untracked files:
    git add *
   ### Unstage the files:-
    git restore --staged FileName.exten
    git reset head FileName.exten
   ### List all the untracked files to remove:-
    git clean -n
   ### delete all the untracked files:-
    git clean -f
  ## local repo :left_right_arrow: remote repo
   ### Add the staged files to the local repo:-
    git commit -m "commit message"
   ### Add the committed files to the remote repo:-
    git push RemoteName(origin) BranchName(master)
   ### know the RemoteName:-
    git remote -v
   ### know the BranchName:-
    git branch
   
 
 ### Practice pull request:-
  team admin

  This Is Note 

  this is second note
