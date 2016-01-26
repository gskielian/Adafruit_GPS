## Drone Sampler GPS

We're making slight modifications to adapt this to a pollution geostamping drone.

## List of Mods and Settings:

* using/modding the parsing.pde example which is compatible with Arduino Nano
* minifying code for sample time, altitude, latitude, and longitude
* using this without interrupts -- and will merge with other libraries

## Connections

1. Connect TX of the GPS module to Digital 3
2. Connect RX of the GPS module to Digital 2
3. Connect VCC and Gnd to 5v and GND respectively


## Many Thanks to Adafruit for Open Sourcing this :D


This is the Adafruit GPS library - the ultimate GPS library
for the ultimate GPS module!

Tested and works great with the Adafruit Ultimate GPS module
using MTK33x9 chipset
    ------> http://www.adafruit.com/products/746

These modules use TTL serial to communicate, 2 pins are required to  
interface

Adafruit invests time and resources providing this open source code, 
please support Adafruit and open-source hardware by purchasing 
products from Adafruit!

Written by Limor Fried/Ladyada  for Adafruit Industries.  
BSD license, check license.txt for more information
All text above must be included in any redistribution

To download. click the "Download ZIP" at the right side, extract the archive and rename the uncompressed folder Adafruit_GPS. Check that the Adafruit_GPS folder contains Adafruit_GPS.cpp and Adafruit_GPS.h

Place the Adafruit_GPS library folder your <arduinosketchfolder>/libraries/ folder. You may need to create the libraries subfolder if its your first library. Restart the IDE.
