# learning-git
CS50W lecture
I created this to save notes on how to use git and github.These notes are based on a lecture on Edx.org.
I plan to use this as a blue print for future git hub repositories.
**************
NOTES 
SCM stands for source code manager
examples of git config setup
git config user.name
git config user.email
git config --global core.editor "name of editor(VSCode)"
use git help to display commands for help 
eg git help log

***************
So step #1
On the github site create a repository
step #2
in your code editor
run git clone
step #3
change into newly cloned and downloaded repository
step #4
create a file
step $5
run git add + file name that you just created
step #6touch
run git status to see what you have
then run git commit -m"message"
to commit and include a message
 we can also use -am meaning I add all the messages
 step #7
 we then run git push to push the changes up to the repository
 *******
 Git Pull is the opposite of git push ..it will get the latest code from the repository
 from the code editor 
 run git pull
 *************
 
 Merge comfilcits occur when there are different versions of files and the steps to be taken 
 are as follows
 run git pull 
 read conflict message and markers
 fix code and keep what we want to keep
 then run git commit 
 then run git push
 
 ***************
 git log keeps track of all the git activities and changes and by whom and commit messages
 
 
 ***************
 
 git reset can revert the repository to a previous sommit
 git reset --hard <commit hash (name of commit)>
 git reset --origin/master(copy on the github site)
 
 **************
 Branches
  we can check out a new branch to work on for whatever reason
 typing git branch shows what branch is being worked on and it is denoted by a *
 the currrent files being worked on is called the head
 the head can be switched..

 
run  git checkout -b + the name of the branch

git checkout - switches branches


*********************
git merge will merge all the branches together

*********************

forking
clicking fork makes your own copy of a repository into your own repository

**********************
github pages

 
