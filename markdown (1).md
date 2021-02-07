# __Лабораторная работа №1__

Выполнил: Егошин Антон И-21
```
  git init
```
```
Reinitialized existing Git repository in C:/Users/User/Desktop/github/.git/
User@DESKTOP-JDRRE4T MINGW64 ~/Desktop/github (master)
```
```
git status
```
```
On branch master
No commits yet
Untracked files: (use "git add ..." to include in what will be committed) index.html
nothing added to commit but untracked files present (use "git add" to track)
User@DESKTOP-JDRRE4T MINGW64 ~/Desktop/github (master)
```
```
git add *
```
```
User@DESKTOP-JDRRE4T MINGW64 ~/Desktop/github (master)
```
```
git commit -m "мой первый коммит"
```
```
[master (root-commit) 14025c8] мой первый коммит 1 file changed, 0 insertions(+), 0 deletions(-) create mode 100644 index.html
User@DESKTOP-JDRRE4T MINGW64 ~/Desktop/github (master)
```
```
git rm
```
```
fatal: No pathspec was given. Which files should I remove?
User@DESKTOP-JDRRE4T MINGW64 ~/Desktop/github (master)
```
```
git log
```
```
commit 14025c87d59164ccfb06bbefddbae4d81df61a85 (HEAD -> master) Author: Egoshin21 anton.egoshin2016@yandex.ru Date: Sat Feb 6 14:51:29 2021 +0300
мой первый коммит
User@DESKTOP-JDRRE4T MINGW64 ~/Desktop/github (master)
```
```
git branch -M main
```
```
User@DESKTOP-JDRRE4T MINGW64 ~/Desktop/github (main)
```
```
git remote add origin https://github.com/Egoshin21/gittest.git
```
```
User@DESKTOP-JDRRE4T MINGW64 ~/Desktop/github (main)
```
```
git push -u origin main
```
```
Enumerating objects: 3, done. Counting objects: 100% (3/3), done. Writing objects: 100% (3/3), 245 bytes | 245.00 KiB/s, done. Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 To https://github.com/Egoshin21/gittest.git
[new branch] main -> main Branch 'main' set up to track remote branch 'main' from 'origin'.
User@DESKTOP-JDRRE4T MINGW64 ~/Desktop/github (main)
```