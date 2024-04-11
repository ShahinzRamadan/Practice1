# :stop_sign: Basic commands
  ### list all the existing files(tracked/modified/untracked/committed...etc):-
    git status
  ## :small_orange_diamond: Staging area
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
  ## :small_orange_diamond: local repo :arrow_right: remote repo
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
# :stop_sign: Git configuration
   ### List most available configurations:-
     git config --list
     git config --l
   ### List all available configurations:-
     git help config
   ### Set a value for a specific configuration (userName):-
     git config --global user.name "YourUserName"
   ### Show the value of a specific configuration (userName):-
     git config --global user.name
   ### Remove the value of a specific configuration (userName):-
     git config --global --unset user.name
     git config --global user.name ""
  ## :small_orange_diamond: Aliases:-
   ### Set an alias (st) for a command (git status):-
     git config --global alias.st status
   ### Set an alias (cm) for a multi-word command (git commit -m):-
     git config --global alias.cm "commit -m"
   
  
# 📑Notes
  * If you work on multiple projects >>create a new repo for each project
  * If you are about to add new features >>create a new branch for each feature
  * You don't have to connect to the remote while you're working on the local >> Finish all the work on the local then commit all the changes at once
  * If you set an alias for a command >>this doesn't mean that the original command won't work >>both of them will do the job
  * When you set an alias for a command you have to make sure that the alias you set doesn't make any conflicts with existing commands >>you can do so by googling `git alias list` and you will find a whole list of preset aliases that don't make any conflicts
