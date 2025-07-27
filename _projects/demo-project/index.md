---
layout: post
title: Systems Engineering Project 1
description:  
skills: 
  - 3D Modelling
  - Python Programming
  - ROS 1 (Melodic)

main-image: /LIMO_Robot.png
---

---

# Project Overview
This project aims to deploy the LIMO Robot by AgileX and navigate an arena consisting of 8 different 1.33m x 1.5m plots themed around Changi Airport. The project utilises ROS 1 Navigation Stack and Real-Time Appearance-Based Mapping (rtabmap), in order to successfully navigate through the arena.
For more information regarding the project, you can check our group's [Github](https://github.com/pokohroh/ros-portfolio).

---
# Hardware Given

## LIMO by AgileX
{% include image-gallery.html images="LIMO_Robot2.png" height="400" %}
This project uses the LIMO Robot by AgileX, and its EAI XL2 LiDAR, ORBBEC® Dabai stereo depth camera, as well as other in-built sensors to perform SLAM, path planning and navigation, and obstacle avoidance.
The final goal being to succesfully navigate any given plot number within the arena.

---
# Arena Map Design
## Requirements  
To test the deployment of the LIMO Robot, each team was tasked to create a 1.33m x 1.5m sized map that emulated a particular landmark of Changi Airport for the LIMO to navigate. In my team's case, we were given the task to emulate Terminal 1.
Aside from the map size, there was also a additional requirement that the LIMO Robot was to navigate through the center of the map within a 5cm radius.

## Design Choices
To emulate Terminal 1's design, not only did our team try matching key design choices from the area itself. We also decided to include a key landmark from Terminal 1, the Kinetic Rain sculpture, in order to emulate it as best we can.

Following this, our team created a path layout that would ensure ample difficulty in order to test the LIMO Robot's navigation capabilities as seen here.

## Finalised Arena Design (SolidWorks)
{% include image-gallery.html images="Arena_Final.jpg" height="400" %}  

## Live Arena
{% include image-gallery.html images="Live_Arena.jpg" height="400" %}

---  
# Mapping & Live Demo

## Mapping
Below is the completed map of the entire arena as captured and displayed within RViz (ROS Visualisation)
{% include image-gallery.html images="Mapping_Image.jpg" height="400" %}  
  
## Live Demo
{% include youtube-video.html id="mY0nM8mVUw4" autoplay= "false"%}
