# Xiaomi M365 Display
<img src="https://github.com/Levi990e/M365-Dashboard/blob/master/pics/dash.png?raw=true" width="200" height="475" />  

Credit & Original code from: https://github.com/augisbud/m365_dashboard 

Modified for my own usage and liking, original uses a Ardunio Mini, but I am using a Arduino Pro Nano for this.

# Products Used
Arduino Pro Nano  
I2C OLED 0.96"  
3d Printed Bracket  
1N4148 Diode  
0.25w 120ohm Resistor  

# Flashing   
These libraries are needed for the code to work, can be installed inside the Arduino IDE 2.   
- SSD1306Ascii by Bill Greiman   
- WatchDog by Nadav Matalon   

# Physical Connections  
<img src="https://github.com/Levi990e/M365-Dashboard/blob/master/pics/diagram.png?raw=true" width="600" height="600" /> 

# Updating M365 firmware / Disabling the Dashboard
Turn on the scooter and immediately engage and hold the throttle and brake before the logo disappears from the dashboard LCD. You will enter on dashboard disabled mode.
The Arduino TX/RX pins will go to hi impedance state leaving the communication BUS free.   

By this way you can update the M365 firmware without disconnecting the dashboard or any cable.   

A new power cycle will reset the dashboard to normal mode.   
