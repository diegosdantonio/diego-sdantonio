---
title: Modelling, identification and control of a quadcopter 
summary: In this section, you will find my research report to obtain the title of electronic engineer.
tags: 
- Path Following
- Control systems
- Robotics systems
- Quadricopter
- PID

date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Top

header:
  image: "bannerthesis.jpg"
  caption: ""

links:
- name: Research report
  url: https://drive.google.com/file/d/1cLvQb9oe7LSownHyC2hA0GqO0C8ioIdD/view?usp=sharing
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Currently, the use of Drones, in precision agriculture, is of vital importance for the transport of agricultural materials, crop monitoring, cartographic mapping in relief, among others. Of the union between D + TEC group Unibague  and Fedearroz borned a project about to research in precision agriculture. The aim is detect causes stress in rice. This can be determined in using high resolution, multispectral and thermographic cameras.

{{< gallery >}}
  
Quadcopter, also known as quadrotor, is a helicopter with four rotors. The rotors are directed upwards and they are placed in a square formation with equal distance from the center of mass of the quadcopter. The quadcopter is controlled by adjusting the angular velocities of the rotors which are spun by electric motors. Quadcopter is a typical design for small unmanned aerial vehicles (UAV) because of the simple structure. 

Quadcopter has received considerable attention from researchers as the complex phenomena of the quadcopter has generated several areas of interest. The basic dynamical model of the quadcopter is the starting point for all of the studies but more complex aerodynamic properties has been introduced as well, like the turbulence, fails, etc. Different control methods has been researched, including PID controllers, LQR, predictive.

This work show, the control in pitch, roll and yaw of non comercial quadcopter, using a raspberry pi and a shield Navio2, the code was write in Python, C++ and Assembler. In fact The control methods will showed PID, LQR and one PID variant.

<iframe width="560" height="315" src="https://www.youtube.com/embed/videoseries?list=PLOokMXg9oefW431q2Zm5pXP6OSRPcbTYV&index=3" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

