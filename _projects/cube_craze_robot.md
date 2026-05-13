---
layout: project
title: "MAE 3780 Final Robot Competition"
subtitle: "MAE 3780 Mechatronics, Spring 2026"
date: 2026-5-13
image: assets/images/cube-craze/robot1.jpg
tags: [robotics, embedded-c, mechatronics, competition]
---

### Summary

This project was the capstone of MAE 3780 Mechatronics, where teams of three designed and built autonomous robots to compete in a cube-collection tournament. Beyond the mechanical and electrical design, the project's core challenge was writing all firmware in C using direct AVR register access, giving me hands-on experience with hardware timers, interrupts, and H-bridge motor control.

---

### My Contributions

- Developed the robot's firmware in C without using any built in Arduino library functions along with my teammates
- Designed parts to be laser cut for the cube collecting mechanism
- Assembled and tested the robot
- Implemented logic updates and mechanism updates through an iterative testing process

---

### Robot Design

The robot uses a three-walled wooden enclosure mounted to the standard chassis to funnel
cubes inward. Deployable black paper skirts, held in place by rubber bands hooked onto a
positional servo, are released at the start of each match to expand the robot's perimeter
and interfere with opposing robots' QTI sensors. All turns during the match are to the
right, ensuring collected cubes stay funneled deeper into the enclosure rather than spilling out.

<div class="image-block-full">
  <img src="{{ site.baseurl }}/assets/images/cube-craze/robot_cad.jpeg"
       alt="SolidWorks CAD model of the robot"
       style="width:100%; display:block; margin:auto;">
</div>
<p style="text-align:center; font-size:0.9em; color:#666;">
  SolidWorks CAD model
</p>


### Additional Photos

  <div style="flex:1 1 0; min-width:0;">
    <img src="{{ site.baseurl }}/assets/images/cube-craze/robot2.jpg"
         alt="Robot collecting cubes"
         style="display:block; width:100%; height:auto;">
    <p style="text-align:center; font-size:0.85em; color:#666;">Robot collecting cubes</p>
  </div>


---
