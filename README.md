\# the first time you will need to add a local repository

git clone \<url>

\# check which branches are present and which is the current one

git branch<br>
\# For example, you may see:<br>
\# development<br>
\#*main

#for new developments, switch to the `development` branch

git checkout development<br>
\#Switched to branch `development`

\# create or modify files, for example foo.py<br>
\# add to GIT for tracking if new

git add foo.py

\# check the current status

git status

\# commit changes

git commit -am "description message"

\# switch to `main` branch

git checkout main

\# merge successful changes into the master branch, resolving conflicts if they arise

git merge development

\# push changes to the shared repository

git push