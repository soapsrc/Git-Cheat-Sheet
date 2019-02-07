# Tutorial

Github Commands:<br>
git - check if we have github<br>
git -version - check version of our github<br>
git config -global user.name "Your Username"
local repository - located on your machine
  first commit our codes to our local repository
  then push it to the remote repository
  git add . - to index the changes
  git commit -m "the first commit"
  git status - branch should be updated
  git push origin master - push change to remote repo
    master - the branch
git clone
steps for committing a new change:
  make changes to file
  type in command line:
    git status
      to find the differences
    git add .
    git commit -m "commit title"
    git status
      should say "nothing to commit"
    git remote add origin "url of newRepo"
      add change to a new repo
    git pull origin master - remote repository
repo:
  can clone existing remote repo or init creating repo
 git clone - gets existing repo from remote
 git init - create own repo in local
  copy url
  right click in directory
  click git bash
  type in command line: git clone "url"
 how to check if we have .git format:
   cd "Project Name"
   ls --all
    list every file - used to check if we have .git
  
  Github website:
    Trace commits
 
