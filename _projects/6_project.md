---
layout: page
title: Internet Photo Collections 
description: Modeling and Organizing Large Scale Internet Photo Collections
img: assets/img/iconic_cropped.png
importance: 1
category: internet photo collections
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/iconic.png" title="Iconic" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<b>Modeling and Recognition of Landmark Image Collections Using Iconic Scene Graphs</b>
Rahul Raguram, Changchang Wu, Jan-Michael Frahm, and Svetlana Lazebnik
<i>International Journal of Computer Vision (IJCV), 2011.</i>
[<a href="assets/pdf/ijcv2011.pdf">paper (pdf)</a>] [<a href="http://www.cs.unc.edu/PhotoCollectionReconstruction">webpage</a>]

<b>Building Rome on a Cloudless Day</b>
Jan-Michael Frahm, Pierre Georgel, David Gallup, Tim Johnson, Rahul Raguram, Changchang Wu, Yi-Hung Jen, Enrique Dunn, Brian Clipp, Svetlana Lazebnik, Marc Pollefeys
<i>European Conference on Computer Vision (ECCV), 2010.</i>
[<a href="assets/pdf/ECCV2010.pdf">paper (pdf)</a>] [<a href="http://www.cs.unc.edu/~jmf/rome_on_a_cloudless_day">webpage</a>]

<i><b>Press</b></i>: <a href="http://www.bbc.co.uk/news/technology-11827854"   target="_blank">BBC</a> <a href="http://reesenews.org/2011/03/29/uncs-computer-program-builds-3-d-models-in-one-day/13304/" target="_blank">ReeseNews</a> <a href="http://www.readwriteweb.com/archives/flickr_rome_3d_double-time.php" target="_blank">ReadWriteWeb</a> <a href="http://www.physorg.com/news/2010-11-worth-thousand-million-words-d.html" target="_blank">PhysOrg</a> <a href="http://www.techjournalsouth.com/2010/11/unc-researchers-create-3d-models-from-online-photo-databases/" target="_blank">Tech Journal</a> <a href="http://www.newswise.com/articles/worth-a-thousand-million-words-researchers-create-3-d-models-from-online-photo-databases">NewsWise</a>

Recent years have seen an explosion in consumer digital photography and a phenomenal growth of community photo-sharing websites. At UNC, we have developed systems for modeling and visualizing landmarks based on large-scale, heavily contaminated image collections gathered from the Internet. Our approach to this problem encompasses image clustering, robust geometric verification, structure from motion and stereo to achieve high computational performance. Our <a href="assets/pdf/ijcv2011.pdf">original</a> system was capable of handling datasets containing tens of thousands of images, and we have more <a href="assets/pdf/ECCV2010.pdf">recently</a> extended this to be able to process <i>millions</i> of images in a day, on a single PC.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/iconicsum.png" title="Iconic Summaries" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<b>Computing Iconic Summaries of General Visual Concepts</b>
Rahul Raguram and Svetlana Lazebnik
<i>Workshop on Internet Vision, Conference on Computer Vision and Pattern Recognition (CVPR), 2008.</i>
[<a href="assets/pdf/iconic.pdf">paper (pdf)</a>] 

In this work, we consider the problem of selecting iconic images to summarize <i>general visual categories</i>. We define iconic images as high-quality representatives of a large group of images consistent both in appearance and semantics. To find such groups, we perform joint clustering in the space of global image descriptors and latent topic vectors of tags associated with the images. To select the representative iconic images for the joint clusters, we use a quality ranking learned from a large collection of labeled images. Results on four large-scale datasets demonstrate the ability of our approach to discover plausible themes and recurring visual motifs for challenging abstract concepts such as "love" and "beauty".