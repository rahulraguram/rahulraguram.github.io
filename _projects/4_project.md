---
layout: page
title: ARRSAC
description: Adaptive, real-time robust estimation
img: assets/img/arrsac.png
importance: 1
category: robust estimation
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cov.png" title="cov-RANSAC" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<b>covRANSAC: Exploiting Uncertainty in Random Sample Consensus</b><br>
Rahul Raguram, Jan-Michael Frahm and Marc Pollefeys<br>
<i>International Conference on Computer Vision (ICCV), 2009.</i>
[<a href="assets/pdf/RaguramECCV08.pdf">paper (pdf)</a>] 

There are a number of scenarios (e.g., real-time 3D reconstruction) where time-constrained robust estimation is of interest. While there have been a number of recent efforts aimed at increasing the efficiency of the basic RANSAC algorithm, few of them are directly applicable in situations where real-time performance is required. To this end, we have proposed a real-time robust estimation framework, which builds upon the strengths of previous approaches, bringing together various ideas in order to achieve state of the art performance. In particular, ARRSAC is suitable for use in real-time applications with a limited time budget, and is capable of providing accurate results over a wide range of inlier ratios. At UNC, we have used ARRSAC in various large-scale 3D reconstruction systems, operating on both <a href="./papers/ISPRS2010.pdf">video sequences</a>, as well as <a href="./papers/ijcv2011.pdf">internet</a> <a href="./papers/ECCV2010.pdf">photo</a> <a href="./papers/ISPRS2010.pdf">collections</a>.



