---
date: '2025-12-09T09:53:42+02:00' # date in which the content is created - defaults to "today"
title: 'Hierarchical Reinforcement Learning for Embodied Manipulation in Habitat 2.0'
draft: false # set to "true" if you want to hide the content 


params:
    image:
        src: "images/works/hrl.png"
        scale: 0.7

## The content is used for the description of the project
---
[Github](https://github.com/kohlir2020/WPI_DS551_G10_Final.git)

As part of the Reinforcement Learning course project, we implemented a Hierarchical Reinforcement Learning with Hindsight Experience Replay for navigation and manipulation tasks in a simulated apartment environment using Habitat Sim and PyBullet. The system consisted of a high-level policy that selected sub-goals and a low-level policy that executed actions to achieve those sub-goals. 

My work in the project involved implementing the above for a Franka Panda arm in simulation. We tested out PPO, A2C and SAC for the low-level policy and compared their performance in terms of success rate in achieving the sub-goals. We then trained a TD3 model for the high-level policy to select sub-goals. We improved the success rate from 0% to 37% after testing out different training methods like Curriculum Learning, Prioritized Experience Replay and tuning the HER parameters. The overall system was integrated with the Navigation Subsystem using an LLM for high-level decision making.

```