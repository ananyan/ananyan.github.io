---
layout: page
title: Designing for emerging tech
img: assets/img/DET/CuriousAndFurious.gif
description: design, course (Berkeley)
category: 2019
---
## <u>Overview</u>
**My Role:** VR Development, computer vision and speech recognition for interactive devices, mechanical design for physical prototypes  
**Tools/Skills:** Raspberry Pi, Python, Google Cloud API, Unity, CAD (Fusion 360), 3D Printing   
**Timeline:** August - December 2019 (2 weeks  each)  
**Team:** 4 each (MechE, Computer Science, HCI, Psychology, Architecture) 

## <u>Context</u>
Technology, from algorithms that can recognize faces, voices, or gestures to robots that can share a workspace with humans, has the potential to fundamentally change how humans experience the world they live in. It is important to have the technical fluency and creativity to design solutions that embed these technological advances into society's daily activities in ways that improve the quality of life.

## <u>Goal</u>
Design speculative experiences and devices using emerging technologies, such as mixed reality, machine learning, and robotics, as creative materials

## <u>Extra-Real: Virtual Reality (using Unity on Oculus Quest)
### **An Ocean's Story** 
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/DET/Anoceansstory.png" alt = "An Ocean Story cover image: hermit crab surrounded by trash" class="img-fluid" %}
    </div>
</div>

An Ocean’s Story is a VR experience that explores the effects of marine debris on marine life. Entering An Ocean’s Story will drop you in present-day Kamilo Point, Hawaii, where you will witness the accumulation of plastic marine debris from the Great Pacific Garbage Patch. You will find that you are no longer a human, but instead, are viewing the beach through the eyes of a much smaller creature - the hermit crab. You then begin your journey through the ocean, trying to avoid trash that may damage your shell. If you suffer significant damage to your shell, you have a few opportunities to find a replacement shell. Your goal is to survive until you reach the trash-free paradise at the end - our vision for the Kamilo Point of the future, if we as humans take responsibility for the problem we have caused. 

<div align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/CKMGqEr92SU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

You, the user, are immersed into our experience from the perspective of a hermit crab. As the experience starts, you’re deployed on a beach. You can walk around, given enough space, or use both the controllers for movement, with the L joystick triggering the direction of movement and the R joystick triggering the change in the visual field. To your top right, you see a health bar which is full at the beginning. As the game starts, enter the water and you’re in a world where there’s a lot of pollution and trash is cascading down from the top of the ocean to the bottom. These trash objects are recognizable - plastic bags, pieces of paper, debris and crushed soda cans. Your objective is to move from the beach you’re deployed on to another beach at the end of the ocean, while avoiding the trash. If you collide with any piece of trash, your shell is damaged, and this is reflected in the health bar. Conversely, if you find a new shell, your health bar is reset to the max. Outside of this basic interaction, listen for ominous music and look out for the details in the terrain - your hands-turned-crab-claws and the decrease in trash as you metaphorically travel through time to the future, when pollution has been curbed due to better societal awareness and policy.

<a href="/assets/pdf/PROJ03_Process.pdf">PDF</a> of detailed design process.

## <u>Conversation: Speech Recognition (using Google Cloud Speech-to-Text on RPi)</u>
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

<div align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/jrJ6WAsjsq0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<a href="/assets/pdf/PROJ02_Process.pdf">PDF</a> of detailed design process.

## <u>Perception: Computer Vision (using Google Cloud Vision on RPi)</u>
### **Starbucks Steve: a gesture-based coffee counter assistant** 
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/DET/Steve.jpg" alt = "Starbucks Steve cover image: starbucks cup with arms on platform with screen giving choice of caffeine or decaf" class="img-fluid" %}
    </div>
</div>

Steve is a smart coffee assistant that was intended to help customers make decisions about their drinks. Upon perceiving a customer, Steve prompts a series of binary questions to guide the customer to choose aspects of their drink such as flavor, caffeine, or milk. Users interact with Steve by pointing left or right. Steve confirms the choice by lifting his left or right “arms” to mirror the user's gesture. He also gives feedback through display on the LCD screen and through a speaker. Designed in a shape that resembles a real Starbucks coffee cup, we hope Steve can help users make beverage choices more easily!

<div align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/Soylf5HEnM0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

[PDF](/assets/pdf/PROJ01_Process.pdf) of detailed design process.

## <u>Robots: Mobility (using Husqvarna Automower)</u>
### **HohohoBot** 
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/DET/Hohohobot.png" alt = "HohohoBot cover image: rendering of moving christmas tree with the caption spreading holiday cheer from far to near" class="img-fluid" %}
    </div>
</div>

The HoHoHoBot roams through the basement halls of Etcheverry Hall, across the breezeway to Soda Hall, and crosses the street to main campus, spreading holiday cheer across campus. It aims to bring people  together through sharing well wishes and sentiments. By allowing people to record messages and listen to messages from other places, the HoHoHoBot gathers messages from one location and brings them to another in the form of a collaborative tree decorating activity.

<div align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rudonu3daCI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<a href="/assets/pdf/PROJ04_Process.pdf">PDF</a> of detailed design process.

## <u>Reflection</u>
All of these projects were developed as part of the course Designing for Emerging Technologies. They allowed us to exercise our creativity and to speculate on unique ways in which technology can be used for various purposes and begin to see if they are actually feasible! Note: The thumbnail GIF is the "Curious and Furious" (and hungry) robot I made based on the Hungry Robot by EunChan Park on Youtube. If you hold the capacitive button too long, it will eat the washers!
