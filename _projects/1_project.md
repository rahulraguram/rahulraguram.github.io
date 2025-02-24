---
layout: page
title: RECON
description: Scale Adaptive Robust Estimation via Residual Consensus
img: assets/img/recon.png
importance: 1
category: robust estimation
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/recon.png" title="RECON" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<b>RECON: Scale Adaptive Robust Estimation via Residual Consensus</b><br>
Rahul Raguram and Jan-Michael Frahm.<br>
<i>International Conference on Computer Vision (ICCV) (Oral Presentation)</i>, 2011.<br>
[<a href="https://rahulraguram.com/assets/pdf/0727.pdf">paper (pdf)</a>]

In this work, we present a threshold-free robust estimation framework capable of efficiently fitting models to contaminated data. While RANSAC and its many variants have emerged as popular tools for robust estimation, their performance is largely dependent on the availability of a reasonable prior estimate of the inlier threshold. This work builds on the simple observation that models generated from uncontaminated minimal subsets are somehow "consistent" in terms of the behavior of their residuals, while contaminated models exhibit uncorrelated behavior. By leveraging this observation, we then develop a very simple, yet effective algorithm that does not require apriori knowledge of either the scale of the noise, or the fraction of uncontaminated points.