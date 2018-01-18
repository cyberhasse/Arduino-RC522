# Arduino-RC522-I2C_LCD
My personal door opening mechanism.
Some phrases are in swedish.
Changed so that it works with my I2C LCD,
and added a button function for opening door-lock,
with esp8266 from anywhere in the world.

Added this under void setup()

// This makes the LCD display work with longer wires but some of my nanos v3 show strange behaviour


Wire.begin ();
TWBR = 152;


// In the case of I2C make sure you have pull-up resistors on SDA and SCL in order to get a clean signal.
// 4.7 k is a reasonable value to try (for both of them) with the other ends connected to +5 V
// I didn't need to do that.. time will tell :)

Note!
This is just for storing my stuff and not really a project :)
Code is originally from:
https://github.com/omersiar/RFID522-Door-Unlock

