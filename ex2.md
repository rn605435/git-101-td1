# Exercice 2 : Les 3 états d’un fichier

## - Initialisez un dépôt Git dans un nouveau dossier git-101-td1.
git init

## - Créez un fichier README et un fichier dev.gradle.
touch README.md, touch dev.gradle

## - Quel est l’état Git des deux nouveaux fichiers ?
untracked

## - Indexez ces deux fichiers.
git add .

## - Quel est l’état Git des deux fichiers à présent ?
indexé, ou staged

## - Validez les dans Git, chacun dans une validation séparée.
git commit -m "commit de readme" README.md
git commit -m "commit de devgradle" dev.gradle

## - Quel est l’état Git des deux fichiers à présent ?
validé, ou unmodified
## - Modifiez le fichier README puis annulez les modifications (avec une commande Git !).
git checkout -- README.md