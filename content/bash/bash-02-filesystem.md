+++
title = "Filesystem"
slug = "bash-02-filesystem"
weight = 2
+++

# Navigating directories

~~~ {.bash}
$ whoami   # explain what happens when you type a command: finds it, runs it, displays output, new prompt
$ pwd   # explain /, root directory, path, why 'pwd' is so short (traces to early 1970s)
$ ls
$ ls someDirectory
$ ls /
$ ls -F   # -F displays a bit more info (adds trailing / to the names of directories); -F is a flag/option
$ ls -F someDirectory   # can combine both arguments and flags
$ ls -F /someDirectory   # why an error?
$ cd /Users/razoumov   # this is an absolute path
$ cd Documents   # and this is a relative path
$ cd ..   # go one directory up (parent directory)
$ ls ../directoryName   # also a relative path
$ ls -F -a   # -a displays hidden files
$ cd   # go to home directory, the same as 'cd ~'
$ cd -   # go to previous directory
~~~

# Getting help

~~~ {.bash}
$ man ls
$ ls --help
~~~

> Question: Looking at `ls` documentation, what does the -h (--human-readable) option do?

Explain tab completion in bash.

> **Quiz 1:** If pwd displays /Users/thing, what will ls ../backup display?

> **Quiz 2:** If pwd displays /Users/backup, and -r tells ls to display things in reverse order, what
> command will display: pnas-sub/ pnas-final/ original/

> **Quiz 3:** What does the command `cd` without a directory name do?

> **Quiz 4:** Multiple ways to return to the home directory.
