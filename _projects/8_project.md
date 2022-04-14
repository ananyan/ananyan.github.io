---
layout: page
title: Designing for emerging technologies
img: assets/img/DET/CuriousAndFurious.gif
description: interactive devices
category: UC Berkeley
---
<div class="row">
    <div class="w-50 p-3">
        {% include figure.html path="assets/img/DET/CuriousAndFurious.gif" alt = "Robot Eating Washers" class="img-fluid" %}
    </div>
</div>
<div class="caption">
    The GIF above is the "Curious and Furious" (and hungry) robot I made based on the Hungry Robot by EunChan Park on Youtube. If you hold the capacitive button too long, it will eat the washers!
</div>

## Overview
**Roles:** VR Development, Computer Vision, Mechanical Design,  Speech Recognition  
**Tools/Skills:** Raspberry Pi, Python, Google Cloud API, Unity, CAD (Fusion 360), 3D Printing   
**Time:** August - December 2019 (2 weeks  each)  
**Team:** 4 each (MechE, CompSci, HCI, Psych, Arch) 

The purpose of these projects was to design interactive devices using certain emerging technologies as creative materials. They were developed as part of DES INV-290-6, Designing for Emerging Technologies.

## Extra-Real: Virtual Reality (using Unity on Oculus Quest)
### **An Ocean's Story** 
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/DET/Anoceansstory.png" alt = "An Ocean Story cover image: hermit crab surrounded by trash" class="img-fluid" %}
    </div>
</div>

An Ocean’s Story is a VR experience that explores the effects of marine debris on marine life. 
Entering An Ocean’s Story will drop you in present-day Kamilo Point, Hawaii, where you will witness the accumulation 
of plastic marine debris from the Great Pacific Garbage Patch. You will find that you are no longer a human, 
but instead, are viewing the beach through the eyes of a much smaller creature - the hermit crab. 
You then begin your journey through the ocean, trying to avoid trash that may damage your shell. 
If you suffer significant damage to your shell, you have a few opportunities to find a replacement shell. 
Your goal is to survive until you reach the trash-free paradise at the end - our vision for the Kamilo Point of the future, 
if we as humans take responsibility for the problem we have caused. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/CKMGqEr92SU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

You, the user, are immersed into our experience from the perspective of a hermit crab. As the experience starts, 
you’re deployed on a beach. You can walk around, given enough space, or use both the controllers 
for movement, with the L joystick triggering the direction of movement and the R joystick triggering the change in the visual field. 
To your top right, you see a health bar which is full at the beginning. As the game starts, enter the water and you’re in a world where 
there’s a lot of pollution and trash is cascading down from the top of the ocean to the bottom. These trash objects are recognizable - plastic 
bags, pieces of paper, debris and crushed soda cans. Your objective is to move from the beach you’re deployed on to another beach 
at the end of the ocean, while avoiding the trash. If you collide with any piece of trash, your shell is damaged, 
and this is reflected in the health bar. Conversely, if you find a new shell, your health bar is reset to the max. 
Outside of this basic interaction, listen for ominous music and look out for the details in the terrain - 
your hands-turned-crab-claws and the decrease in trash as you metaphorically travel through time to the future, 
when pollution has been curbed due to better societal awareness and policy.

<a href="/assets/pdf/PROJ03_Process.pdf">PDF</a> of detailed design process.

## Conversation: Speech Recognition (using Google Cloud Speech-to-Text on RasPi)
### **Soulflower**
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/DET/Soulflower.png" alt = "Soulflower cover image: sunflowers in pot on stand" class="img-fluid" %}
    </div>
</div>

SoulFlower is a potted plant that encourages healthier emotional intra- and inter- personal relationships. 
First, it helps its owners be more in touch with their emotions, which often go overlooked during a hectic day. 
Additionally, it encourages friends and roommates who step into the room to better understand the unspoken 
emotional context, avoiding potentially awkward or unintentionally hostile conversations. One flower of SoulFlower 
is capable of drooping and dancing, giving its owner instant feedback on the sentiment of sentences that are uttered. 
A bouquet within SoulFlower keeps track of the accumulated sentiment throughout the day, which is a useful indicator 
for people entering the room to see and adjust their words and actions accordingly. Our current embodiment of SoulFlower 
is for a single-person bedroom, but a future iteration may also find it in multi-person households, where its utility 
in mediating unspoken emotional communication and empathy would become especially prominent.

<iframe width="560" height="315" src="https://www.youtube.com/embed/jrJ6WAsjsq0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<a href="/assets/pdf/PROJ02_Process.pdf">PDF</a> of detailed design process.

## Perception: Computer Vision (using Google Cloud Vision on RasPi)
### **Starbucks Steve: a gesture-based coffee counter assistant** 
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/DET/Steve.jpg" alt = "Starbucks Steve cover image: starbucks cup with arms on platform with screen giving choice of caffeine or decaf" class="img-fluid" %}
    </div>
</div>

Steve is a smart coffee assistant that was intended to help customers make decisions about their drinks. 
Upon perceiving a customer, Steve prompts a series of binary questions to guide the customer to choose aspects of their drink such as flavor, caffeine, or milk. 
Users interact with Steve by pointing left or right. Steve confirms the choice by lifting his left or right “arms” to mirror the user's gesture. 
He also gives feedback through display on the LCD screen and through a speaker. Designed in a shape that resembles a real Starbucks coffee cup, 
we hope Steve can help users make beverage choices more easily!

<iframe width="560" height="315" src="https://www.youtube.com/embed/Soylf5HEnM0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

[PDF](/assets/pdf/PROJ01_Process.pdf) of detailed design process.

## Robots: Mobility (using Husqvarna Automower)
### **HohohoBot** 
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/DET/Hohohobot.png" alt = "HohohoBot cover image: rendering of moving christmas tree with the caption spreading holiday cheer from far to near" class="img-fluid" %}
    </div>
</div>

The HoHoHoBot roams through the basement halls of Etcheverry Hall, across the breezeway to Soda Hall, 
and crosses the street to main campus, spreading holiday cheer across campus. It aims to bring people 
together through sharing well wishes and sentiments. By allowing people to record messages and listen 
to messages from other places, the HoHoHoBot gathers messages from one location and brings them to another 
in the form of a collaborative tree decorating activity.

<iframe width="560" height="315" src="https://www.youtube.com/embed/Rudonu3daCI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<a href="/assets/pdf/PROJ04_Process.pdf">PDF</a> of detailed design process.
