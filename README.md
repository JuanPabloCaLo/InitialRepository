Initial repository for learning git tools (with Visual Studio Code Insiders).
  git init -> Initialize repository.
  git config --global user.name "YourName" -> Sets your username as the one you wrote between the "".
  git config --global user.email email@emailservice.com -> Sets your email as email@emailservice.com.
  git add . -> Adds a change in the working directory.
  git commit -m "message" -> Captures staged changes and adds "message" as a description of them.
  git commit --ammend -> Edits the commit parameters (the "message" is an example). 
  git push --set-upstream origin branch name -> Initial push anytime a new branch is created.
  git push -> The remote changes are uploaded to github repository.
  git push --force-with-lease -> Safer option than git push --force, allows pulls to be made after ammends in the committ and other actions. 
  git branch -> Returns the branches that exist and marks green the active one.
  git branch name -> Creates a branch called name.
  git checkout name -> Switches to branch called name.
  git pull -> downloads changes in the remote repository to update local one
  
