
# maxduino

Modified version from https://github.com/rcmolina/MaxDuino_v1.66 for Keypad LCD Shield (not I2C and buttons read on Analog0 with resistors), and Arduino Mega 2560.
(TESTED on a CPC 6128)


- Software

Main changes: 

#define LCD_KEYPAD for selecting Keypad shield on userMAXconfig.h

When using LCD_KEYPAD I2C must be disabled.

readButton function as a wrapper for digitalRead, works with both Keypad's DAC analog pin and indvidual digital buttons.

Audio output is on pin 23

Motor pin is now on 25 (see pinSetup.h)

- Hardware

No need for audio amplifier neither audio/dc jacks, just conect to arduino headers to the DIN 5 connector.

SD card connection
http://house4u.com.ua/photos/solar-controller/arduino-SD-sch.jpg

Keypad pinout
https://hackster.imgix.net/uploads/attachments/869013/lcd-keypad-shield-pinout_cAw8K5UwWe.jpg

If you cannot see any digits on LCD, maybe you need to adjust the potentiometer.
