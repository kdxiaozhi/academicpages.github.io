---
permalink: /
title: "个人简历"
excerpt: "赵文智"
author_profile: true
redirect_from: 
  - /cn/
  - /cn.html
---

测试中文
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
Urban scenes refer to city blocks which are basic units of megacities, they play an important role in citizensâ€?welfare and city management. We present a hierarchical framework to transfer the existing OSM data to high-resolution images for semantic element determination and urban scene understanding. Two contributions have been made 1). it proposes a transfer learning strategy to boost deep learning-based image classification by transferring OSM prior knowledge to remote sensing images; 2). it proposes an effective bottom-up method for urban scene recognition by considering the spatial distributions of detected semantic objects. 

![Flowchart of Urban scene recognition](/images/urban.png)

Reference paper: [Exploring semantic elements for urban scene recognition: Deep integration of high-resolution imagery and OpenStreetMap (OSM), ISPRS Journal, 151, 237-250.](https://www.sciencedirect.com/science/article/pii/S0924271619300887)


Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.