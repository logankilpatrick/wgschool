+++
title = "Filesystem"
slug = "bash-02-filesystem"
weight = 2
+++

## Navigating directories (6 min)

Covered topics: `pwd`, `ls`, absolute vs. relative paths, command flags, `cd`, path shortcuts.

<!-- In the shell you can type any command after the "$" prompt and press "enter". The *standard output* from -->
<!-- this command will be printed in your terminal. Let's try a simple command: -->

<!-- ~~~ {.bash} -->
<!-- $ whoami -->
<!-- ~~~ -->

<!-- ~~~ -->
<!-- $ pwd   # explain /, root directory, path, why 'pwd' is so short (traces to early 1970s) -->
<!-- $ ls -->
<!-- $ ls someDirectory -->
<!-- $ ls / -->
<!-- $ ls -F   # -F displays a bit more info (adds trailing / to the names of directories); -F is a flag/option -->
<!-- $ ls -F someDirectory   # can combine both arguments and flags -->
<!-- $ ls -F /someDirectory   # why an error? -->
<!-- $ cd /Users/razoumov   # this is an absolute path -->
<!-- $ cd Documents   # and this is a relative path -->
<!-- $ cd ..   # go one directory up (parent directory) -->
<!-- $ ls ../directoryName   # also a relative path -->
<!-- $ ls -F -a   # -a displays hidden files -->
<!-- $ cd   # go to home directory, the same as 'cd ~' -->
<!-- $ cd -   # go to previous directory -->
<!-- ~~~ -->

<!-- {{< video >}} -->
<!-- {{< link url="https://westgrid-julia.netlify.com/school/jl-01-intro.html" text="Navigating directories (6m31s)" >}} -->
<!-- {{< /video >}} -->
<!-- 02-navigating.mkv -->
{{< yt OjbecASHm2k laptop >}}

## Getting help (3 min)

Covered topics: `man`, navigating manual pages, `--help` flag.

<!-- ~~~ {.bash} -->
<!-- $ man ls -->
<!-- $ ls --help -->
<!-- ~~~ -->

<!-- > Question: Looking at `ls` documentation, what does the -h (--human-readable) option do? -->

<!-- Explain tab completion in bash. -->

<!-- > **Quiz 1:** If pwd displays /Users/thing, what will ls ../backup display? -->

<!-- > **Quiz 2:** If pwd displays /Users/backup, and -r tells ls to display things in reverse order, what -->
<!-- > command will display: pnas-sub/ pnas-final/ original/ -->

<!-- > **Quiz 3:** What does the command `cd` without a directory name do? -->

<!-- > **Quiz 4:** Multiple ways to return to the home directory. -->

<!-- 02-help.mkv -->
{{< yt EAp3Xze1TZ0 laptop >}}
