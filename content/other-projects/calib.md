---
date: '2025-12-11T09:53:42+02:00' # date in which the content is created - defaults to "today"
title: 'AutoCalib: Camera Calibration using Checkerboard Pattern'
draft: false # set to "true" if you want to hide the content 

# link: "https://www.adrianmoreno.info" # optional URL to link the logo to

params:
    image:
        src: "images/works/calib.png"
        scale: 0.5

## The content is used for the description of the project
---
[Github](https://github.com/prithvi-raj-b/CV-AutoCalib.git)

I built an automatic camera calibration pipeline from scratch using a checkerboard pattern to estimate a camera’s intrinsic parameters, extrinsic pose, and radial lens distortion. Following the method proposed by Zhengyou Zhang, I implemented homography-based initialization and Rodrigues parameterization for rotation to minimize reprojection error across multiple calibration images. The parameters were optimized using the Levenberg-Marquardt Algorithm. I then developed a custom reverse-mapping image rectification module with bilinear interpolation to remove distortion using the optimized parameters.

```