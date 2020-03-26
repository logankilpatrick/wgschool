+++
title = "Bash Scripting and Tools"
slug = "bash-04-tar-gzip"
+++

# Working with `tar` and `gzip/gunzip`

Let's download some files in Windows' ZIP format:

~~~ {.bash}
$ wget http://bit.ly/bashfile -O bfiles.zip
$ unzip bfiles.zip
$ rm bfiles.zip
$ ls
$ ls data-shell
~~~

ZIP is a compression format from Windows, and it is not very popular in the Unix world. Let's archive the
directory `data-shell` using Unix's native `tar` command:

~~~ {.bash}
$ tar cvf bfiles.tar data-shell/
$ gzip bfiles.tar
~~~

You can also create a gzipped TAR file in one step:

~~~ {.bash}
$ rm bfiles.tar.gz
$ tar cvfz bfiles.tar.gz data-shell/
~~~

Let's remove the directory and the original ZIP file (if still there), and extract directory from our new
archive:

~~~ {.bash}
$ /bin/rm -r data-shell/ bfiles.zip
$ tar xvfz bfiles.tar.gz
~~~

> **Exercise:** Let's create a new subdirectory `~/tmp` with 1000 files inside using `touch a{000..999}`
> and then gzip-archive that subdirectory.
