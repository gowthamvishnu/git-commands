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
 
git reset HEAD FILENAME (to unstage the  a particula file from staging area)
git reset HEAD . or * (to unstage all  the files from staging area)

git status (shows the status of the files whether they are added to the staging area or not)

git checkout filename(for example if we some changes in a file.after somes time you don't want some changes/to discard the changes we use this command)
note:this operation is before adding to the staging area i.e that mean fwe can use this for working area files)
git checkout . (to discard changes for all files in the working area)

 
git commit -m"commit msg" (to add the changes from staging area to remote directory we need to commit the changes with a commit message)
git reset --mixed HEAD~1 (it will reset the latest 1st commit and keeps them in working area)
git reset --soft  HEAD~1(it will reset the latest 1st commit and keeps them in staging area)
git reset --hard HAED~1(it will reset the latest 1st commit and it willn't keep them in staging area or working area)
this reset command will only for local repos.. for remote we use revert and we can reset upto last 3 commits only)

git revert commitid( it will rever the changes from the recent commit and make a new commit)

git push origin <branch name> (pushing the changes from local repo to remote repo by branchname ex: git push origin master)
 
git pull repo_url (it will pull all the new files or changed files from central repo and it directly places or connects them into your master branch)

git fetch repo_url (irt does also the same thing but it actually store in a different branch which is not connect with your workflow.so if you are doing git fetch make sure that you do a git merge .so that you actually can see the changes in your local repo)
git pull = git fetch + merge

git remore add origin repo_url

#GIT_BRANCHING:
git branch <branchname> (to create branch)
 if we made some changes in the branch,those changes does not relects on the mainbranch/master brranch.to reflect changes we need to merge.
 
git merge branchname(here branch name means the branch whcih you want to merge in)
(note:to merge a particular branch we should be in the destination branch)



