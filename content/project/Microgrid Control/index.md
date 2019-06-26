---
title: Autonomous operation of a hybrid microgrid using centralized and distributed control
summary: In this section, it describe the master thesis proposal about to microgrid hybrid control.
tags: 
- Control
- Microgrid
- Hybrid-microgrid
- PID
- Cooperative control
- Simulation systems

date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by Diego Salazar
  focal_point: Top

links:
url_poster: https://drive.google.com/file/d/1KS3BKvVT1mJQPtMvDXZoR3rbjcyY1Vpm/view?usp=sharing
url_code: ""
url_pdf: ""
url_slides: https://drive.google.com/file/d/1zfOqpe0js_f8y08NUCU69Z_1D-sbyRTI/view?usp=sharing
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

This work is based on the master thesis proposal entitled "Autonomous
operation of a hybrid microgrid using centralized and distributed
control”. The selected microgrid architecture is composed of two Direct
Current distribution buses and allows both grids connected and islanded
operation. In Fig. 1, from left to right, the first bus is an Extra Low
Voltage Direct Current (ELVDC) that operates to 48VDC, the second bus
is Low Voltage Direct Current (LVDC) that operates to 240 VDC. Each
bus interconnects several units that instantaneously supply, store or
consume energy. In fact, each connected unit has a first level controller,
which provides regulation of inner variables such as current and power.
Besides, the development of any hybrid microgrid should guarantee the
energy balance and regulation of the constant voltage in the buses, with
the purpose of synchronizing each of the interconnected units. The
propose includes a cooperative master-slave control where the control
action changes between Pv, Pbatt, and Pilc. Each unit has different types
of operation modes. And, the cooperative control will choose which unit
is the master control. For the transition between the two units,
cooperative control will be regulated with them at the same time using
the logistic function as a transition reference.

**[See the poster Cooperative master–slave control for a microgrid ELVDC bus](https://drive.google.com/file/d/1KS3BKvVT1mJQPtMvDXZoR3rbjcyY1Vpm/view?usp=sharing)**

