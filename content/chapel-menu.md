+++
title = "Parallel programming in Chapel"
slug = "chapel-menu"
+++

<!-- This course is a combination of online reading and pre-recorded videos. -->

This **2-day** course is a general introduction to the main principles of parallel programming, using
Chapel programming language to illustrate the basic concepts and ideas. Chapel is a relatively new
language for both shared- and distributed-memory programming, with easy-to-use, high-level abstractions
for both task and data parallelism that make it ideal for learning parallel programming for a novice HPC
user. Chapel is incredibly intuitive, striving to merge the ease-of-use of Python and the performance of
traditional compiled languages such as C and Fortran. Parallel constructs that typically take tens of
lines of MPI code can be expressed in only a few lines of Chapel code. Chapel is open source and can run
on any Unix-like operating system, with hardware support from laptops to large HPC systems.

**Instructor**: Alex Razoumov (WestGrid)

**Level**: beginner/intermediate

**Prerequisites**: This is an introductory course, no prior parallel programming experience is required;
however, having some programming background will allow the attendees to get the most out of this
workshop. Also, we strongly recommend that all attendees have the working knowledge of the
[Linux command line](../bash-menu) and know the basic concepts of [high-performace computing](../hpc-menu).

**Software**: All attendees will need a remote secure shell (SSH) client installed on their computer in
order to participate in the course exercises. On Windows we recommend
[the free Home Edition of MobaXterm](https://mobaxterm.mobatek.net/download.html). On Mac and Linux
computers SSH is usually pre-installed (try typing `ssh` in a terminal to make sure it is there).

{{< figure src="/images/solveMulti.gif" >}}

**June-11**
{{< zoom >}}
<b>9am-9:45am Pacific</b> {{< link url="../chapel-opening1" text="Morning opening session" >}}<br>
{{< /zoom >}}

{{< reading >}}
{{< link url="../chapel/chapel-01-base" text="Basic language features" >}}<br>
{{< link url="../chapel/chapel-02-task-parallelism" text="Task parallelism" >}}
(try to get here as far as you can, and resume tomorrow)
{{< /reading >}}<br>

{{< zoom >}}
<b>2pm-3:30pm Pacific</b> We will go together through the challenges, do some exercises, and debug problems.
{{< /zoom >}}

**June-12**
{{< zoom >}}
<b>9am-9:45am Pacific</b> {{< link url="../chapel-opening2" text="Morning opening session" >}}<br>
{{< /zoom >}}

{{< reading >}}
{{< link url="../chapel/chapel-02-task-parallelism" text="Task parallelism" >}}(continue where you left off yesterday)<br>
{{< link url="../chapel/chapel-03-domain-parallelism" text="Domain parallelism" >}}
{{< /reading >}}<br>

{{< zoom >}}
<b>2pm-3:30pm Pacific</b> We will go together through the challenges, do some exercises, debug problems, and
wrap up the course.
{{< /zoom >}}
