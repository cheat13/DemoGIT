git branch -b work1
git add .
git commit -m ""
git checkout master
git pull --rebase
git merge --no-ff work1
git push