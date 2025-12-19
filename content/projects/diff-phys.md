---
date: '2025-12-12T09:53:42+02:00' # date in which the content is created - defaults to "today"
title: 'Task Formulations for Differentiable Physics Simulation Based Learning for Agile Drones'
draft: false # set to "true" if you want to hide the content 

# link: "https://www.adrianmoreno.info" # optional URL to link the logo to

params:
    image:
        src: "images/works/diff-phys.png"
        scale: 0.4

## The content is used for the description of the project
---
This project involved working with Agile Drones trained using a Differentiable Physics based simulator that simulated the drones as point masses for ease of computation. My work involved testing out different loss functions and model architectures for the learning and compiling the results. 

I included a dynamic obstacle loss term that used the velocity of the obstacle along with a clearance radius for the drone to avoid. I also tested out processing 4 consecutive frames to capture temporal relationships between frames. I then compared the results with validation runs including varying number of dynamic obstacles to measure the impact of the changes.

```