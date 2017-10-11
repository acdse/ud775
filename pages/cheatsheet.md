---
layout: default
---

## Cheatsheet

### Git BASH

$ git version <br />
$ pwd &nbsp;&nbsp;&nbsp;&nbsp; # print working directory: shows what directory you are in <br />
$ ls -al &nbsp;&nbsp;&nbsp;&nbsp; # list statistics -all -long : list the files in this directory <br />
$ cd ~ &nbsp;&nbsp;&nbsp;&nbsp; # goto home directory <br />
$ pwd &nbsp;&nbsp;&nbsp;&nbsp; # /c/Users/nsbe <br />
$ cd .. &nbsp;&nbsp;&nbsp;&nbsp; # go up on the tree directory <br />

$ cd ~ &nbsp;&nbsp;&nbsp;&nbsp; # change directories to your home directory <br />
$ mkdir version-control &nbsp;&nbsp;&nbsp;&nbsp; # make version-control directory <br />
$ cd version-control &nbsp;&nbsp;&nbsp;&nbsp; # go to version-control directory <br />
$ mkdir reflections &nbsp;&nbsp;&nbsp;&nbsp; # create reflections directory <br />
$ cd reflections &nbsp;&nbsp;&nbsp;&nbsp; # go to reflections directory <br />
$ notepad lesson_1_reflections.txt &nbsp;&nbsp;&nbsp;&nbsp; # launch notepad and open lesson_1_reflections.txt <br />
&nbsp;&nbsp;&nbsp;&nbsp; # you can replace notepad by e.g. subl (sublime) <br />
$ pwd &nbsp;&nbsp;&nbsp;&nbsp; # /c/Users/nsbe/version-control/reflections <br />
$ git help diff &nbsp;&nbsp;&nbsp;&nbsp; # show help for the command diff <br />
&nbsp;&nbsp;&nbsp;&nbsp; C:\Program Files\Git\mingw64\share\doc\git-doc\git-diff.html <br />
$ diff -u game_old.js game_new.js	&nbsp;&nbsp;&nbsp;&nbsp; # show differences between these 2 files

Definitions:
- A repository is a group with the multiple files that are saved in each commit
- HEAD is the commit you are currently working
- 'detached HEAD' state means you did "git checkout" to a previous commit

$ cd ~ <br />
$ cd version-control <br />
$ pwd &nbsp;&nbsp;&nbsp;&nbsp; # /c/Users/nsbe/version-control <br />
$ git clone https://github.com/udacity/asteroids.git <br />
$ cd asteroids <br />
$ pwd &nbsp;&nbsp;&nbsp;&nbsp; # /c/Users/nsbe/version-control/asteroids <br />
$ git log --stat <br />
$ git config --global color.ui auto &nbsp;&nbsp;&nbsp;&nbsp; # to get colored diff output: maybe not necessary <br />
$ git diff   ...id_commit/filename...   ...id_commit/filename... <br />

$ git checkout b0678b161fcf74467ed3a63110557e3d6229cfa6 <br />
$ git checkout 3884eab839af1e82c44267484cf2945a766081f3

$ git clone https://github.com/git/git

https://github.com/git/git.git

<br />

[Homepage](../)
