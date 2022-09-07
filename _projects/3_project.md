---
layout: page
title: motorized joystick for power wheelchair
img: assets/img/Joystick/Version1.jpg
description: assistive technology
category: 2018
---
<div class="row">
    <div class="w-50 p-3">
        {% include figure.html path="assets/img/Joystick/Version1.jpg" alt = "First version of the motor attachment on Rhonda's wheelchair." class="img-fluid" %}
    </div>
</div>

## Overview
**Roles:** Mechanical Design Lead  
**Skills:** User Interviews, User Testing, Motor Selection, Machining  
**Time:** September - December 2018  
**Team:** 4 (MechE, EE) 

Developed as part of 2.78, Principles and Practices of Assistive Technology. My role in this project was interviewing/observing Rhonda initially and testing with her.
I was also in charge of designing and manufacturing the mechanical attachments that interfaced between the motor and Rhonda's joystick arm.  

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
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Joystick/FinalVersion.jpg" alt = "Final version of motor attachment with new, stiffer linkage" class="img-fluid" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Joystick/FinalVersionInstalled.jpg" alt = "Final prototype installed on Rhonda's wheelchair for testing" class="img-fluid" %}
    </div>
</div>

The initial version and the modified version are described in detail in this <a href="https://www.instructables.com/id/Developing-a-Motorized-Retractable-Joystick/" target="_blank">Instructable</a>
which was featured on the website. The prototype was given to our user Rhonda. 

## Reflection
There were many lessons learned from this project, particularly about how a theoretical design and the design in reality may not match up. Despite having access to a
test wheelchair arm and specifying a motor with a safety factor, we found that our motor could not handle the load and friction that was present in reality on Rhonda's wheelchair. Thus, we were
forced to make our device operate more slowly so that it would operate at all. I learned how translating a design into its actual operating conditions can shed light on unforeseen problems and on
the trade-offs that often need to be made when designing for performance. Performing frequent testing under the operating environment was impossible because it would disturb Rhonda's daily life, but it
likely would have helped if we had planned ahead and created a few design variations to make the most of our occasional testing sessions and discover the problems upfront.
