# Exercice 5 : Ignorer et supprimer des fichiers
## Vous vous rendez compte (trop tard !) que les fichiers de type .gradle ne devraient pas être suivis par Git.
## - Faites en sorte d’ignorer tous les fichiers de type .gradle.
touch .gitignore
* .gradle (dans .gitignore)
## - Supprimez le fichier dev.gradle de la base de donnée de Git sans le supprimer de votre copie de travail.
 git rm --cached dev.gradle

## - Modifiez le fichier dev.gradle.-Quel est le résultat de la commande git status à présent ?
untracked : .gitignore
deleted : dev.gradle

## - Indexez et validez les modifications.-Quel est le résultat de la commande git status à présent ?
la branche est devant par un commit puisqu'on n'a pas poussé les validations.

## - Poussez la nouvelle validation vers le dépôt distant
git push origin master
touch prod.gradle
git status (working tree clean)