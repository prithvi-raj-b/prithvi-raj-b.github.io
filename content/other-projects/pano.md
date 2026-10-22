---
date: '2025-12-10T09:53:42+02:00' # date in which the content is created - defaults to "today"
title: 'AutoPano: Image Stitching using Classical and Deep Learning Methods'
description: "Panorama stitching with a classical pipeline (corners, ANMS, RANSAC homography, blending) compared against supervised and unsupervised deep homography networks."
draft: false # set to "true" if you want to hide the content 


params:
    image:
        src: "images/works/pano.png"
        scale: 0.5

## The content is used for the description of the project
---
[Github](https://github.com/prithvi-raj-b/CV-MyAutoPano.git)

In this project, we developed an image stitching pipeline that generates panoramic images from a set of input images. Initially we implemented a classical image stitching pipeline using Shi-Tomasi corner detection, ANMS, feature descriptor extraction, SSD feature matching, RANSAC-based homography estimation and multi-band blending. We then implemented supervised and unsupervised CNN architectures inspired by Deep Image Homography Estimation to directly predict the homography between pairs of images, incorporating TensorDLT and spatial transformer layers for differentiable warping and photometric loss optimization. The two approaches were evaluated on a dataset of images captured in various environments, and the results were compared in terms of stitching quality and computational efficiency.
