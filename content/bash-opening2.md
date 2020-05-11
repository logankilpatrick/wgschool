+++
title = "Bash Day 2"
slug = "bash-opening2"
+++

<!-- In this session, I will cover the program for today, answer any questions and share the afternoon -->
<!-- exercises. -->

1. review the program for today
1. answer any questions

By the end of the day you should be able to:

- write a multi-line bash script and function
- process command-line arguments in this script / function
- search inside files with `grep`
- search the filesystem with `find`
- perform basic text manipulation with `sed`, `tr`, `awk`

Some of the hands-on exercises we will do in the afternoon Zoom session:

- Write a function archive() to replace directories with their gzipped archives.
- Write a one-line command that will search for a string in all files in the current directory and all
  its subdirectories, and will hide errors (e.g. due to permissions).
- Write a one-line command that finds 5 largest files in the current directory and prints only their
  names and file sizes in the human-readable format (indicating bytes, kB, MB, GB, ...) in the decreasing
  file-size order. Hint: use `find`, `xargs`, and `awk`.
