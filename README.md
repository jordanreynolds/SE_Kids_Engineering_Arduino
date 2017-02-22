# SE_Kids_Engineering_Arduino
SE Kids engineering day Arduino project


#Setup Instructions:

Install the Aurduino IDE as recommended. (Tested with 1.8.1)
No need to install board from Adafruit - use the standard built-in "AVR Boards" by Arduino with support for the Circuit Playground (tested with 1.6.17)

Install the following libraries:
Adafruit_GFX_Library
Adafruit_NeoMatrix
Adafruit_NeoPixel

Take the LUFA_hid.zip file and unzip it to your Arduino libraries folder, typically "C:\Users\<user>\Documents\Arduino\libraries" in Windows. The LUFA.h file should be in the path "C:\Users\<user>\Documents\Arduino\libraries\LUFA_hid\LUFA.h"

Copy the remaining files into a sketch folder called "SE_Kids_Engineering_Arduino" (typically C:\Users\<user>\Documents\Arduino\SE_Kids_Engineering_Arduino)

#Uploading Code
Note when this firmware is on the board the typical serial port operations in the IDE will not work. To upload, compile and upload, then when it starts looking for the com port press the reset button the the circuit playgorund twice.
