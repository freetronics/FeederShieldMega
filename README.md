Feeder Shield Mega
==================
Copyright 2018-2020 Freetronics Pty Ltd  www.freetronics.com  

Pick and place feeder controller for DIY feeders. Compatible with the
0816 feeders designed by MGRL:

  https://docs.mgrl.de/maschine:pickandplace:feeder:0816feeder

These feeders are commonly used with DIY pick and place machines
running OpenPNP:

  http://openpnp.org

Run the MGRL feeder control firmware.

Adds an I2C display that can be used for reporting events and part
counts.

Uses 10-way IDC cables to connect batches of 4 feeders. Mates to the
MGRL0816 Feeder Link board, which bridges across the 4-pin connections
on 4 feeders mounted side by side.

Features:

 * 24 feeder outputs
 * PWM output and feedback input
 * GND and 5V supply to feeders
 * Software controlled feeder power
 * 128x32 OLED

You can view more online at:

  http://www.freetronics.com.au/fsm


INSTALLATION
------------
The design is saved as an EAGLE project. EAGLE PCB design software is
available from www.cadsoftusa.com free for non-commercial use. To use
this project download it and place the directory containing these files
into the "eagle" directory on your computer. Then open EAGLE and
navigate to the project.


DISTRIBUTION
------------
The specific terms of distribution of this project are governed by the
license referenced below.


LICENSE
-------
Licensed under the TAPR Open Hardware License (www.tapr.org/OHL).
The "license" folder within this repository also contains a copy of
this license in plain text format.
