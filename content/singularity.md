+++
title = "Introduction to Singularity containers"
slug = "singularity"
+++

This is a **1-day** course.

**Instructor**: Grigory Shamov (Univ. Of Manitoba / WestGrid)

<!-- **Course plan**: -->

**Target audience**: general

**Level**: beginner

<!-- **Prerequisites**:  -->

**Software**: All attendees will need a remote secure shell (SSH) client installed on their computer in
order to participate in the course exercises. On Windows we recommend
[the free Home Edition of MobaXterm](https://mobaxterm.mobatek.net/download.html). On Mac and Linux
computers SSH is usually pre-installed (try typing `ssh` in a terminal to make sure it is there).

You can find the PDF slides [here](../Singularity-WGSummer2020-06-16.pdf), and a gzipped tar file
containing all commands for each exercise [here](../singularityCommands.tar.gz).

You will be submitting jobs to the reservations on Cedar:

```
salloc --account=def-training-wa --mem-per-cpu=8Gb --time=0-2:00:00 --reservation=wgsummer-wr_cpu
```

```
salloc --gres=gpu:p100:1 --cpus-per-task=8 --mem=40Gb --time=0-2:00:00 --account=def-training-wa --reservation=wgsummer-wr_gpu
```

**June-16**
{{< zoom >}}
<b>9am-noon Pacific</b>
Live session: 30-40 min presentation blocks.
{{< /zoom >}}
