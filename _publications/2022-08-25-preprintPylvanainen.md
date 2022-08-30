---
title: "Fast4DReg: Fast registration of 4D microscopy datasets"
collection: publications
date: 2022-08-25
venue: 'bioRxiv'
authors: 'Joanna W Pylvänäinen, Romain F Laine, Sujan Ghimire, Gautier Follain, Ricardo Henriques, Guillaume Jacquemet'
paperurl: https://www.biorxiv.org/content/10.1101/2022.08.22.504744
type: 'Preprint'
doi: https://doi.org/10.1101/2022.08.22.504744
theme: "software, methods"
resources: 'NanoJ'
---

<h2> Abstract </h2>
<p align= "justify">
Unwanted sample drift is a common issue that plagues microscopy experiments, preventing accurate temporal quantification of biological processes. While multiple methods and tools exist to correct images post-acquisition, performing drift correction of large 3D videos using open-source solutions remains challenging and time-consuming. Here we present a new pipeline developed as an ImageJ/Fiji macro called Fast4DReg that can quickly correct axial and lateral drift in 3D video microscopy datasets. Fast4DReg works by creating intensity projections along multiple axes and estimating the drift between frames using 2D cross-correlations. Using synthetic and acquired datasets, we demonstrate that Fast4DReg performs better than other state-of-the-art open-source drift correction tools and significantly outperforms them in speed (5x to 60x). We also demonstrate that Fast4DReg can be used to register misaligned channels in 3D using either calibration slides or misaligned images directly. Altogether Fast4DReg provides a quick and easy-to-use method to correct 3D imaging data before further visualization and analysis. Fast4DReg is available on GitHub.

{% include paper-research-resources.html %}
