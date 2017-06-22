## Arduino Clock
A 4-Digit Seven Segment Clock with Thermometer

### Wiring Connections
Initially I wired connections according to [ecotronics Blog](http://ecotronics.ch.honorius.sui-inter.net/wordpress/2013/multiplexed-4-digit-7-segment-led-display-mit-arduino-ansteuern/).
Seven Segment connections of this project:
a = 6;
b = 7;
c = 8; 
d = 9;
e = 10;
f = 11;
g = 12;
p = A5; // I did not want to use 13 due to built-in led.
d4 = 5;
d3 = 4;
d2 = 3;
d1 = 2;

Thermistor Connection (Thermometer):
Thermistor should be connected with an equal resistor serially from + to - and their junction should be connected as:
ThermistorPin = A3;

Buttons for setting clock:
SetModeButton = A2;
SetHourButton = A0;
SetMinuteButton = A1;


### Additional Libraries
Libraries can be found modified (if needed) or unmodified in this project as "libraries" folder.

This project uses [TimerOne](https://github.com/PaulStoffregen/TimerOne) (Paul Stoffregen - CC BY 3.0 US) and [SevSeg](https://github.com/sparkfun/SevSeg/) (Nathan Seidle - Beerware license).

### Created By
Ozan KARAALİ, 2017

