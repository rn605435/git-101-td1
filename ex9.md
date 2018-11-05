Exercice 2 : Résoudre un conflit de fusion
-Créez une nouvelle branche ma-branche.
git branch ma-branche
-Dans la branche master, effectuez une modification dans le fichier README.md, indexez et validez là.
git add & commit ...
-Dans la branche ma-branche, effectuez une modification dans le fichier README.md sur la même ligne qu’à l’étape précédente (dans master), indexez et validez là.
git add & commit ...
-Fusionnez la branche ma-branche dans la branche master. Cette fois, vous devriez avoir des conflits à résoudre...
git checkout master 
git merge ma-branche
conflict --
git add .
git commit 
git push 
-Supprimer la branche ma-branche.
git branch -d ma-branche