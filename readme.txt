- cd into Projects folder on Desktop 
- git init Project folder = Projects becomes a git repo
- add readme.txt to be added to repo = git add readme.txt (temporary staging area)
- git status to see files changed/ added
- when progress is made, commit changes in staging area with a commit message
- git commit -m"added readme.txt"

change stuff in read me
add all changes to all files using:
git add .
or just for specific file
git add readme.txt

changes are in back in staging area & now commit changes

git commit -m"testing how to commit changes to readme.txt file"

now want to change to new branch called new
git checkout -b new

C:\Users\********\Desktop\Projects>git checkout master
Switched to branch 'master'

C:\Users\*********\Desktop\Projects>git checkout new
Switched to branch 'new'

merge master & new branch
git merge master 

added new remote called origin with specified url
git remote add origin https://github.com/alessandra-s/testRepo.git

make sure on master branch
push all commits to the origin remote repository & push to master
git push -u origin master

https://www.youtube.com/watch?v=DVRQoVRzMIY