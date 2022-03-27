---
layout: page
title: motorized joystick for power wheelchair
img: assets/img/Joystick/Version1.jpg
description: assistive technology
category: MIT
---
<img src="/images/Joystick/Version1.jpg" alt = "First version of the motor attachment on Rhonda's wheelchair." style="position:relative" width="300">

## Overview
**Roles:** Mechanical Design Lead  
**Skills:** User Interviews, User Testing, Motor Selection, Machining  
**Time:** September - December 2018  
**Team:** 4 (MechE, EE) 

Developed as part of 2.78, Principles and Practices of Assistive Technology.

## The Problem
Multiple sclerosis can cause loss of strength in the arms. For power wheelchair users, the joystick juts out in front to allow
easy access and control. However, it can get in the way when trying to reach a sink or a table. In this case, the user has to manually
swing the joystick back, which can cause discomfort or in some cases, is not possible without assistance. A previous solution to this
problem was developed in the past in this class, but it lacked robustness, was not easy to debug the electronics, and could not be 
adapted for another user with even slightly different needs (our user was left-handed rather than right-handed).

**This project was a second iteration on developing an attachment to motorize the retracting of the joystick for a power wheelchair.**

## The Process
After meeting with Rhonda, our user, several times, we developed a first prototype. This process is shown in the video below.
<iframe width="560" height="315" src="https://www.youtube.com/embed/Ut_dXh0NC9Y" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
However, we found that after building it in the shop, when we tested it with Rhonda, it was not reliable. When attached to her 
wheelchair, the load on the motor was much higher than what we had initially accounted for. The joystick arm was 
deflecting due to the load of the joystick at the end, increasing the load on the motor beyond what it was able to handle. For this 
reason, we iterated on the design another time. First, we replaced the motor with a more powerful motor, though we had to trade-off
the speed of retraction. Then, we replaced the aluminum bars of the arm with thinner, but taller bars to prevent the deflection.
Finally, we made the bars out of steel, as we found that it improved the robustness of the attachment, despite being slightly heavier.  
 
## The Result
<img src="/images/Joystick/FinalVersion.jpg" alt = "Final version of motor attachment with new, stiffer linkage" style="position:relative" >
<img src="/images/Joystick/FinalVersionInstalled.jpg" alt = "Final prototype installed on Rhonda's wheelchair for testing" style="position:relative" >
The initial version and the modified version are described in detail in this <a href="https://www.instructables.com/id/Developing-a-Motorized-Retractable-Joystick/" target="_blank">Instructable</a>
which was featured on the website. The prototype was given to our user Rhonda. 
