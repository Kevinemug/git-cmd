# git-exercise
<h1>Bundle 1</h1>

<h2>Exercise 1</h2>

* git init
* git branch -b master main
* git add . , git commit -m"adding changes"
* git remote  add origin https://github.com/Kevinemug/git-cmd
* git push origin main
* git checkout -b dev
* git checkout -b test
* git checkout dev
* git branch -d test

<h2>Exercise 2</h2>

* git stash save "puting home.html away for a while"
* git stash save "puting about.html away for a while"
* git stash save "puting team.html away for a while"
* git stash list
* git stash pop 'stash@{1}'
* git stash apply 'stash@{1}'
* git stash pop 'stash@{0}'
* git reset --hard HEAD


<h1>Bundle 2</h1>

<h2>Exercise 2</h2>

* git checkout main
* git pull origin main
* git checkout -b ft/service-redesign
* git add service.html
* git commit -m "Add changes to service.html"
* git push origin ft/service-redesign
* git checkout main
* git add service.html
* git commit -m "Add different changes to service.html"
* git push origin main
* git checkout ft/service-redesign
* git diff main
* git merge main
* git commit -m "Merge main branch into ft/service-redesign"
* git push origin ft/service-redesign






