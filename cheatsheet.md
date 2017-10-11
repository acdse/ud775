---
layout: default
---

## Cheatsheet

#### Git BASH

$ git version
$ pwd 		# print working directory: shows what directory you are in
$ ls -al 	# list statistics -all -long : list the files in this directory
$ cd ~		# goto home directory
$ pwd		# /c/Users/nsbe
$ cd ..		# go up on the tree directory

$ cd ~						# change directories to your home directory
$ mkdir version-control		# make version-control directory
$ cd version-control		# go to version-control directory
$ mkdir reflections			# create reflections directory
$ cd reflections			# go to reflections directory
$ notepad lesson_1_reflections.txt # launch notepad and open lesson_1_reflections.txt
									# you can replace notepad by e.g. subl (sublime)
$ pwd						# /c/Users/nsbe/version-control/reflections
$ git help diff				# show help for the command diff
C:\Program Files\Git\mingw64\share\doc\git-doc\git-diff.html
$ diff -u game_old.js game_new.js	# show differences between these 2 files

Definitions:
- A repository is a group with the multiple files that are saved in each commit
- HEAD is the commit you are currently working
- 'detached HEAD' state means you did "git checkout" to a previous commit

$ cd ~
$ cd version-control 
$ pwd									# /c/Users/nsbe/version-control
$ git clone https://github.com/udacity/asteroids.git
$ cd asteroids
$ pwd									# /c/Users/nsbe/version-control/asteroids
$ git log --stat
$ git config --global color.ui auto		# to get colored diff output: maybe not necessary
$ git diff   ...id_commit/filename...   ...id_commit/filename...

$ git checkout b0678b161fcf74467ed3a63110557e3d6229cfa6
$ git checkout 3884eab839af1e82c44267484cf2945a766081f3

$ git clone https://github.com/git/git

			https://github.com/git/git.git

<br />

[Homepage](../)
