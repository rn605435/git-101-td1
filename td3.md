# Ex1 
git branch td3-1
git checkout td3-1
git add .
git commit -m "validation de license"
git checkout master
git merge td3-1
git push
git branch 2-0-stable
git checkout 2-0-stable
git push -u origin 2-0-stable
git tag -a v2.0.0 -m "version 2.0.0"
git push --tags
Comment procédez-vous pour résoudre ce bug 
--> on crée un tag de la version puis on stash ce qu'il faut préserver.
git tag -a v2.0.1 -m "version 2.0.1"
git stash
git checkout master
git status
git push -u origin 2-0-stable
git push -u origin master
git push --tags
rm LICENSE
git add .
git commit -m "license file deleted"
git push
git checkout 2-0-stable
git tag -a v2.0.2 -m "version 2.0.2"
git stash
git push -u origin 2-0-stable
git checkout master
git push -u master
git push -u origin master
git push --tags
# Ex2
git branch td3-2
git checkout td3-2
git push origin td3-2:td3-2-bis
# Ex3
git pull master
git checkout -b td3-3 origin/master
# Ex4
git checkout master
git branch td3-4
git add .
git commit -m "modif sur readme pour ex4 td3"
git checkout td3-4
git add .
git commit -m "modif readme q3 ex4 td3"
git rebase master
git checkout master
git merge td3-4
git push


