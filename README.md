# git-exercise
<h1>Bundle 1</h1>

<h2>Exercise 1</h2>

* git init
* git branch -b master main
* git add . , git commit -m"adding changes"
* git add remote origin https://github.com/Kevinemug/git-cmd
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
