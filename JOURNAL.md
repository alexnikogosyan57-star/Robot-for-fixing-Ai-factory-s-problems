---
title: "Robot for fixing Ai factory's problems"
author: "Alex"
description: "This robot is participating in the ArmRobotics2026 competition, where it must autonomously navigate a 4×8 meter field and complete 8 tasks: 3 easy, 3 medium, and 2 difficult. The difficulty increases throughout the course, from precise line following and basic actions to color and object recognition, accurate navigation, strict time and physical constraints, and complex mechanical tasks that must be completed autonomously."
created_at: "2026-09-30"
---

# September 30: Case for a dedicated H-Bridge on a 2WD Smart Car: Half of it.

I imported the 3D models for the Smart Car 2WD chassis, the Arduino (along with its dedicated case), and the H-Bridge (with a suitable mounting base). I began designing a combined case for the Arduino and H-Bridge so they could be stacked, thereby saving space on the robot and creating a neat, attractive appearance.

![pcb layout](Files/Images/3D/Screenshot%202026-09-29%20201221.webp)

**Total time spent: 1 hours 16 min**

# November 1: Case for 9V battery

I created a custom case for a 9V battery so it could be inserted and connected to the power leads. It is convenient because it takes up little space and requires no screws to mount to the chassis.

![pcb layout](Files/Images/3D/Screenshot%202026-09-30%20175453.webp)

**Total time spent: 1 hours 12 minute**

# November 3: Case for the Arduino and H-bridge and added IR sensors.

I finished building the shared case for the H-Bridge and Arduino. It looks great and can be mounted to the chassis either with or without screws; it takes up less space and looks much neater. I also added two TCRT5000 IR sensors so the robot can follow a black line.

![soldering](Files/Images/3D/Screenshot%202026-10-03%20190346.webp)
![soldering](Files/Images/3D/Screenshot%202026-10-03%20190359.webp)

**Total time spent: 1 hours 1 minute**

# November 4: New sensors, accuracy, yellow line and black line.

I examined the design in detail and resized the parts intended to fit into the slots, accounting for the slight expansion (a few millimeters) that occurs during 3D printing. I added an extra TCRT5000 IR sensor on the right side and a VEML6400 color recognition sensor on the left to detect the yellow line and ensure smoother line-following performance. I also created a section of the test track's black line to visualize the scale in a real-world context.

![soldering](Files/Images/3D/Screenshot%202026-10-04%20200951.png)
![soldering](Files/Images/3D/Screenshot%202026-10-04%20201051.png)
![soldering](Files/Images/3D/Screenshot%202026-10-04%20201101.png)

**Total time spent: 1 hours 53 minute**
