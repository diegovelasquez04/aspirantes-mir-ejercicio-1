
jvelasquezl@jvelasquezl MINGW64 ~ (master)
$ pwd
/c/Users/jvelasquezl

jvelasquezl@jvelasquezl MINGW64 ~ (master)
$ cd C:\Clase2

$ cd C:\Clase2\ejercicios1^C


jvelasquezl@jvelasquezl MINGW64 /c/Clase2
$ cd C:\Clase2\ejercicios1
bash: cd: C:Clase2ejercicios1: No such file or directory

jvelasquezl@jvelasquezl MINGW64 /c/Clase2
$ cd ejercicios1

jvelasquezl@jvelasquezl MINGW64 /c/Clase2/ejercicios1
$ touch readme.md

jvelasquezl@jvelasquezl MINGW64 /c/Clase2/ejercicios1
$ git config --global user.name "Jvelasquezl"

jvelasquezl@jvelasquezl MINGW64 /c/Clase2/ejercicios1
$ git config --global user.email "diegovelasquez04@gmail.com"

jvelasquezl@jvelasquezl MINGW64 /c/Clase2/ejercicios1
$ cd.
bash: cd.: command not found

jvelasquezl@jvelasquezl MINGW64 /c/Clase2/ejercicios1
$ cd .

jvelasquezl@jvelasquezl MINGW64 /c/Clase2/ejercicios1
$ cd .

jvelasquezl@jvelasquezl MINGW64 /c/Clase2/ejercicios1
$ dir
readme.md

jvelasquezl@jvelasquezl MINGW64 /c/Clase2/ejercicios1
$ cd .

jvelasquezl@jvelasquezl MINGW64 /c/Clase2/ejercicios1
$ cd ..

jvelasquezl@jvelasquezl MINGW64 /c/Clase2
$ dir
ejercicios  ejercicios1

jvelasquezl@jvelasquezl MINGW64 /c/Clase2
$ cd ejercicios

jvelasquezl@jvelasquezl MINGW64 /c/Clase2/ejercicios
$ git init
Initialized empty Git repository in C:/Clase2/ejercicios/.git/

jvelasquezl@jvelasquezl MINGW64 /c/Clase2/ejercicios (master)
$ git commit -m "Versión Inicial"
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ejercicios1/

nothing added to commit but untracked files present (use "git add" to track)

jvelasquezl@jvelasquezl MINGW64 /c/Clase2/ejercicios (master)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

jvelasquezl@jvelasquezl MINGW64 /c/Clase2/ejercicios (master)
$ git commit -m "Versión Inicial"
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)
jvelasquezl@jvelasquezl MINGW64 /c/Clase2/ejercicios (master)
$ git add .

jvelasquezl@jvelasquezl MINGW64 /c/Clase2/ejercicios (master)
$ git commit -m "Versión Inicial"
[master (root-commit) 4fd4c9f] Versión Inicial
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 ejercicios1/readme.md

jvelasquezl@jvelasquezl MINGW64 /c/Clase2/ejercicios (master)
$ ^C


jvelasquezl@jvelasquezl MINGW64 /c/Clase2/ejercicios (master)
$ git add .

jvelasquezl@jvelasquezl MINGW64 /c/Clase2/ejercicios (master)
$ git commit -m "Agregar Solución  primer ejercicio"
[master 5049aaf] Agregar Solución  primer ejercicio
 1 file changed, 116 insertions(+)

$ git remote add origin https://github.com/diegovelasquez04/aspirantes-mir-ejercicio-1.git

jvelasquezl@jvelasquezl MINGW64 /c/Clase2/ejercicios (master)
$ it push -u origin master
bash: it: command not found

jvelasquezl@jvelasquezl MINGW64 /c/Clase2/ejercicios (master)
$ git push -u origin master
info: please complete authentication in your browser...
remote: Repository not found.
fatal: repository 'https://github.com/diegovelasquez04/aspirantes-mir-ejercicio-1.git/' not found

jvelasquezl@jvelasquezl MINGW64 /c/Clase2/ejercicios (master)
$ git push -u origin master
info: please complete authentication in your browser...
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (8/8), 1.15 KiB | 196.00 KiB/s, done.
Total 8 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/diegovelasquez04/aspirantes-mir-ejercicio-1.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.