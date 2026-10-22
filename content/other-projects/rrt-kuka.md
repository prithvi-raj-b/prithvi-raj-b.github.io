---
date: '2024-08-21T09:53:42+02:00' # date in which the content is created - defaults to "today"
title: 'Comparison of RRT Algorithms for RCM-constrained KUKA Manipulator'
draft: false # set to "true" if you want to hide the content 


params:
    image:
        src: "images/works/rrt-kuka.png"
        scale: 0.5

## The content is used for the description of the project
---
[Github](https://github.com/prithvi-raj-b/rrtstar-kuka-iiwa7.git)

As part of the Introduction to Motion Planning course at IIT Madras, I compared the performance of RRT, RRT* and Bi-Directional RRT for planning while maintaining a Remote-Center-of-Motion (RCM) constraint on a KUKA IIWA 7-DOF manipulator. I developed a sample environment in PyBullet to test the algorithms and compared their performance and rates of success.

```
