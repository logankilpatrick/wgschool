+++
title = "Wildcards, redirections, pipes"
slug = "bash-06-wildcards-redirection-pipes"
weight = 6
+++

# Wildcards, redirection to files, and pipes

<!-- * open http://bit.ly/bashfile in your browser, it'll download the file bfiles.zip -->
<!-- * unpack bfiles.zip to your Desktop; you should see ~/Desktop/data-shell -->

~~~ {.bash}
$ cd <parentDirectoryOf`data-shell`>
$ ls data-shell
$ cd data-shell/molecules
$ ls
$ ls p*   # this is a Unix wildcard; bash will expand it to 'ls pentane.pdb propane.pdb'
$ ls *.pdb   # another wildcard, will expand to "ls cubane.pdb ethane.pdb ...'
$ wc -l *.pdb   # list number of lines in each file
$ wc -l *.pdb > lengths.txt   # redirect the output of the last command into a file
$ more lengths.txt
$ sort -n lengths.txt   # sort numerically, i.e. 2 will go before 10, and 6 before 22
$ sort -n lengths.txt > sorted.txt
$ head -1 sorted.txt   # show the length of the shortest (number of lines) file
$ wc -l *.pdb | sort -n | head -1   # three commands can be shortened to one - this is called Unix pipe
~~~

Standard input of a process. Standard output of a process. Pipes connect the two.

> **Exercise:** build a single command to show the lenth of the longest (number of lines) file

> **Exercise:** Try to explain the difference between these two commands:
> ~~~ {.bash}
> echo hello > test.txt
> echo hello >> test.txt
> ~~~

> **Quiz 7:** What code would you use to move all the .dat files into the analyzed sub-directory?

> **Quiz 8:** Command to list the three files with the least number of lines.

## Aliases

Aliases are one-line shortcuts/abbreviation to avoid typing a longer command, e.g.

~~~ {.bash}
$ alias cp='cp -i'
$ alias mv='mv -i'
$ alias ls='ls -aFh'
$ alias hi='history'
$ alias cedar='ssh -Y cedar.computecanada.ca'
$ alias weather='curl wttr.in/vancouver'
~~~
