---
layout: default
---

## Cheatsheet

### All Git Bash shell commands used in this course
---

$ git version <br />
$ pwd <br />
$ ls -alhF <br />
$ cd ~ <br />
$ pwd &emsp;&emsp;&emsp;&emsp;&emsp; # /c/Users/nsbe<br />
$ cd .. <br />

$ cd ~ <br />
$ mkdir version-control <br />
$ cd version-control <br />
$ mkdir reflections <br />
$ cd reflections <br />
$ notepad lesson_1_reflections.txt <br />
$ subl lesson_1_reflections.txt <br />
$ pwd &emsp;&emsp;&emsp;&emsp;&emsp; # /c/Users/nsbe/version-control/reflections <br />
$ git help diff <br />
C:\Program Files\Git\mingw64\share\doc\git-doc\git-diff.html <br />
$ diff -u game_old.js game_new.js	

Definitions:
- A repository is a group with the multiple files that are saved in each commit
- HEAD is the commit you are currently working
- 'detached HEAD' state means you did "git checkout" to a previous commit

$ cd ~ <br />
$ cd version-control <br />
$ pwd &emsp;&emsp;&emsp;&emsp;&emsp; # /c/Users/nsbe/version-control <br />
$ git clone https://github.com/udacity/asteroids.git <br />
$ cd asteroids <br />
$ pwd &emsp;&emsp;&emsp;&emsp;&emsp; # /c/Users/nsbe/version-control/asteroids <br />
$ git log --stat <br />
$ git config --global color.ui auto &emsp;&emsp;&emsp;&emsp;&emsp; # to get colored diff output, maybe not necessary <br />
$ git diff   ...id_commit/filename...   ...id_commit/filename... <br />

$ git checkout b0678b161fcf74467ed3a63110557e3d6229cfa6 <br />
$ git checkout 3884eab839af1e82c44267484cf2945a766081f3

$ git clone https://github.com/git/git

https://github.com/git/git.git

<br />

[Homepage](../)
