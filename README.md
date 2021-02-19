# git-commands

#Introduce yourself to git.
git config --global user.name "examplename"
git config --global user.mail "example@mail"

#To use the different username and password for a particular project.
#change it inside the project
 #change the directory to particular directory.folling commands
git config user.name "examplename"(without global)
git config user.mail "example@mail"(without global)

git clone "repo_url"(to clone the remote repo to local workspace)

git log (irt will tell you total commits information like how many commites done,commitid,commited by whom,commit information etc..)

git add "<filename>" / git add . (adding the files/code/changes to the staging area from local workspace/working area)
 
git commit -m"commit msg" (to add the changes from staging area to remote directory we need to commit the changes with a commit message)

git push origin <branch name> (pushing the changes from local repo to remote repo by branchname ex: git push origin master)
 
git pull repo_url (it will pull all the new files or changed files from central repo and it directly places or connects them into your master branch)

git fetch repo_url (irt does also the same thing but it actually store in a different branch which is not connect with your workflow.so if you are doing git fetch make sure that you do a git merge .so that you actually can see the changes in your local repo)
git pull = git fetch + merge



