---
layout: project
title: Delta and mobile robot   
img: assets/img/PizzaRobot/placetopping.gif 
description: ROS, Python, CAD (SolidWorks), Computer Vision, Hardware  
category: MIT
---
<img src="/images/PizzaRobot/placetopping.gif" alt = "Delta robot picks up and places a fake pepperoni" style="position:relative">

*The GIF shows our robotic system, named R.E.M.Y. (Robot for Expedited Manufacturing of Ya' pizzas) at work (4x speed).*
## Overview
**Roles:** Delta Robot Hardware, Mobile Robot Software  
**Skills:** ROS, Python, CAD (SolidWorks), Computer Vision, Hardware   
**Time:** February - June 2019   
**Team:** 9 (MechE, CompSci)

Developed as part of 2.12, Introduction to Robotics.

## The Problem
This project had several goals:

- Build a delta robot from a given base design
- Design and implement an end effector for the delta robot
- Develop software for the "chef" delta robot to identify, pick up, and place "toppings" on a "pizza"
- Develop software for the "waiter" mobile robot to navigate a board to deliver the "pizza"
- Develop integration and communication so the delta robot transfers the finished "pizza" to the mobile robot for delivery 

My primary roles were in building the delta robot and developing the software for the mobile robot. 

## The Process
The first step was to build the delta robot. We were provided with a base design, which we modified for improvement. We redesigned the frame so that
it would be more stable and created a fixture for the table so that it would be placed in the same place every time. In addition, we wanted our workspace
to be larger than what the base design could reach. To do this, we changed the length of the linkages, used ball joints with a larger angular range, and decreased
the size of the end plate. 

Calculated workspace for original ball joints (20 degrees)
<img src="/images/PizzaRobot/workspace20.png" alt = "3D graph showing workspace for delta robot using blue dots." style="position:relative" >

Calculated workspace for new ball joints (55 degrees)
<img src="/images/PizzaRobot/workspace55.png" alt = "3D graph showing improved, larger workspace for delta robot using blue dots." style="position:relative" >

Finally, we redesigned the spacers used to attach the linkages and joints together to reduce friction. The final robot is pictured below.
<img src="/images/PizzaRobot/deltarobot.jpg" alt = "Delta robot with metal frame and linkages surrounding a table with fake pizza within the lab." style="position:relative" >

For the end effector, we decided on a granular jamming system, which would allow us to relatively easily pick up the various topping shapes and sizes (compared to a 
motor-actuated gripper). This granular jamming end effector was controlled using a solenoid valve and vacuum pump as shown below. 
<img src="/images/PizzaRobot/endeffectorlogic.jpg" alt = "Diagram showing connections between valve, end effector, and limit switches." style="position:relative" >

The physical device was fabricated using a balloon, coffee grounds, and a 3D printed housing.
<img src="/images/PizzaRobot/endeffector.jpg" alt = "End effector with balloon, coffee grounds, and 3D printed housing." style="position:relative" >

Using a camera mounted to the top of the frame, software was developed using OpenCV to detect the colors and shapes of the toppings, as well as the locations in which
they should be dropped.
<img src="/images/PizzaRobot/toppingcv.png" alt = "Top view of pizza and toppings with green outlines and color labels." style="position:relative" >

Software was developed for the mobile robot to navigate the boards based on dead reckoning as well as april tags and computer vision for course correction. Finally, the two robots
communicated with each other through ROS nodes. The mobile robot would independently reach the table, but only continue on its path to the end once the delta robot was finished 
placing toppings and had transferred the pizza.

The following is a diagram of the system.
<img src="/images/PizzaRobot/robotsoftware.jpg" alt = "Block diagram of robot system software architecture." style="position:relative" >

## The Result
The final system worked on a rough level, but unfortunately, I can't find a video of the full system or even any videos we took in the later parts of the project, 
so I guess I can't provide full proof of that! Some of the challenges were adapting to different lighting to detect the colors of the toppings and ensuring that the 
failure of the delta robot to perfectly complete the toppings on the pizza would not prevent the robot from at least transferring 
the pizza and allowing the mobile robot to complete its task. Here are videos of the robot functioning at least in parts during testing (Last GIF is 2x speed):

<img src="/images/PizzaRobot/pickuptopping.gif" alt = "Delta robot picks up and places a fake pepperoni" style="position:relative">
<img src="/images/PizzaRobot/transferpizza.gif" alt = "Delta robot transfers pizza" style="position:relative">
<img src="/images/PizzaRobot/mobilerobotrun.gif" alt = "Mobile robot passes waiter obstacle and reaches end" style="position:relative">

Overall, this was a challenging project with several moving parts that had to all work for success at the system level. As with many projects, we likely would have figured out several of the problems given more time,
but it was a good lesson in working with an interdisciplinary team as well as integrating software and hardware! However, we did win an award for the best software in the class!
<img src="/images/PizzaRobot/swaward.JPG" alt = "Award for the 2.12 Introduction Robotics 2019 Term Project Competition for Robo's Pizzera Restaurant Automation. Best Software." style="position:relative">