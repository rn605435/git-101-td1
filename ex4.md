# Exercice 4 : Cloner et récupérer les données d’un dépôt distant

## - Ouvrez un nouveau tab/fenêtre dans votre terminal, et remontez d’un niveau (cd ..).
cd ..

## - Clonez votre dépôt distant créé à l’exercice 3 dans un nouveau dossier git-101-td1-bis.
git clone https://github.com/rn605435/git-101-td1.git git-101-td1-bis

## - Créez un nouveau fichier LICENSE, indexez et validez le.
touch LICENSE
git add LICENSE
git commit -m "license commited"

## - Pousser la nouvelle validation vers le dépôt distant.
git push origin master

## - Dans le premier tab/fenêtre (projet git-101-td1): Récupérez les données du dépôt distant et mettez à jour la branche courante, grâce à une seule commande.
git pull

## - Vous pouvez supprimer le dossier git-101-td1-bis, nous n’en aurons plus besoin
done