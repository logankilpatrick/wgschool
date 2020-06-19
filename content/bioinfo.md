+++
title = "Bioinformatics sessions: data analysis tools"
slug = "bioinfo"
+++

This is a **3-day** workshop.

**Target audience**: researchers in bioinformatics

**Level**: beginner

**Software**: All attendees will need a remote secure shell (SSH) client installed on their computer in
order to participate in the course exercises. On Windows we recommend
[the free Home Edition of MobaXterm](https://mobaxterm.mobatek.net/download.html). On Mac and Linux
computers SSH is usually pre-installed (try typing `ssh` in a terminal to make sure it is there).

<!-- **Prerequisites**:  -->

---

**Wednesday June-17**  
*"Short read mapping and visualization: Core aspects of next-generation sequencing data analysis"*  
with Phillip Richmond

{{< zoom >}}
<b>9am-noon Pacific</b> &nbsp; Live session
{{< /zoom >}}

{{< yt CGvMm7JXQGs 63 >}}
&nbsp;<br>
{{< yt x_uRLx1o9AM 63 >}}
&nbsp;<br>
{{< yt UzCIGF4_OTg 63 >}}
&nbsp;<br>

You can find the online slides
[here](https://docs.google.com/presentation/d/17JLujUNtsvSIzN0XZAM8OMT0tnrmoZvotF3eCydrN-c). Here is the
[PDF version](../ngs-phil.pdf).

Today we will be submitting jobs to the reservation on Cedar:

```
cd ~/scratch
salloc --account=def-training-wa_cpu --reservation=wgss1-wr_cpu --mem-per-cpu=... --time=... <other_flags>
```

1. session opening
1. 30-min lecture
1. participants watch videos 1 & 2 (~10-15 min each) and complete activities for each;
  activities will range from 15 min to 45 min depending on skill level
1. reconvene, mini check-in
1. participants watch video 3, complete activity afterwards
1. reconvene, describe homework, close

<!-- Video 1 - Mapping short reads against the reference genome (Fastq —> SAM) -->
<!-- Video 2 - Converting mapped reads from SAM —> BAM and indexing -->
<!-- Video 3 - Visualizing mapped reads in IGV and taking snapshots -->


&nbsp;<br>

---

**Thursday June-18**  
*"Building a Reproducible Data Analysis Pipeline"*  
with Matthew Douglas (Genome Science Center)

{{< zoom >}}
<b>9am-noon Pacific</b> &nbsp; Live session
{{< /zoom >}}

You can find the PDF slides [here](../pipeline-matthew.pdf).

- 45-60min presentation + some time for Q&A, no coding for the audience
- based on first-hand experience in several research projects

&nbsp;<br>

---

**Friday June-19**  
*"Setting up a bioinformatics pipeline with SnakeMake"*  
with Brian McConeghy

{{< zoom >}}
<b>9am-noon Pacific</b> &nbsp; Live session
{{< /zoom >}}

You can find the PDF slides [here](../pipeline-brian.pdf).

- 60min presentation followed by live Q&A
