---
layout: page
title: cov-RANSAC
description: Exploiting Uncertainty in Random Sample Consensus
img: assets/img/cov.png
importance: 1
category: robust estimation
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cov.png" title="cov-RANSAC" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<b>covRANSAC: Exploiting Uncertainty in Random Sample Consensus</b><br>
Rahul Raguram, Jan-Michael Frahm and Marc Pollefeys.<br>
<i>International Conference on Computer Vision (ICCV)</i>, 2009.<br>
[<a href="https://rahulraguram.com/assets/pdf/RaguramICCV09.pdf">paper (pdf)</a>] 

One of the implicit assumptions in RANSAC is that a model produced from an all-inlier minimal subset will be consistent with all other inliers in the data. However, in practice, it has been observed that this is rarely the case; since model hypotheses are generated from noisy data points, the model parameters are also affected by noise. In this work, we show how the various uncertainties of the estimation process can be explicitly modeled within a robust estimation framework. Coupled with tests to characterize the "non-randomness" of a solution, this strategy can result in up to an order of magnitude improvement in efficiency over RANSAC. 


