# Exercice 1 : Créer, fusionner et supprimer une branche

## - Dans votre projet git-101-td1 créé lors du TD1 :

## - Créez une nouvelle branche ma-branche.-Dans la branche master, effectuez une modification dans le fichier README.md, indexez et validez là.
git branch ma-branche
git add .
git commit -m ""

## - Basculez sur la branche ma-branche, effectuez une modification dans le fichier LICENSE, indexez et validez là.
git checkout ma-branche
git add .
git commit -m ""

## - Fusionnez la branche ma-branche dans la branche master.
git checkout master
git merge ma-branche

## - Supprimer la branche ma-branche.
git branch -d ma-branche