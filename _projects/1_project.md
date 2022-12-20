---
layout: page
title: Robust Estimation
description: Worked on efficient algorithms for robust estimation in computer vision
img: assets/img/recon.png
importance: 1
category: work
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/recon.png" title="RECON" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<b>RECON: Scale Adaptive Robust Estimation via Residual Consensus</b><br>
Rahul Raguram and Jan-Michael Frahm<br>
<i>International Conference on Computer Vision (ICCV), 2011 (Oral Presentation).</i><br>
[<a href="assets/pdf/0727.pdf">paper (pdf)</a>]

In this work, we present a threshold-free robust estimation framework capable of efficiently fitting models to contaminated data. While RANSAC and its many variants have emerged as popular tools for robust estimation, their performance is largely dependent on the availability of a reasonable prior estimate of the inlier threshold. This work builds on the simple observation that models generated from uncontaminated minimal subsets are somehow "consistent" in terms of the behavior of their residuals, while contaminated models exhibit uncorrelated behavior. By leveraging this observation, we then develop a very simple, yet effective algorithm that does not require apriori knowledge of either the scale of the noise, or the fraction of uncontaminated points.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/usac.png" title="RECON" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<b>Universal/Über RANSAC</b><br>
<b>USAC: A universal framework for random sample consensus</b><br>
Rahul Raguram, Ondrej Chum, Marc Pollefeys, Jiri Matas and Jan-Michael Frahm<br>
<i>IEEE Transactions on Pattern Analysis and Machine Intelligence (PAMI).</i>
[<a href="assets/pdf/RaguramPAMI13.pdf">paper (pdf)</a>] 

In this paper, we present a comprehensive overview of recent research in RANSAC-based robust estimation, by analyzing and comparing various approaches that have been explored over the years. We provide a common context for this analysis by introducing a new framework for robust estimation, which we call Universal RANSAC (USAC). USAC extends the simple hypothesize-and-verify structure of standard RANSAC to incorporate a number of important practical and computational considerations. In addition, we provide a general-purpose C++ software library that implements the USAC framework by leveraging state of the art algorithms for the various modules. This implementation thus addresses many of the limitations of standard RANSAC within a single unified package. We benchmark the performance of the algorithm on a large collection of estimation problems. The implementation we provide can be used by researchers either as a stand-alone tool for robust estimation, or as a benchmark for evaluating new techniques.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cov.png" title="RECON" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<b>covRANSAC: Exploiting Uncertainty in Random Sample Consensus</b><br>
Rahul Raguram, Jan-Michael Frahm and Marc Pollefeys<br>
<i>International Conference on Computer Vision (ICCV), 2009.</i>
[<a href="assets/pdf/RaguramICCV09.pdf">paper (pdf)</a>] 

One of the implicit assumptions in RANSAC is that a model produced from an all-inlier minimal subset will be consistent with all other inliers in the data. However, in practice, it has been observed that this is rarely the case; since model hypotheses are generated from noisy data points, the model parameters are also affected by noise. In this work, we show how the various uncertainties of the estimation process can be explicitly modeled within a robust estimation framework. Coupled with tests to characterize the "non-randomness" of a solution, this strategy can result in up to an order of magnitude improvement in efficiency over RANSAC. 
