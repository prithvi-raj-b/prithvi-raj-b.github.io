---
date: '2025-12-13T09:53:42+02:00' # date in which the content is created - defaults to "today"
title: 'Monosense: Monocular Perception Pipeline for Urban Scene Understanding'
draft: false # set to "true" if you want to hide the content 

# link: "https://www.adrianmoreno.info" # optional URL to link the logo to

params:
    image:
        src: "images/works/monosense.png"
        scale: 0.45

## The content is used for the description of the project
---
[Github](https://github.com/N-Raghav/Mono-Sense.git)

In this project from the Computer Vision course at WPI, we architected an end-to-end monocular perception pipeline over 27,000+ frames spanning 13 Tesla Model S sequences, unifying detection, depth, 3D pose, and velocity estimation into a Blender-rendered 3D scene. We trained custom YOLOv26 detectors on the BDD100K and LISA Traffic Sign datasets and added a vehicle subtype classifier.

My work involved developing 3D pose estimation through FCOS3D and Depth-Anything-V2 fusion, along with a 3-stage velocity pipeline using Lucas-Kanade ego-motion and RANSAC 6-DoF alignment for parked vehicle classification and collision prediction. We also implemented classical CV modules for traffic-light state and arrow detection, brake lights, road arrows, pedestrian pose using YOLOv8m, and YOLOWorld open-vocabulary detection of cones, barrels, and dustbins.

```
