---
permalink: /
title: "Highlighted Researches!"
excerpt: "Wenzhi Zhao"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Deeply synergistic optical and SAR time series for crop dynamic monitoring
------
Inspired by deep learning, this study presents a novel strategy to learn the relationship between optical and SAR time series based on the sequence of contextual information. To be specific, we extended the conventional CNN-RNN to build Multi-CNN-Sequence to Sequence (MCNN-Seq) model, and formulate the correlation between the optic and SAR time series sequences. We verified the MCNN-Seq model and found that the accuracy of the predicted optical image was determined by crop types and phenological stages, both in the spatial and temporal domain, respectively. For several crops, such as onion, winter wheat, corn, and sugar beet, our predictions are fitting well with R2 0.9409, 0.9824,0.9157, and 0.9749, respectively.

![Comparisons between the reference and the predicted image for dates: 2018/04/01 and 2018/04/16. (a), (g)Sentinel-2 NDVI reference and (b), (c), (h), (i) predicted images are compared visually. (d), (j)error histograms and (e), (f), (k), (l) density scatter plot compared from a statistical perspective. The red circle is the area with low accuracy.)](/images/data_fusion/sar_optical_time_series.png)

Reference paper: [Deeply synergistic optical and SAR time series for crop dynamic monitoring, RSE,247.](https://www.sciencedirect.com/science/article/pii/S0034425720303229)

Seasonal invariant change detection with bitemporal images
------
Change detection by comparing two bitemporal images is one of the most fundamental challenges for dynamic monitoring of the Earth surface. To serve this purpose, we proposed a metric learning-based generative adversarial network (GAN) (MeGAN) to automatically explore seasonal invariant features for pseudo change suppressing and real change detection. The MeGAN has the following contributions: 1) it automatically explores change patterns from the complex bitemporal background without human intervention and 2) it aims to maximally exclude pseudochanges from the seasonal transition term and map out real changes efficiently.

![Seasonal invariant change detection results. (Left: inputs, middle: pesudo changes, right: detected changes.)](/images/MeGAN.gif)

Reference paper: [Incorporating Metric Learning and Adversarial Network for Seasonal Invariant Change Detection, IEEE TGRS, 58(4), 2720 - 2731.](https://ieeexplore.ieee.org/document/8937747)

OCNN for high-resolution satellite imagery interpretation
------
Object-CNN (OCNN) provides a fast, accurate way for semantic labeling of satellite images while keeping detailed information (such as edges) about geographical entities. Different from the conventional CNN, we integrated the idea of OBIA and deep feature learning for improved image classification. It is an easy design to support satellite imagery mapping and benchmark evaluation.
![Flowchart of OCNN](/images/ocnn.gif)

Reference paper: [Object-Based Convolutional Neural Network for High-Resolution Imagery Classification, IEEE JSTARS, 10(7), 3386-3396.](https://ieeexplore.ieee.org/document/7890382) [Code](https://github.com/kdxiaozhi/OCNN)

Urban scene recognition with deeply transfered OSM data
------
Urban scenes refer to city blocks which are basic units of megacities, they play an important role in citizens’ welfare and city management. We present a hierarchical framework to transfer the existing OSM data to high-resolution images for semantic element determination and urban scene understanding. Two contributions have been made 1). it proposes a transfer learning strategy to boost deep learning-based image classification by transferring OSM prior knowledge to remote sensing images; 2). it proposes an effective bottom-up method for urban scene recognition by considering the spatial distributions of detected semantic objects. 

![Flowchart of Urban scene recognition](/images/urban.png)

Reference paper: [Exploring semantic elements for urban scene recognition: Deep integration of high-resolution imagery and OpenStreetMap (OSM), ISPRS Journal, 151, 237-250.](https://www.sciencedirect.com/science/article/pii/S0924271619300887)


Getting started
======


**Markdown generator**


For more info
------
More info can be found in [the CV](https://kdxiaozhi.github.io/cv/). 
