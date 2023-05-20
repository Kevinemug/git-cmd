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



<h1>Bundle 3</h1>

<h2>Exercise 1/h2>

* git checkout -b ft/team-page
* git add .
* git commit "changes"
* git checkout main
* git checkout -b ft/contact-page
* git checkout ft/team-page
* git git cherry-pick git cherry-pick 378243c103b2ac54e9d8947a94bcbf2b49712585
* git add . ,git commit ,git push
* git checkout -b ft/faq-page
* git add ,git commit ,git push
* git revert 378243c103b2ac54e9d8947a94bcbf2b49712585
 *  git push

<h2>Exercise 2/h2>
  
  * git checkout -b  ft/home-page-redesign
  * git checkout main
  * git add ,git commit,git push
  * git checkout ft/home-page-redesign
  * git pull origin main
  * git rebase main
*git add ,git commit git push
  
  
  
  
  
   E:\git-exercise> git revert 52c93141ac619dd001d37734f3433657eeda7b4c
 delete mode 100644 Random-files/faq.html
On branch ft/faq-page
nothing to commit, working tree clean
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 340 bytes | 170.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Kevinemug/git-cmd.git
PS E:\git-exercise> git branch ft/home-page-redesign
PS E:\git-exercise> git checkout main
Switched to branch 'main'
PS E:\git-exercise> git add .
PS E:\git-exercise> git commit -m"some changes to main"
[main f3bc77a] some changes to main
 1 file changed, 1 insertion(+), 1 deletion(-)
PS E:\git-exercise> git push origin main
To https://github.com/Kevinemug/git-cmd.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/Kevinemug/git-cmd.git'
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
PS E:\git-exercise> git pull origin main
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 888 bytes | 1024 bytes/s, done.
From https://github.com/Kevinemug/git-cmd
 * branch            main       -> FETCH_HEAD
   b7c3932..69c8757  main       -> origin/main
Merge made by the 'ort' strategy.
 README.md | 27 +++++++++++++++++++++++++++
 1 file changed, 27 insertions(+)
PS E:\git-exercise> git push origin master
error: src refspec master does not match any
error: failed to push some refs to 'https://github.com/Kevinemug/git-cmd.git'
PS E:\git-exercise> git push origin main  
Enumerating objects: 12, done.
Counting objects: 100% (10/10), done.
 0), pack-reused 0
To https://github.com/Kevinemug/git-cmd.git
   69c8757..807189c  main -> main
PS E:\git-exercise> git checkout -b ft/home-page-redesign
fatal: a branch named 'ft/home-page-redesign' already exists
PS E:\git-exercise> git checkout  ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'
From https://github.com/Kevinemug/git-cmd
 README.md              | 27 +++++++++++++++++++++++++++
 Random-files/home.html |  2 +-
PS E:\git-exercise> git rebase main
Successfully rebased and updated refs/heads/ft/home-page-redesign.
PS E:\git-exercise> git commit -m"new changes rebased"
[ft/home-page-redesign b505ec1] new changes rebased
 1 file changed, 1 insertion(+), 1 deletion(-)
PS E:\git-exercise> git push origin home-page-redesign
error: src refspec home-page-redesign does not match any
error: failed to push some refs to 'https://github.com/Kevinemug/git-cmd.git'
PS E:\git-exercise> git push origin ft/home-page-redesign
Enumerating objects: 24, done.
Counting objects: 100% (24/24), done.
Delta compression using up to 4 threads
Compressing objects: 100% (21/21), done.
Writing objects: 100% (21/21), 2.14 KiB | 547.00 KiB/s, done.
Total 21 (delta 9), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (9/9), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/Kevinemug/git-cmd/pull/new/ft/home-page-redesign
remote:
To https://github.com/Kevinemug/git-cmd.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign
PS E:\git-exercise>






