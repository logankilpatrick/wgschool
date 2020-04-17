+++
title = "Archiving and compressing"
slug = "bash-04-tar-gzip"
weight = 4
+++

In this video we will be working with a ZIP file that you can download and unpack with

~~~ {.bash}
$ wget http://bit.ly/bashfile -O bfiles.zip
$ unzip bfiles.zip
~~~

Unlike an SSD or a hard drive on your laptop, the filesystem on HPC cluster was designed to store large
files, ideally with parallel I/O. As a result, it handles any large number of small I/O requests (reads
or writes) very poorly, sometimes bringing the I/O system to a halt. For this reason, we strongly
recommend that users do not store thousands (or more) individual files -- instead you should pack them
into a small number of large archives. This is where the archiving tool `tar` comes in handy.

## Working with `tar` and `gzip/gunzip` (8 min)

<!-- Let's download some files in Windows' ZIP format: -->

<!-- ~~~ {.bash} -->
<!-- $ wget http://bit.ly/bashfile -O bfiles.zip -->
<!-- $ unzip bfiles.zip -->
<!-- $ rm bfiles.zip -->
<!-- $ ls -->
<!-- $ ls data-shell -->
<!-- ~~~ -->

<!-- ZIP is a compression format from Windows, and it is not very popular in the Unix world. Let's archive the -->
<!-- directory `data-shell` using Unix's native `tar` command: -->

<!-- ~~~ {.bash} -->
<!-- $ tar cvf bfiles.tar data-shell/ -->
<!-- $ gzip bfiles.tar -->
<!-- ~~~ -->

<!-- You can also create a gzipped TAR file in one step: -->

<!-- ~~~ {.bash} -->
<!-- $ rm bfiles.tar.gz -->
<!-- $ tar cvfz bfiles.tar.gz data-shell/ -->
<!-- ~~~ -->

<!-- Let's remove the directory and the original ZIP file (if still there), and extract directory from our new -->
<!-- archive: -->

<!-- ~~~ {.bash} -->
<!-- $ /bin/rm -r data-shell/ bfiles.zip -->
<!-- $ tar xvfz bfiles.tar.gz -->
<!-- ~~~ -->

<!-- > **Exercise:** Let's create a new subdirectory `~/tmp` with 1000 files inside using `touch a{000..999}` -->
<!-- > and then gzip-archive that subdirectory. -->

Covered topics: `tar` and `g(un)zip`.

<!-- 04-archives.mkv -->
{{< yt ckD5jOCnyBU 63 >}}
