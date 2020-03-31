+++
title = "Introduction"
slug = "bash-01-intro"
weight = 1
+++

<!-- # Introduction -->

We use HPC systems (clusters) to do computing beyond the scale of a desktop, specifically by:

* using many processors speed up computation,
* solve larger problems that do not fit on a desktop,
* decompose large problems onto multiple nodes and compute them in parallel.

- Using HPC systems usually involves the use of a shell
  - unlike a GUI, it is a text-based interface to the operating system that excels at two things: <!-- command interpreter -->
    1. launching other tools and scripts and
	1. connecting standard input/output of these tools through pipes to form more complex commands
  - follows the classic UNIX philosophy of breaking complex projects into simpler subtasks and chaining
    together components and utilities
  - a shell around the operating system kernel (coconut analogy), surrounded itself by utilities and applications
  - its commands are often very cryptic (to avoid too much typing)
- Why learn Unix shell: very powerful, great for automation and creating reproducible workflows,
  necessary to work on larger Unix systems
- Bash is one of many Unix shell implementations

For the hands-on work, we have set up a small training cluster *cassiopeia.c3.ca* that features the same
software setup as our real production clusters. In the ["Introduction to HPC"](../hpc) course you will
learn the specifics of working on a cluster: its software environment, scheduler, compilers, parallel
programming models, and so on. In this course we will learn how to work with a remote Linux machine and
its filesystem, the basic Linux commands, how to transfer files to/from/between remote systems, and
similar introductory topics.

You can connect to a remote HPC system via SSH (secure shell) using a terminal on your laptop. Linux and
Mac laptops have built-in terminals, whereas on Windows we suggest using a free version of MobaXterm
that comes with its own terminal emulator and a simple interface for remote SSH sessions.

# Logging in to a remote system

Let's log in to *cassiopeia.c3.ca* using a username userXXX (where XXX=001..118):

~~~ {.bash}
[local]$ ssh userXXX@cassiopeia.c3.ca   # password supplied by the instructor
~~~

- those on Windows please use MobaXterm
- use the prompt to distinguish the remote from local terminals
