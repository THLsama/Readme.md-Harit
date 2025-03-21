C:\Users\User\Desktop\Readme.md>git init
Initialized empty Git repository in C:/Users/User/Desktop/Readme.md/.git/

C:\Users\User\Desktop\Readme.md>git add .

C:\Users\User\Desktop\Readme.md>git commit -m "README"
[master (root-commit) 039ff8f] README
 1 file changed, 17 insertions(+)    
 create mode 100644 index.html       

C:\Users\User\Desktop\Readme.md>git checkout

C:\Users\User\Desktop\Readme.md>git checkout -b feature
Switched to a new branch 'feature'

C:\Users\User\Desktop\Readme.md>git branch
* feature
  master

C:\Users\User\Desktop\Readme.md>git add .

C:\Users\User\Desktop\Readme.md>git commit -m "add name and email" 
[feature 39758ed] add name and email
 1 file changed, 1 insertion(+), 1 deletion(-)

C:\Users\User\Desktop\Readme.md>git branch master
fatal: a branch named 'master' already exists

C:\Users\User\Desktop\Readme.md>git checkout master
Switched to branch 'master'

C:\Users\User\Desktop\Readme.md>git branch
  feature
* master

C:\Users\User\Desktop\Readme.md>git merge feature
Updating 039ff8f..39758ed
Fast-forward
 index.html | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)

C:\Users\User\Desktop\Readme.md>git remote add README.md  https://github.com/THLsama/Readme.md-Harit.git 

C:\Users\User\Desktop\Readme.md>git branch -M main

C:\Users\User\Desktop\Readme.md>git push -u README.md main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 594 bytes | 297.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/THLsama/Readme.md-Harit.git
 * [new branch]      main -> main
branch 'main' set up to track 'README.md/main'.

C:\Users\User\Desktop\Readme.md>git branch
  feature
* main

C:\Users\User\Desktop\Readme.md>git switch feature
Switched to branch 'feature'

C:\Users\User\Desktop\Readme.md>git switch main
Switched to branch 'main'
Your branch is up to date with 'README.md/main'.

C:\Users\User\Desktop\Readme.md>
