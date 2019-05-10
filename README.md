# prueba
esto es una prueba del video tutorial


User@DESKTOP-QPQVB1S MINGW64 /c/It_Resource/ItR_Repo/RepoPrueba
$ git clone https://github.com/matiasgonzalezUNO/prueba.git
Cloning into 'prueba'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.

User@DESKTOP-QPQVB1S MINGW64 /c/It_Resource/ItR_Repo/RepoPrueba
$ git status
fatal: not a git repository (or any of the parent directories): .git

User@DESKTOP-QPQVB1S MINGW64 /c/It_Resource/ItR_Repo/RepoPrueba
$ cd prueba

User@DESKTOP-QPQVB1S MINGW64 /c/It_Resource/ItR_Repo/RepoPrueba/prueba (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        Prueba.txt
        Prueba2.txt

nothing added to commit but untracked files present (use "git add" to track)

User@DESKTOP-QPQVB1S MINGW64 /c/It_Resource/ItR_Repo/RepoPrueba/prueba (master)
$ git commit
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
        Prueba.txt
        Prueba2.txt

nothing added to commit but untracked files present

User@DESKTOP-QPQVB1S MINGW64 /c/It_Resource/ItR_Repo/RepoPrueba/prueba (master)
$ git add Prueba.txt

User@DESKTOP-QPQVB1S MINGW64 /c/It_Resource/ItR_Repo/RepoPrueba/prueba (master)
$ git add Prueba2.txt

User@DESKTOP-QPQVB1S MINGW64 /c/It_Resource/ItR_Repo/RepoPrueba/prueba (master)
$ git commit
[master 4e6f7b6] Esto es la tercer prueba
 2 files changed, 1 insertion(+)
 create mode 100644 Prueba.txt
 create mode 100644 Prueba2.txt

User@DESKTOP-QPQVB1S MINGW64 /c/It_Resource/ItR_Repo/RepoPrueba/prueba (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

User@DESKTOP-QPQVB1S MINGW64 /c/It_Resource/ItR_Repo/RepoPrueba/prueba (master)
$ git push origin master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 349 bytes | 116.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0)
To https://github.com/matiasgonzalezUNO/prueba.git
   090f2b0..4e6f7b6  master -> master

User@DESKTOP-QPQVB1S MINGW64 /c/It_Resource/ItR_Repo/RepoPrueba/prueba (master)
$
