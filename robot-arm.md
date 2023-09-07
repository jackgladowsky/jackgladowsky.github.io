---
layout: plain
---

# FPGA Robot Arm Project
In my second year at Northeastern I took Embedded Design. Our final project 
was to design a program using Quartus Schematic to control the robot arm.
We were simulating the robot arm being used on an assembly line, where it 
would repeteively pick and place items down. For our project, we used a water 
bottle as the item to pick and place.  

We first had the user manually input the starting and ending positions using the switches
and buttons on the DE1-SoC that was provided to us.  

![DE1-SoC Buttons and Switches](/assets/img/robot-arm/DE1-SoC_Layout_top_01-01.jpg)

The robot had 5 degrees of freedom, which means it has 5 joints where the arm can move at.
The user was able to select a corresponding switch to turn on that joint, and then by using
2 of the buttons, they were able to rotate the joint.

Once the starting and ending positions were set, the user would flip another switch that would
set the robot moving back and forth between the starting and stopping positions. I added custom 
logic to make the arm move high enough to make sure the bottle would not collide with the table. 
I also added logic to smoothen out the transition between the two positions so the bottle would 
not fall out of the robotic arms grip.

If you want a more detailed explanation of how the program works please check out the paper I wrote
to accompany this project: [Robot Arm Paper](/assets/pdf/Jack%20Gladowsky%20Robot%20Arm%20Paper.pdf).
Also check out this youtube that explains how the entire thing works: [Robot Arm Video](https://youtu.be/saduSDQNsCo).

![Robot Arm Gif](/assets/gifs/robotarm-gif.gif)
<!--[Robot Arm](/assets/img/robot-arm/robot-arm.jpg)-->
