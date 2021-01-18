https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners

Last login: Mon Jan 18 22:42:39 on ttys000
thierrycapy@MacBook-Pro-de-thierry ~ % cd ~/desktop
thierrycapy@MacBook-Pro-de-thierry desktop % mkdir gitProjekt
thierrycapy@MacBook-Pro-de-thierry desktop % cd gitProjekt 
thierrycapy@MacBook-Pro-de-thierry gitProjekt % git init
Initialized empty Git repository in /Users/thierrycapy/Desktop/gitProjekt/.git/
thierrycapy@MacBook-Pro-de-thierry gitProjekt % touch Osakar.txt
thierrycapy@MacBook-Pro-de-thierry gitProjekt % ls
Osakar.txt
thierrycapy@MacBook-Pro-de-thierry gitProjekt % git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	Osakar.txt

nothing added to commit but untracked files present (use "git add" to track)

thierrycapy@MacBook-Pro-de-thierry gitProjekt % git add Osakar.txt 
thierrycapy@MacBook-Pro-de-thierry gitProjekt % git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   Osakar.txt

thierrycapy@MacBook-Pro-de-thierry gitProjekt % git commit -m "My first commit 2021-01-18 23:34:03"
[master (root-commit) 29c00c0] My first commit 2021-01-18 23:34:03
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Osakar.txt
thierrycapy@MacBook-Pro-de-thierry gitProjekt % git status
On branch master
nothing to commit, working tree clean

thierrycapy@MacBook-Pro-de-thierry gitProjekt % touch README.md
thierrycapy@MacBook-Pro-de-thierry gitProjekt % git add README.md
thierrycapy@MacBook-Pro-de-thierry gitProjekt % git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   README.md

thierrycapy@MacBook-Pro-de-thierry gitProjekt % git commit -m "Commit"
[master b630802] Commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
thierrycapy@MacBook-Pro-de-thierry gitProjekt % git branch -M main
thierrycapy@MacBook-Pro-de-thierry gitProjekt % git remote add origin https://github.com/3osakar/localRepository.git

thierrycapy@MacBook-Pro-de-thierry gitProjekt % git push -u origin main
Username for 'https://github.com': 3osakar
Password for 'https://3osakar@github.com': 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (5/5), 432 bytes | 432.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0)
To https://github.com/3osakar/localRepository.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
thierrycapy@MacBook-Pro-de-thierry gitProjekt % git push -u origin main

