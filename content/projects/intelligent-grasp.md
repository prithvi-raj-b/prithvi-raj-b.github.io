---
date: '2025-07-31T09:53:42+02:00' # date in which the content is created - defaults to "today"
title: 'Intelligent Grasp Planning using LLM'
draft: false # set to "true" if you want to hide the content 


params:
    image:
        src: "images/works/intelligent-grasp.png"
        scale: 0.5

## The content is used for the description of the project
---
Prior to starting this project, I had worked with CNN based methods for an end-to-end perception and grasp planning pipeline. This work gave me the necessary prerequisite knowledge to begin work on my own iteration of the grasp planning pipeline. The work has also been published as a journal article: [DOI](https://doi.org/10.1007/s10846-025-02307-3)

Learning from this, I developed a novel grasp planning and manipulation pipeline capable of generating effective grasp poses for everyday objects in the environment, using a Robotiq three-fingered gripper on a UR5e manipulator. The pipeline used a combination of semantic knowledge from an LLM (Gemini Flash 2.5), image segmentation and classification using the DetIC model, and RANSAC on 3D Point Cloud data for query based pick and place operations. This work received the Best Paper award at the 2025 IEEE 4th International Conference on Smart Technologies for Power, Energy, and Control held at NIT Goa.

```