go to link and download https://git-scm.com/download/win



https://github.com/nkoteeswaran/Portfolio
git add .
git commit -am 'own comment'
git push
git status





Fortune@Fortune-PC MINGW64 /d/git
$ git clone https://github.com/nkoteeswaran/Portfolio.git
Cloning into 'Portfolio'...
remote: Enumerating objects: 44, done.
remote: Counting objects: 100% (44/44), done.
remote: Compressing objects: 100% (35/35), done.
remote: Total 44 (delta 8), reused 44 (delta 8), pack-reused 0
Unpacking objects: 100% (44/44), 1.80 MiB | 1.18 MiB/s, done.

Fortune@Fortune-PC MINGW64 /d/git
$ cd Portfolio/

Fortune@Fortune-PC MINGW64 /d/git/Portfolio (master)
$ touch readme.md



Type a message


Fortune@Fortune-PC MINGW64 /d/git/Portfolio (master)
$ ls
assets/  index.html  readme.md

Fortune@Fortune-PC MINGW64 /d/git/Portfolio (master)
$ git add .

Fortune@Fortune-PC MINGW64 /d/git/Portfolio (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   readme.md


Fortune@Fortune-PC MINGW64 /d/git/Portfolio (master)
$ git commit -am 'added readme'
[master ae1cd3d] added readme
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 readme.md

Fortune@Fortune-PC MINGW64 /d/git/Portfolio (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

Fortune@Fortune-PC MINGW64 /d/git/Portfolio (master)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 306 bytes | 306.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/nkoteeswaran/Portfolio.git
   b33060e..ae1cd3d  master -> master

Fortune@Fortune-PC MINGW64 /d/git/Portfolio (master)
$ cd assets/

Fortune@Fortune-PC MINGW64 /d/git/Portfolio/assets (master)
$ ls
avatar.png  favicon.ai  favicon.gif  favicon.png  fontawesome/  layout.min.css  resume.pdf

Fortune@Fortune-PC MINGW64 /d/git/Portfolio/assets (master)
$ cd ..

Fortune@Fortune-PC MINGW64 /d/git/Portfolio (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   readme.md

no changes added to commit (use "git add" and/or "git commit -a")

Fortune@Fortune-PC MINGW64 /d/git/Portfolio (master)
$ git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

Fortune@Fortune-PC MINGW64 /d/git/Portfolio (master)
$ git add .

Fortune@Fortune-PC MINGW64 /d/git/Portfolio (master)
$ git commit -am 'done'
[master 6380c51] done
 1 file changed, 6 insertions(+)

Fortune@Fortune-PC MINGW64 /d/git/Portfolio (master)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 325 bytes | 325.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/nkoteeswaran/Portfolio.git
   ae1cd3d..6380c51  master -> master

Fortune@Fortune-PC MINGW64 /d/git/Portfolio (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

Fortune@Fortune-PC MINGW64 /d/git/Portfolio (master)
$ ^C

Fortune@Fortune-PC MINGW64 /d/git/Portfolio (master)
$ ^C

Fortune@Fortune-PC MINGW64 /d/git/Portfolio (master)
$
