## Commands Used in GitBash and their Output
git init: 
-Initializes a new Git repository in your local folder.
-Creates a .git folder where Git tracks your commits

git clone + repo-url: 
-Downloads a remote Git repository from GitHub to your local machine.
-Automatically creates a folder with the repo’s name and sets origin as the remote

git add + file:
-Stages changes in a file so that Git knows to include it in the next commit.

git commit -m + message:
-Records a snapshot of your staged changes.
-m allows you to add a commit message describing your changes

git push -u origin main:
-Uploads local commits to the remote repository on GitHub
-u sets upstream tracking, so future pushes can just use git push.
main is the branch you are pushing

