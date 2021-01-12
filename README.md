# Mémo

## Commandes git à retenir
**git commit :** import
**git checkout :** pour aller se positionner quelque part *
**git merge :** créer un commit qui a deux parents
**git rebase :** pour amenner deux branches au même niveau
**^ :** pour remonter d'un cran
**~ :** pour remonter de ~ cran
**git reset :** pour réécrire l'histoire et remonter comme si le reste n'avait jamais existé
**git revert :** idem mais pour branches distantes (créer un "bis")


## Pour créer un dépôt par une ligne de commande

…or create a new repository on the command line // process pour initier le fichier
ouvrir git bach
taper pwd pour voir où on est
taper cd documents, pour aller dans ce répertoire
taper mkdir git, pour créer ce dossier
taper cd git, pour aller dans ce répertoire
taper mkdir memo, pour créer le fichier
echo "# Memo" >> README.md, pour lui donner un nom de sortie
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/BouvetS74/Memo.git
git push -u origin main

git pull pour descendre les modifications de Github vers le fichier
                
…or push an existing repository from the command line
git remote add origin https://github.com/BouvetS74/Memo.git
git branch -M main
git push -u origin main
…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
