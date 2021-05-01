# ESP8266-I2C-LCD1602

Compatible with the latest Arduino IDE
Original Library https://github.com/agnunez/ESP8266-I2C-LCD1602
Modified for ESP8266 with GPIO0-SDA GPIO2-SCL and LCD1602 (16 char x 2 row) display and 
modified to allow configuration through lcd.begin(sda,scl) or other GPIO's used with I2C, or use pointer to TwoWire through lcd.begin(wire)

# Installation #
Create a new folder called "LiquidCrystal_I2C" under the folder named "libraries" in your Arduino sketchbook folder.
Create the folder "libraries" in case it does not exist yet. Place all the files in the "LiquidCrystal_I2C" folder.

# Usage #
To use the library in your own sketch, select it from *Sketch > Import Library*.

-------------------------------------------------------------------------------------------------------------------
This library is based on work done by DFROBOT (www.dfrobot.com).
