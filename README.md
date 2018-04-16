# mydevjourney

1. Master GitHub (because its essentials)
https://www.youtube.com/watch?v=MJUJ4wbFm_A (super great explanation about github.

what it used for,
1. Keep track to changes to code.
2. Collaborating with team is easier because its repo is syncing with people.
3. Testing changes in purpose to make it better without losing the original, yes you can copy paste project but what if you work on big project? its gonna be pain in the ass.
4. Work as time machine like in apple machine because you can revert back to previous version of your code in case changes you made messed up.

master this command line to use github efficiently, yes we love ugly terminal instead of beautiful GUI
1. git clone <url>
  - makes a copy of repository
  - stores it on your computer
  - a "fork" create your own copy of someone else's repository (think of it like bitcoin fork) so you can make changes and do testing as many as you want without messing the original repo.

2. git add
  - adds a modified file you wanted to commit to "staging area" (think of it like quality check befor shipping in factory)
  - tells git to include the file in the next revision to the repository.
  - the command itself (git add *adds all changed files)

3. git diff
  - show the changes made in repository, which line is been modified or you can say which line is different with the original file.

4. git commit -m "messages"
  - commit the file in staging area to repository, or you can say save the changes to repository as a new revision.
  - records a messages
  - git commit -am "message" adds and commit in same steps. means you dont need to using separate git add command.

5. git status
  - shows the status of repository, to make sense whats currently happening in repo such as changes, and show comparison between forked repo with original repo in terms of commit.
  
6. git push
  - push the current state of local repository to github repository, kind of final changes upon release of code.
  
7. git pull
  - retrieve changes from remote repository.
  - pull github repository to existing local forked repository and update it to current version of github repo.
  
Merge conflicts.
  - when two different commits can't be automatically merged
  - need to be resolved.
  - the error messages will occur when you try to pull the repo, github will said (check in github.pdf)
  
8. git log
  - shows a history of commit and messages
  
9. git reset
  - git reset --hard <commit>
    reverts code back to previous commit
  - git reset --hard origin/master
    reverts code back to remote repository version
  
10. git branch
  make different version of of repo inside of repo itself.
  
11. git merge

12. pull requests
