---
title: "[CVPR 2022] How Much Does Input Data Type Impact Final Face Model Accuracy?"
tags:
- Computer Vision
- Featured
subtitle: ""
external_link: 'https://openaccess.thecvf.com/content/CVPR2022/html/Luo_How_Much_Does_Input_Data_Type_Impact_Final_Face_Model_CVPR_2022_paper.html'
publication_types:
  - "1"
authors:
  - Jiahao Luo 
  - Fahim Khan
  - Issei Mori
  - Akila de Silva
  - Eric Ruezga
  - Minghao Liu
  - Alex Pang
  - James Davis
publication: 2022 The Conference on Computer Vision and Pattern Recognition (CVPR)
publication_short: CVPR
abstract: Face models are widely used in image processing and other domains. The input data to create a 3D face model ranges from accurate laser scans to simple 2D RGB photographs. These input data types are typically deficient either due to missing regions, or because they are under-constrained. As a result, reconstruction methods include embedded priors encoding the valid domain of faces. System designers must choose a source of input data and then choose a reconstruction method to obtain a usable 3D face. If a particular application domain requires accuracy X, which kinds of input data are suitable? Does the input data need to be 3D, or will 2D data suffice? This paper takes a step toward answering these questions using synthetic data. A ground truth dataset is used to analyze accuracy obtainable from 2D landmarks, 3D landmarks, low quality 3D, high quality 3D, texture color, normals, dense 2D image data, and when regions of the face are missing. Since the data is synthetic it can be analyzed both with and without measurement error. This idealized synthetic analysis is then compared to real results from several methods for constructing 3D faces from 2D photographs. The experimental results suggest that accuracy is severely limited when only 2D raw input data exists.
summary: 'We have quantified and analyzed the base-line reconstruction accuracy of a face model as a function of source
data type commonly used in the domain.'
draft: false
featured: false
url_pdf: 'https://openaccess.thecvf.com/content/CVPR2022/papers/Luo_How_Much_Does_Input_Data_Type_Impact_Final_Face_Model_CVPR_2022_paper.pdf'
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
date: "2022-09-18T23:31:31.369Z"
---
