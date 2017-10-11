---
layout: default
---

## Lesson 1 reflections

How did viewing a diff between two versions of a file help you see the bug that
was introduced?

    It was helpful because the diff tool (on Linux, or the FC tool on Windows)
	compare the files and outputs/prints on the screen (only) the differences
	between these two files (nomather how big they are), so we can easily spot
	the bug in our code.

How could having easy access to the entire history of a file make you a more
efficient programmer in the long term?

    As programmers we code brick upon brick, and sometimes we even experiment,
	when at some point we decide to revert back to some selected point in time
	we may do so because we have the entire history versions of our code file.

What do you think are the pros and cons of manually choosing when to create a
commit, like you do in Git, vs having versions automatically saved, like Google
docs does?

    The pros of manual commits are that, if made in the right time, they will
	always reflect a clear and logical purpose/reason, as oppoesd to the cons
	that may reflect bad judgement e.g. too many or too much commits or even
	forgetting to commit.

Why do you think some version control systems, like Git, allow saving multiple
files in one commit, while others, like Google Docs, treat each file separately?

    Because git is oriented to coding projects that normally involves multiple
	files that are interconnected, while others, like Google Docs target files
	that are self-contained.

How can you use the commands git log and git diff to view the history of files?

    First "git clone" your github repository to your version-control folder,
	then "git log --stat" to view the commits info, then "git diff" the id's
	of two different commits to see the insertions and deletions from the
	previous to the next commit.

How might using version control make you more confident to make changes that
could break something?

    Using version control allow us to keep track of multiple versions of a
	file and we can freely make changes because if we break something we can
	track bugs by reverting to previous working versions of a file.

Now that you have your workspace set up, what do you want to try using Git for?

    Fill in your answer here

<br />

[Homepage](../)
