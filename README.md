Rack32 ESP32 rack-mount controller with Ethernet
================================================

Copyright 2021 SuperHouse Automation Pty Ltd  www.superhouse.tv

A general purpose control board for rack mount projects, compatible
with the [Open eXtensible Rack System](https://oxrs.io/).

![Rack32 PCB](Images/RACK32-v1_0-oblique-1024.jpg)

DIY rack-mount projects often require an Ethernet connection, a
status display, power regulation, and other features that are not
specific to the project.

This board fits into a rack-mount case and provides those common
features so they don't have to be recreated every time.

Features:

 * ESP32 microcontroller with WiFi.
 * 10/100Mbps Ethernet.
 * Support for both DIY (12V) PoE and 48V 802.3af PoE.
 * Pluggable terminal block for optional external DC power input.
 * Automotive-grade voltage regulator for harsh electrical environments.
 * 6-way IDC "I2C-Breakout" header for linking to other boards.
 * 8-way IDC "SPI-LCD" header for connection to an LCD.
 * USB-C connector for loading firmware.
 * Auto power source selection between USB-C, PoE, and external DC.
 * I/O header with power, 2 x I2C ports, and second hardware serial port.
 * Micro SD card slot for config files, logs, and media storage.
 * Onboard temperature sensor.
 * Header for front-panel power LED.
 * Can be built with onboard PCB antenna or external WiFi antenna.

More information:

  [www.superhouse.tv/rack32](http://www.superhouse.tv/rack32)

INSTALLATION
------------
The design is saved as an EAGLE project. EAGLE PCB design software is
available from www.cadsoftusa.com free for non-commercial use. To use
this project download it and place the directory containing these files
into the "eagle" directory on your computer. Then open EAGLE and
navigate to the project.


CREDITS
-------
Designed by Jonathan Oxer jon@oxer.com.au


DISTRIBUTION
------------
The specific terms of distribution of this project are governed by the
license referenced below.


LICENSE
-------
Licensed under the TAPR Open Hardware License (www.tapr.org/OHL).
The "license" folder within this repository also contains a copy of
this license in plain text format.
