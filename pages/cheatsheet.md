---
layout: default
---

## Cheatsheet

#### Git BASH

$ git version <br />
$ pwd &nbsp;&nbsp;&nbsp;&nbsp; # print working directory: shows what directory you are in <br />
$ ls -al &nbsp;&nbsp;&nbsp;&nbsp; # list statistics -all -long : list the files in this directory <br />
$ cd ~ &nbsp;&nbsp;&nbsp;&nbsp; # goto home directory <br />
$ pwd &nbsp;&nbsp;&nbsp;&nbsp; # /c/Users/nsbe <br />
$ cd .. &nbsp;&nbsp;&nbsp;&nbsp; # go up on the tree directory <br />

$ cd ~						# change directories to your home directory <br />
$ mkdir version-control		# make version-control directory <br />
$ cd version-control		# go to version-control directory <br />
$ mkdir reflections			# create reflections directory <br />
$ cd reflections			# go to reflections directory <br />
$ notepad lesson_1_reflections.txt # launch notepad and open lesson_1_reflections.txt <br /> # you can replace notepad by e.g. subl (sublime) <br />
$ pwd						# /c/Users/nsbe/version-control/reflections <br />
$ git help diff				# show help for the command diff <br />
C:\Program Files\Git\mingw64\share\doc\git-doc\git-diff.html <br />
$ diff -u game_old.js game_new.js	# show differences between these 2 files <br />

Definitions:
- A repository is a group with the multiple files that are saved in each commit
- HEAD is the commit you are currently working
- 'detached HEAD' state means you did "git checkout" to a previous commit

$ cd ~ <br />
$ cd version-control <br />
$ pwd									# /c/Users/nsbe/version-control <br />
$ git clone https://github.com/udacity/asteroids.git <br />
$ cd asteroids <br />
$ pwd									# /c/Users/nsbe/version-control/asteroids <br />
$ git log --stat <br />
$ git config --global color.ui auto		# to get colored diff output: maybe not necessary <br />
$ git diff   ...id_commit/filename...   ...id_commit/filename... <br />

$ git checkout b0678b161fcf74467ed3a63110557e3d6229cfa6 <br />
$ git checkout 3884eab839af1e82c44267484cf2945a766081f3 <br />

$ git clone https://github.com/git/git

https://github.com/git/git.git

<br />

[Homepage](../)
