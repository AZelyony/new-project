\# the first time you will need to add a local repository

git clone <url>

\# check which branches are present and which is the current one

git branch<br>
\# development<br>
\#*main

#for new developments, switch to the 'development' branch

git checkout development
\#Switched to branch 'development'

\# create or modify files, for example foo.py
\# add to GIT for tracking if new

git add foo.py

\# check the current status

git status

\# commit changes

git commit -am "description message"

\# switch to main branch

git checkout main

\# merge successful changes into the master branch, resolving conflicts if they arise

git merge development

\# push changes to the shared repository

git push