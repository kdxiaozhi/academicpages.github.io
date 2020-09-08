---
permalink: /
title: "Highlighted Researches!"
excerpt: "Wenzhi Zhao"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Cropland change detection with harmonic function and generative adversarial network (CropGAN)
------
GAN has been widely applied in semi-supervised learning, sample generation, and image classification. Meanwhile, GAN has been adopted to detect changes from binary images, and it overcomes the difficulty caused by training sample shortage. Still, the utilization of GAN models for time-series change detection remains unexploited. Different from binary image change detection, the time-series data demonstrates the phenological processes of cropland are much more complex in terms of change detection. To remedy this, the self-attention GAN is introduced to generate realistic samples for efficient change detection with time-series data.

--

![The general workflow of the CropGAN for crop change detection.)](/images/time_series/cropgan1.png)

Reference paper: [Cropland change detection with harmonic function and generative adversarial network, GRSL.][Data, Access Code: re5k](https://pan.baidu.com/s/19axjQIK2UwKEEVG1I8yVgw)

Crop Mapping from Sentinel-1 Polarimetric Time-Series with a Deep Neural Network
------
Timely and accurate agricultural information is essential for food security assessment and agricultural management. Synthetic aperture radar (SAR) systems are increasingly available in crop mapping, as they provide all-weather imagery. In particular, the Sentinel-1 sensor provides dense time-series data, thus offering a unique opportunity for crop mapping. However, in most studies, the Sentinel-1 complex backscatter coefficient was used directly which limits the potential of the Sentinel-1 in crop mapping. Meanwhile, most of the existing methods may not be tailored for the task of crop classification in time-series polarimetric SAR data. To solve the above problem, we present a novel deep learning strategy in this research. To be specific, we collected Sentinel-1 time-series data in two study areas. The Sentinel-1 image covariance matrix is used as an input to maintain the integrity of polarimetric information. Then, a depthwise separable convolution recurrent neural network (DSCRNN) architecture is proposed to characterize crop types from multiple perspectives and achieve better classification results. The experimental results indicate that the proposed method achieves better accuracy in complex agricultural areas than other classical methods. Additionally, the variable importance provided by the random forest (RF) illustrated that the covariance vector has a far greater influence than the backscatter coefficient. Consequently, the strategy proposed in this research is effective and promising for crop mapping.
![The general workflow of the proposed DSCRNN.)](/images/time_series/2020_RS_qy.png)
Reference paper: [Crop Mapping from Sentinel-1 Polarimetric Time-Series with a Deep Neural Network, Remote Sensing.](https://www.mdpi.com/2072-4292/12/15/2493)

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



For more info
------
More info can be found in [the CV](https://kdxiaozhi.github.io/cv/). 
