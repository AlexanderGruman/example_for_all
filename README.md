- First thing (do this one time only): fork this repository.
- Then Clone the repo you have forked.

  -- if you want to Update your forked repository:
  1. Ensure you have remote to the main fork (AlexanderGruman repo), if not: "git remote upstream <URL>"
  2. Check if you have 2 remotes (one for your forked repo, one for the upstream repo): "git remote -v"
  3. git fetch upstream (מביא את השינויים בעצם לפורק שלך)
  4. switch to your brench: git switch main
  5. Now you can update your main branch (of your fork) by marging: "git  merge upstream/main"
  6.  -- IF YOU HAVE CONFLICTS- SOLVE THEM!!! --
  7.  after you have done, you want to push the changes to your forked repo: "git push origin main"
  8.  trying to change the README file 
