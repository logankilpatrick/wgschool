+++
title = "Bash Scripting and Tools"
slug = "bash-01-intro"
+++

# Introduction

* Why use a cluster: computing beyond the scale of a desktop (faster, bigger, cost, efficientcy)
* Using HPC systems often involves the use of a shell
  * text-based interface to the OS (unlike a GUI): (1) command interpreter and mechanism to launch tools
    / utilities / compiled binaries / system calls / other scripts and (2) a way to connect standard I/O
    of these tools through pipes to form more complex commands
  * follows the classic UNIX philosophy of breaking complex projects into simpler subtasks and chaining
    together components and utilities
  * a shell around the kernel (coconut analogy), along with utilities and applications
  * commands are often very cryptic (to avoid too much typing)
  * bash is one of many Unix shell implementations
* Why learn Unix shell: very powerful, great for automating workflows, necessary on bigger Unix systems
* Connection to an HPC system is often done via SSH using a terminal on your laptop
  * Linux and Mac laptops have built-in terminals
  * on Windows many terminal emulators; we'll be using a free version of MobaXterm
* We have set up a small cluster training cluster cassiopeia.c3.ca, that features the same software setup
  as our real production clusters
  * in *"Intro to HPC"* we will learn the specifics of working on a cluster: software environment,
    scheduler, compilers, etc.
  * now -- using this cluster -- we will learn how to work with a remote Linux system using the shell,
    the basic Linux commands, working with the file system, how to remote-transfer files, and similar
    introductory topics
