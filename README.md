# ArduinoNeoPixel_Button
NeoPixel Leds/ Addressable Leds pattern changing setup with single Push Button 

Neopixel LED Pattern changer with Arduino uno and a single Push Button

The connections are as follows 
Button's 1st Pin = Digital pin 2 
Button's 2nd Pin = GND
Neopixel Data Pin = Digital Pin 5
Neopixel GND = GND

Seperate 5V power supply provided to Neopixel LED 
**It work by just power from Arduino Uno, at least mine works with 300 Leds so for testing on estrip is enough
for more strips You'll need external 5V power Supply

Single button is clicked multiple time sto change pattern, the code is written in a way where 
the current running pattern is interrupted to change it into new pattern. There are in all 34 Pattern 

Further Development is on going to combine Adafruit Neopixel and FastL:ed libraries into one and add better pattern and 
add hardware upgrade
