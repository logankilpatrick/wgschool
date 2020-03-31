+++
title = "Bash Scripting and Tools"
slug = "bash-11-other"
+++

{{< next110 prev="../bash-10-text-manipulation" up="../bash" >}}

# Fuzzy finder `fzf`

* third-party tool, not installed by default
* basic usage: interactive processing of standard input
* advanced usage: key bindings and fuzzy completion

On cassiopeia.c3.ca you can install it into your $HOME with:

~~~ {.bash}
$ source /project/shared/fzf/.fzf.bash     # each user in each shell or put it into your ~/.bashrc
$ fzf
$ nano $(fzf --height 40%)
~~~

# Other advanced bash topics

- exercise: write a function to compare two directories
- sed, awk
- arithmetics
- permissions
- how to control processes
- GNU_Parallel
- homebrew if enough Macs

{{< next110 prev="../bash-10-text-manipulation" up="../bash" >}}
