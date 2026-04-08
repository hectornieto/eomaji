---
layout: post
title: "EOMAJI Webinar - PRISMA Hyperspectral data: from acquisition to application"
date: 2026-03-04 10:00:00 +2000
tags: news dissemination
excerpt_separator: <!--more-->
---

Webinar conducted on March 4th 2026 by María Dolores Raya-Sereno, post-doctoral researcher in the Environmental Remote Sensing and Spectroscopy Laboratory (https://speclab.csic.es/en/)

<!--more-->
Hyperspectral satellite PRISMA (Precursore IperSpettrale della Missione Applicativa) is an Earth Observation satellite launched by the Italian Space Agency (ASI). This satellite has a spatial resolution of 30 × 30 m and 230 bands in the visible, NIR, and SWIR regions (400-2500 nm). The satellite’s data acquisition capability is particularly useful for monitoring crop phenology, water stress, and evapotranspiration throughout the study sites in EOMAJI project.

However, PRISMA's images typically require pre-processing due to a co-registration issue. Co-registration is a critical step in image processing, as it ensures that pixels representing the same geographical location are spatially aligned across all spectral bands. 

This problem is solved by the automated the automated and Robust Open-Source Image Co-Registration Software (AROSICS) (https://github.com/GFZ/arosics) used to automatically detect tie points or brightness edges by applying cross-correlation techniques between an input and reference band.


Access to the webinar, as well as the open-source code for processing PRISMA images, can be found at:


* [Webinar: PRISMA Hyperspectral data: from acquisition to application] (https://balanbbb.corp.csic.es/playback/presentation/2.3/1a0665844e37349f4623d83419e891e51891840b-1772612974630)

* [Jupyter Notebook for geometric and radiometric correction of hyperspectral images from the PRISMA satellite] (https://github.com/md-raya/prisma-image-preprocessing)



