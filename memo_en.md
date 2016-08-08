# Memento-Git-GitHub

## Create / Manage my repository and commits

Do my folder a Git repository :

`git init`

------------------

See the status of my repository :

`git status`

------------------

Do my first commit :

``git add .``

``git commit -m “Mon message de commit”``

------------------

Make the following commits :

``git commit -am “Mon message de commit”``

------------------

See the list of commits :

``git log``

------------------

View the latest X commits :

``git log -n X``

------------------

View commits to a particular file :

``git log -p <nom_fichier>``

------------------

Position on a particular commit :

``git checkout <sha_commit>``

------------------

Back on the last commit :

``git checkout master``

## Create and edit my branchs

Show branches :

``git branch``

------------------

Create a new branch :

``git branch <nom_nouvelle_branche>``

------------------

Position on a branch :

``git checkout <nom_branche>``

------------------

Create a branch and position above :

``git checkout -b <nom_nouvelle_branche>``

------------------

Rename the current branch :

``git branch -m <nouveau_nom>``

------------------

To delete a merged branch :

``git branch -d <nom_branche>``

------------------

Delete an unfused branch /!\ :

``git branch -D <nom_branche>``

------------------

Merge a branch with the master branch :

``git merge <nom_branche_a_fusionner_avec_master>`` On the master branch

**IF CONFLICT**


In the file indicated the place of conflict between **<<<<<<  >>>>>>**.

Solving by hand -> add -> commit -> save the file that opens in the console

## Put aside my work temporarily

Put aside what you do to do something else and come back without commit :

``git stash``

------------------

Recover what has been set aside :

``git stash pop``

## GitHub / Working at several

Clone a GitHub project via https :

`git clone <lien_https_du_projet>`

Send a branch on GitHub :

``git push origin <nom_branche>``

------------------

Send all on GitHub :

``git push origin --all``

------------------

Collect news from Github :

``git pull origin <nom_branche>``

------------------

Know who did what :

``git blame <nom_fichier>``

------------------

Details of what was done on a commit :

``git show <sha_commit>``
