---
title: "Project Proposal"
permalink: "/Project Proposal/"
mathjax: true
layout: page
---

# Project Proposal #

## Background

Realistic locomotion in robots has been a long-standing challenge. There has been great success with robots like Laikago in mimicking animal locomotion with agility. Laikago has 18 degrees of freedom. Robots like Laikago with a high number of degrees of freedom and multiple sensors have had success with locomotion. Cheaper robots like Bittle with only 8 degrees of freedom and fewer sensors have not yet been able to achieve the same success. It would be an interesting development if a much cheaper robot could perform as well as its more expensive counterparts. Similar to how the Laikago robot was trained we aim to train the Bittle robot to walk using reinforcement learning. Achieving that result with the Bittle would help us gain useful information regarding approximating the sensors. 

## Timeline
* Add Raspberry Pi on Arduino
* Get Isaac Gym running
* Make sure IMU data is matching simulation data
* Use Reinforcement Learning on Bittle 
* Get Bittle walking

## Questions?
* How do we approximate the sensing ?
* How to better control the actuator ?
* How to come up with a new learning method that builds off the complex stuff?
    
## Resources
* [Petoi Bittle Manual](https://bittle.petoi.com/)
* [Learning Agile Robotic Locomotion Skills by Imitating Animals](https://xbpeng.github.io/projects/Robotic_Imitation/2020_Robotic_Imitation.pdf)
* [Jason’s Repo](https://github.com/jasonjabbour/motion_imitation_tiny_robots)
* [Jason Raspberry Pi Setup](https://github.com/jasonjabbour/motion_imitation_tiny_robots/blob/master/bittle_controller/Raspberry%20Pi%20Zero%202W%20Setup.pdf)
* [Jason’s Open Cat Repo](https://github.com/jasonjabbour/Tiny-Robot-Motion-Imitation-OpenCat)
* [PyBullet Quickstart guide](http://dirkmittler.homeip.net/blend4web_ce/uranium/bullet/docs/pybullet_quickstartguide.pdf)
* [Isaac Gym Video](https://www.youtube.com/watch?v=d9HEhXH5_hs)


