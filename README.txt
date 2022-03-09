Git And Git HUB
Git is tool having following features , while GitHub is a site used to host local repository, so that can be used from anywhere.(remote access)
1. Clonning
   ..Clonning a remote repo to local repo
   ..git clone <reposotiry address>

2. Version Control- Using git Locally on computer

   ..git init 
   ..git add <file>
   ..git commit -m "<Message>"
   ..git log
   ..git status
   ..git diff
   ..git checkpoint //rollback to previous version

3. Git and Remote Repositories

   ..by using gitHub
   ..create new repo 
   ..on the Host(remote) system add/setup repositry through repositry link provided by GitHub when 
     you create new repo.
   ..git remote add origin https://github.com/rustyboy0908/GitEssentials.git
   ..git push -u origin master
   ..Using gitHub we have remote repository

4. Branch and Merging
   ..For development project its good practice to have a experimental brach(to debug or add new feature) so that all the hit and 
     trialmethod does not affect the Master branch.
   ..git branch <new branch name>      // creating branch .
   ..git branch                 // current branch information.
   ..git checkout <branch name> // switching to branch .
   ..go to master branch then merge the other branch
   ..git merge <branch name>
   ..do git push from your master branch itself.
   ..Git changes will be reflected on the gitHub.

5. Optional Git Challenge
6. Forking and Pull Request
   .. Mering via interface with method GitHub Pull request.
7. Gitignore

  ..git rm --cached -r . //for removing all the files which have beed add to git
