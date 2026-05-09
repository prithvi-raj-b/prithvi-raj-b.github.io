---
date: '2025-12-14T09:53:42+02:00' # date in which the content is created - defaults to "today"
title: 'Deep Visual-Inertial Odometry'
draft: false # set to "true" if you want to hide the content 

# link: "https://www.adrianmoreno.info" # optional URL to link the logo to

params:
    image:
        src: "images/works/dvio.png"
        scale: 0.65

## The content is used for the description of the project
---
[Github](https://github.com/N-Raghav/deep-visual-inertial-odometry.git)

As part of the Computer Vision course at WPI, we designed an end-to-end deep visual-inertial odometry research project for downward-facing UAV cameras. We built a synthetic VIO dataset by integrating Blender photorealistic rendering with an IMU simulator over oval, clover, and spiral trajectories, producing aligned ground-truth pose, IMU, and altimeter streams.

The work involved reproducing AirIO and AirIMU for IMU-only odometry and a Siamese MobileNetV2 + correlation + LSTM architecture for vision-only odometry, then fusing the two branches via a cross-attention module for full 6-DoF VIO. We benchmarked the proposed pipeline against PRGFlow on ATE, RTE, and mean rotation error across multiple trajectory types. I also extended PRGFlow with an explicit yaw-prediction head, removing its reliance on the IMU for in-plane rotation, and quantified the accuracy trade-off against the original 3-scalar formulation.

```
