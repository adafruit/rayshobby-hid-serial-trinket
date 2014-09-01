========================================================

This folder contains Arduino code and host software to
demonstrate HID-class USB serial communication for AVRs
using V-USB. The code and circuit design are based on V-USB
http://www.obdev.at/products/vusb/index.html
and USnoobie. It is designed to work for ATmega328 but
can be adapted to other AVR microcontrollers as well.

The software is written by Ray Wang at Rayshobby LLC
and published under the Creative Commons Attribution-
ShareAlike (CC-SA) 3.0 license.

Frank: Original website is at http://rayshobby.net/?p=7363 and original github is at https://github.com/rayshobby/hid-serial
Frank: I am forking this to add support for Adafruit Industries Trinket, see https://learn.adafruit.com/trinket-fake-usb-serial
Frank: Some of the irrelevant folders have been removed from this fork
Frank: usbconfig.h is completely changed to support Trinket instead

========================================================

The folders are organized as follows:

- 'arduino code' contains the Arduino library for HIDSerial.
  To use it:
  * copy boards.txt (from hardware/arduino folder)
    to the corresponding folder in your arduino installation
    directory, and the HIDSerial library to your arduino's 
    libraries directory.
  * Run Arduino (the recommended version is 1.0.5 or 1.0.4).
  * Make sure you select Trinket from Tools -> Boards
  * Select any provided example from File -> Examples -> HIDSerial
  * Upload
  
- 'host software' contains the standalone applications and Processing
   source code for HIDSerialMonitor. Please check the README.txt
   therein.
   
========================================================
