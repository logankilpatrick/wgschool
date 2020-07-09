+++
title = "MATLAB sessions"
slug = "matlab"
+++

This is a **3-day** workshop.

<!-- **Course plan**: -->

**Target audience**: general  

**Level**: beginner

<!-- **Prerequisites**:  -->

**Software**: For Parallel MATLAB, all attendees will need a remote secure shell (SSH) client installed
on their computer in order to participate in the course exercises. On Windows we recommend
[the free Home Edition of MobaXterm](https://mobaxterm.mobatek.net/download.html). On Mac and Linux
computers SSH is usually pre-installed (try typing `ssh` in a terminal to make sure it is there).

Also, please ensure you have the following:

- a [supported browser](https://www.mathworks.com/support/requirements/browser-requirements.html)
- a MathWorks account (if you don't already have one please go [here](https://www.mathworks.com/login)
  to create one)

The Parallel MATLAB session will also introduce submitting MATLAB parallel jobs on Cedar Monday
afternoon. It would be helpful to have a Compute Canada account, but we will also be providing guest
accounts.

<!-- We have some short videos for each of the session, that will be posted shortly. They can be watched -->
<!-- before or during the sessions. At the start of each morning session we will walk folks through logging -->
<!-- into MATLAB as well as downloading the day's workshop material. The afternoon will be spent answering -->
<!-- questions/demos. -->

---

**Monday (July-06)**  
*"Parallel MATLAB"* with Raymond Norris
<!-- will need guest accounts on Cedar + reservation for this session -->

Please download the PDF slides:
* [Parallel Computing Hands-On Workshop](/slides/matlabParallelComputing.pdf)
* [Scaling MATLAB on Compute Canada](/slides/matlabOnComputeCanada.pdf) (from slide #12 to the end not officially
  supported until the scripts are deployed)

Today we will be submitting jobs to the reservation on Cedar:

```
cd ~/scratch
salloc --account=def-training-wa_cpu --reservation=wgss3-wr_cpu --mem-per-cpu=... --time=... <other_flags>
```

**July-06**
{{< zoom >}}
<b>9am-10am Pacific</b>
Live introduction session.
{{< /zoom >}}

{{< video >}}
<!-- {{< link url="../bash/bash-02-filesystem" text="Navigating the filesystem (9 min)" >}}<br> -->
See the video below (33 min)
{{< /video >}}<br>

{{< zoom >}}
<b>2:30pm-3:30pm Pacific</b>
Live Q&A session.
{{< /zoom >}}

&nbsp;<br>

{{< yt H8KM487zNrk 63 >}}

&nbsp;<br>

---

**Tuesday (July-07)**  
*"Machine learning with MATLAB"* with Reece Teramoto

* [PDF slides](/slides/matlabMachineLearning.pdf)
* [Clean exercise files](https://sft.mathworks.com/human.aspx?r=&Arg06=637127050&Arg12=filelist) (enter username
  "customer" and password "MathWorks")

You can download individual files from your [MATLAB drive](https://drive.matlab.com) to your computer. Alternatively,
you can use the [MATLAB Drive Connector](https://www.mathworks.com/help/matlabdrive/ug/install-matlab-drive.html) to
download entire directories.

**July-07**
{{< zoom >}}
<b>9am-10am Pacific</b>
Live introduction session.
{{< /zoom >}}

{{< video >}}
{{< link url="../matlab-machine-learning" text="Machine Learning videos (76 min)" >}}<br>
{{< /video >}}<br>

{{< zoom >}}
<b>2:30pm-3:30pm Pacific</b>
Live Q&A session.
{{< /zoom >}}

&nbsp;<br>

---

**Wednesday (July-08)**  
*"Deep learning with MATLAB"* with Reece Teramoto

* [PDF slides](/slides/matlabDeepLearning.pdf)
* [Clean exercise files + large training dataset](https://sft.mathworks.com/human.aspx?r=&Arg06=637023204&Arg12=filelist)
  (enter username "customer" and password "MathWorks")

You can download individual files from your [MATLAB drive](https://drive.matlab.com) to your computer. Alternatively,
you can use the [MATLAB Drive Connector](https://www.mathworks.com/help/matlabdrive/ug/install-matlab-drive.html) to
download entire directories.

**July-08**
{{< zoom >}}
<b>9am-10am Pacific</b>
Live introduction session.
{{< /zoom >}}

{{< video >}}
{{< link url="../matlab-deep-learning" text="Deep Learning videos (90 min)" >}}<br>
{{< /video >}}<br>

{{< zoom >}}
<b>2:30pm-3:30pm Pacific</b>
Live Q&A session.
{{< /zoom >}}







<!-- Zoom conversation with Raymond and Reece -->
<!-- parallel workshop -->
<!-- - 30min video hosted at mathworks -->
<!-- - others online from mathworks -->
<!-- - they will email the instructions directly to all attendees and will cc me -->
<!-- machine learning and deep learning workshops -->
<!-- - will use breakout rooms -->
<!-- - Reece will send me his videos, Ok to upload them to WG's youtube channel -->
