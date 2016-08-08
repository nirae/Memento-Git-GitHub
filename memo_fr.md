# Memento-Git-GitHub

## Création/Gestion de mon repository et commits

Faire de mon répertoire un repository Git :

`git init`

------------------

Voir l’état de mon repository :

`git status`

------------------

Faire mon premier commit :

``git add .``

``git commit -m “Mon message de commit”``

------------------

Faire les commit(s) suivant(s) :

``git commit -am “Mon message de commit”``

------------------

Voir la liste des commits :

``git log``

------------------

Voir les X derniers commits :

``git log -n X``

------------------

Voir les commits d’un fichier en particulier :

``git log -p <nom_fichier>``

------------------

Se positionner sur un commit en particulier :

``git checkout <sha_commit>``

------------------

Revenir sur le dernier commit :

``git checkout master``

## Créer et modifier mes branches

Afficher les branches :

``git branch``

------------------

Créer une nouvelle branche :

``git branch <nom_nouvelle_branche>``

------------------

Se positionner sur une branche :

``git checkout <nom_branche>``

------------------

Créer une branche et se positionner dessus :

``git checkout -b <nom_nouvelle_branche>``

------------------

Renommer la branche courante :

``git branch -m <nouveau_nom>``

------------------

Supprimer une branche fusionnée :

``git branch -d <nom_branche>``

------------------

Supprimer une branche non fusionnée /!\ :

``git branch -D <nom_branche>``

------------------

Fusionner une branche avec la branche master :

Positionné sur la branche master

``git merge <nom_branche_a_fusionner_avec_master>``

**EN CAS DE CONFLIT**

Dans le fichier est indiqué l’endroit de conflit entre **<<<<<<  >>>>>>**.

Une fois résolu à la main -> add -> commit puis enregistrer le fichier qui s'ouvre dans la console

## Mettre de côté mon travail temporairement

Mettre de côté ce qu’on fait pour faire autre chose puis y revenir sans faire de commit :

``git stash``

------------------

Récupérer ce qui a été mis de côté :

``git stash pop``

## GitHub / Travailler à plusieurs

Cloner un projet GitHub via https:

`git clone <lien_https_du_projet>`

Envoyer une branche sur GitHub :

``git push origin <nom_branche>``

------------------

Tout envoyer sur GitHub :

``git push origin --all``

------------------

Récupérer les nouveautés depuis Github :

``git pull origin <nom_branche>``

------------------

Savoir qui a fait quoi :

``git blame <nom_fichier>``

------------------

Détail de ce qui a été fait sur un commit :

``git show <sha_commit>``
