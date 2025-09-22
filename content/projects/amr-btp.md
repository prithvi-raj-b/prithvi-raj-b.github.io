---
date: '2024-08-25T09:53:42+02:00' # date in which the content is created - defaults to "today"
title: 'Obstacle Aware Navigation and Mapping in a Dynamic Environment'
draft: false # set to "true" if you want to hide the content 

# link: "https://www.adrianmoreno.info" # optional URL to link the logo to

params:
    # button:
    #     icon: "icon-arrow-right"
    #     btnText: "Case Study"
    #     URL: "https://www.adrianmoreno.info"
    image:
        src: "images/works/amr-btp.png"
        scale: 0.7

## The content is used for the description of the project
---

For my Bachelor Thesis Project, I developed a sensor fusion algorithm and implemented it as the local planner of an AMR in simulation. RTabMapping was done using Point Cloud data from an RGB-D camera and GMapping was done using a 2D LiDAR. These two maps were then fused, enabling better obstacle avoidance around tables, chairs and other scenarios where just the 2D LiDAR would fail. I also implemented a dynamic collision avoidance system using DBSCAN to avoid unexpected obstacles during operation.


