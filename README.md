# Joystick Shield RG Custom
Joystick shield for Arduino Pro Micro with shift registers, i2c text LCD and ws2812 led support.
RG Custom PCB  shield allows you to easy create your own control panel, throttle or joystick device. 

Controller supports: 4 analogue inputs. (256 steps are more than enough to 10k Ohm pots), 40 inputs. Pushbuttons, toggle switches with pulse, rotary encoders, pov hats.
i2c text LCD displays. ws2812 leds.

### To build it you will need.
1. Shield PCB
2. Arduino pro micro
3. 5pcs CD4021BE shift registers
4. 5pcs 10kOhm sip9 array resistors.
5. 2.54mm Male PCB Single Row Straight Header Strip Connectors

Arduino IDE 1.6.6 (or above) library that adds a joystick to the list of HID devices an Arduino Leonardo or Arduino Micro (or any Arduino clone that is based on the ATmega32u4) can support. This will not work with Arduino IDE 1.6.5 (or below).

## You will need to install 3 additional libraries:
Info on how to install additional libraries can be found here.
https://www.arduino.cc/en/Guide/libraries#toc4

### Arduino Joystick library ver 1.0
https://github.com/MHeironimus/ArduinoJoystickLibrary/tree/version-1.0

### LiquidCrystal_I2C
https://github.com/marcoschwartz/LiquidCrystal_I2C

### Adafruit_NeoPixel
https://github.com/adafruit/Adafruit_NeoPixel

### Link on PCB in OSH Park https://oshpark.com/shared_projects/YERseqpP
