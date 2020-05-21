+++
title = "Working with ParaView filters"
slug = "vis-04-filters"
weight = 4
+++

## ParaView filters

<!-- 04a-filters1.mp4 -->

## Store your visualization workflow with a state file

<!-- 04b-state-file.mp4 -->

## Side-by-side visualization

<!-- 04c-side-by-side.mp4 -->

## Visualizing vectors

<!-- 04d-vectors.mp4 -->

#### Creating better streamlines

<!-- 04e-better-streamlines.mp4 -->

#### Line integral convolution (LIC)

<!-- 04f-lic.mp4 -->

## Reading CSV data

<!-- 04g-csv.mp4 -->

## Word of caution

Many visualization filters, e.g. Clip and Slice, transform stuctured grid data into unstructured
data. Since unstructured data can take several times as much memory, it is a good idea to monitor the
memory footprint of your visualization workflow. If your current memory usage is already close to the
physical memory of your computer (or the memory allocation of the cluster job running your `pvserver`),
applying such a filter will either force your computer to swap, making everything very slow, or your job
on the cluster will get killed, and therefore your `pvserver` will be terminated.

In ParaView it is easy to monitor your memory usage by clicking on View -> Memory Inspector.

If you are running our of memory with a remote, distributed visualization (we will study this later), the
best option is to ask for more CPU cores with a fixed `--mem-per-cpu`. Not only will this give you more
total memory, it will also speed up your rendering and data reading, assuming that your file format
supports parallel I/O.
