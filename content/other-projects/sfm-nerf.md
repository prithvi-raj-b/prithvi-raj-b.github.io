---
date: '2025-12-12T12:53:42+02:00' # date in which the content is created - defaults to "today"
title: 'Buildings Built in Minutes: SfM and NeRF'
description: "Monocular Structure-from-Motion with bundle adjustment and a Neural Radiance Field, both implemented from scratch."
draft: false # set to "true" if you want to hide the content 


params:
    image:
        src: "images/works/sfm-nerf.png"
        scale: 0.5

## The content is used for the description of the project
---
[Github](https://github.com/prithvi-raj-b/CV-SfM-and-NeRF.git)

As part of the Computer Vision course at WPI, we implemented a complete monocular Structure-from-Motion pipeline from scratch. The pipeline involved SIFT-based feature matching, Fundamental Matrix estimation, Essential Matrix recovery, camera pose extraction and cheirality-based pose disambiguation. We then developed Linear and Nonlinear Triangulation, PnP with RANSAC and Sparse Bundle Adjustment to jointly optimize the 3D structure and multi-view camera poses by minimizing reprojection error.

In the second part of the project, we implemented NeRF from scratch, building a 5D radiance field MLP with differentiable volume rendering.
