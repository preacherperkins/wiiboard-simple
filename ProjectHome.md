# Wiiboard Simple #

First of all, this is considered to be an "extension" to the wiimote simple library found at (http://code.google.com/p/wiimote-simple/). It enables users to "easily" utilise the Nintendo Wii Balance Board with their own projects.

The design of the library is based similarly to wiimote simple so that users can use both libraries without the need to learn two completely different libraries.

There is also a python version of the library (although usage is different to the java version).


## Features ##

  * Measure someone's balance by reading force pressure data (converted to KG)
  * Respond to the power button push
  * Set the power button LED on or off


## Instructions ##

Requirements (Java version):
  * Java SDK (1.6 for now)
  * An implementation of JSR-82 (e.g. Bluecove or Avetana)
  * Bluetooth drivers

Requirements (Python version):
  * Python 2.5
  * PyBlueZ
  * Bluetooth drivers


For the bluetooth drivers, the library will not work under the windows winsock bluetooth stack.
The library has been tested with WIDCOMM drivers under windows XP and Vista.
It should be able to work on linux and 32-bit mac machines.

Note: the python version probably won't work on mac machines