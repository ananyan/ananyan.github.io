---
layout: page
title: latte yo-yo
img: assets/img/Latte/Latteyoyo.png
description: consumer product
category: MIT
---
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Latte/Latteyoyo.png" alt = "Final manufactured yoyo with and without cup" class="img-fluid" %}
    </div>
</div>

## Overview
**Roles:** Mold Design (3D Printed and Machined), Manufacturing (Injection-molded base)  
**Skills:** Design for Manufacturing, CAD (SolidWorks), CAM (MasterCAM), 3D Printing, CNC Milling, Injection Molding, Quality  
**Time:** September - December 2018  
**Team:** 5 (MechE) 

Developed as part of 2.008, Design & Manufacturing II.

## The Problem
The goal of this project was to design a yo-yo for manufacturing at scale.  

Due to a shared love of coffee shops, my team designed a yo-yo based on a latte. The yo-yo required a base with a fitted metal shim for weighting, a snap-fit between the "coffee" and the base, 
a fit between an injection molded "coffee" and the thermoformed part "foam", and a thermoformed "cup." 

## The Process
The yo-yo was first modeled using SolidWorks.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Latte/LatteYoyoCAD.jpeg" alt = "CAD model of blue yoyo with brown coffee and white foam art that looks like leaves." class="img-fluid" %}
    </div>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Latte/LatteYoyoWithCup.jpeg" alt = "CAD model of yoyo sitting within white cup." class="img-fluid" %}
    </div>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Latte/Exploded.png" alt = "Exploded view of yoyo parts (cup, base piece, connector, shim, foam piece, coffee piece)." class="img-fluid" %}
    </div>
</div>

This model was then used to design the molds. MasterCAM was used to create the toolpaths for creating the molds from aluminum and then the molds were made using
a CNC mill and a CNC lathe. A mold was 3D printed using an SLA printer for thermoforming the "foam." 
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Latte/Milling.jpeg" alt = "CNC milling the mold for the yoyo base piece." class="img-fluid" %}
    </div>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Latte/BaseMold.jpeg" alt = "Finished yoyo base mold with magnets to hold the shim." class="img-fluid" %}
    </div>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Latte/CoffeeMold.jpeg" alt = "Finished CNC milled mold for the coffee piece with a negative pattern for the latte art." class="img-fluid" %}
    </div>
</div>

Test runs were conducted for all of the parts to optimize the process parameters and ensure the parts fit together as desired. The molds had to be 
modified a couple of times to improve the snap-fit. Finally, we did a production run and produced 100 of each part (50 of the cup) and assembled
50 yo-yos.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Latte/AssemblyLine.jpeg" alt = "Layout of parts to assemble 50 yoyos." class="img-fluid" %}
    </div>
</div>

The full process is shown in the video below.
<iframe width="560" height="315" src="https://www.youtube.com/embed/UWJcgpvfgeg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## The Result
The final yo-yo is shown with and without its "cup" below. The yo-yos were subject to a drop test to ensure that they did not fall apart.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Latte/FinalYoyo.jpeg" alt = "Final manufactured yoyo without cup" class="img-fluid" %}
    </div>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Latte/WithCup.jpeg" alt = "Final manufactured yoyo inside thermoformed cup" class="img-fluid" %}
    </div>
</div>
