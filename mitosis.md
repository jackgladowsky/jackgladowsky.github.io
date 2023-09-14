---
layout: plain
---

# Mitosis

Mitosis is a 3D printer than can self-replicate and print everything 
you need to build another 3D printer besides the electronics! I am the 
electrical project lead where I am in charge of configuring the custom
Marlin firmware that our printer runs on, as well as wiring up the entire
printer and all of its accessories. 

![Mitosis Printer](/assets/img/mitosis/printer2.JPG)

[Marlin](https://github.com/MarlinFirmware/Marlin) is open-source firmware
built for 3D printers. There are many pre-configured binaries of Marlin
that you can download online for specific printers, but since ours is custom,
we had to define our own Marlin configuration. We first began by creating a base
configuration that could control the 5 different stepper motors the printer used. 
One motor for the X direction, one for the Y direction, two for the Z direction, 
and one for the extruder. The video below shows us controlling the motors for the 
first time using [Pronterface](https://www.pronterface.com/), which is another 
open-source software that lets you connect to and control your printer from a computer.

[Link Coming]()

We then hooked up the X and Z motors to get a first glimpse at how the
printhead moves around. The video below shows how shaky the printhead was,
but we have fixed that in version 2!

[Link Coming]()

We then configured Marlin to enable the extruder heating up and did a first test of
the extruder, which you can see below.

[Link Coming]()

Along with the main printer, we are also working on a 'Filastruder" which is a machine
that will take in plastic beads, and dispense filament that the printer can use. This is
super cost efficient because you can buy 10kg of pellets for only $100, and if you bought
10kg of spooled filament, it would cost you upwards of $200!

We are currently working on Version 2 of the printer, where we are designing a custom 
control board along with major upgrades to the frame of the printer to make it more stable.