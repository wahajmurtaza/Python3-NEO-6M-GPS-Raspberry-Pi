# Python3-NEO-6M-GPS-Raspberry-Pi
This is source code for NEO-6M GPS module for Python3. It can be used on Raspberry pi or any device using python.


The previously open source codes don't work on new raspbian sketch or doesn't have support to python3.
This is code for decoding Neo-6m message and extracting exact latitudes and longitudes.

Pyserial library is required for working. Note that you have to define port name and connect port before executing the code.

It also has support for USB/TTL but the drivers must be installed properly.


# Installation
No isntallation is required for raspberry Pi or PC. Just python is required and pyserial library to be installed.

For raspberry pi serial or USB must be enable using
'raspi-config' 
command

or from configuration.

On raspberry pi both USB or Serial pins can be used.
