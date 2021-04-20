#Creating new project

cd project/
git init 
git add .
git commit -m "message"

#Cloning
git clone "url"

#Branching
git branch        #shows the branches list
git checkout -b "name"    # creating a new branch 
git commit -a
git checkout main         #back to main branch

#The git fetch command downloads commits, files, and refs from a remote repository into your local repo
git fetch

#Fetched content has to be explicitly checked out
git merge
git checkout

#To see what commits have been added to the upstream master, you can run a git log using orign
git log

#To approve the changes and merge them into your local master branch use the following commands
git checkout master
git log origin/master

#Then we can use git merge origin/master
git merge origin/master

#to upload local repository content to a remote repository
git push
