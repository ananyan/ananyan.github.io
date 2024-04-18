---
layout: page
title: Spatial Interactions for Interactive Design Space Exploration
img: assets/img/ICVR/generatiVRimage.png
description: ar/vr
category: 2022
---
<div class="row">
    <div class="w-50 p-3">
        {% include figure.html path="assets/img/ICVR/generatiVRimage.png" alt = "Many shelf design alternatives constrained based on desired placement of items" class="img-fluid" %}
    </div>
</div>
<div class="caption">
    Example of constraining the design space using the functionality filter in VR to place items where a user would want them on the shelf
</div>

## Overview
**Roles:** VR Development, Design Generation and Evaluation, User Study Design  
**Skills:** Unity, Rhino3D/Grasshopper, C-Sharp, User Study   
**Time:** August - December 2022  
**Team:** 3 (MechE, HCI)/Individual   

Second iteration of interactions developed for GeneratiVR project and used in a user study (published in ICED '23).

## VR Demo
Example of using the interactions to narrow down to a desired design (context: a shelf to display projects or books in a Design Institute's lobby).
<iframe width="560" height="315" src="https://drive.google.com/file/d/1_fd6jwaStWsA72pomCqgWaR6ba-WQVsn/view?usp=sharing" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Skip to Timestamp 01:39 - 02:29 for a demonstration of the Direct Manipulation Filter, which allows gestural specification of geometry  
Skip to Timestamp 04:43 - 05:24 for a demonstration of the Functionality Filter, which allows the placement of objects to specify how the design will function (how the shelf will hold items)  
Skip to Timestamp 5:45 - 7:00 for a demonstration of using both the Direct Manipulation Filter and Functionality Filter to constrain the design space based on both form and function  

## Reflection
This was an interesting exploration of how we might want to specify constraints or requirements using modalities other than text. In this case, VR allows an immersive way to specify desired functionality or size, as well as view the designs from different perspectives. However, a challenge with using VR in the way we implemented the interactions is that you cannot see the design from a "bird's eye view," which is a convenience of traditional 3D software. In addition, people are not used to interacting with design spaces in this way (at a higher-level of abstraction, based on use and gestural specification of geometry) compared to modifications at a parameter level. Therefore, more work would have to be done to understand how people can create a better mental model of how to leverage such an approach and what capabilities it may enable.
