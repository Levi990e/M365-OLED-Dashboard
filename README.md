# Xiaomi M365 Display
<img src="https://cdn.discordapp.com/attachments/1082291382305169510/1168512901280186468/IMG_20231030_122312.jpg" width="200" height="475" />  
Credit & Original code from: https://github.com/augisbud/m365_dashboard  
Modified for my own usage and liking, original uses a Ardunio Mini, but I could never get that to work.  

# Products Used
Arduino Pro Micro  
I2C OLED 0.96" or 1.3" Screen  
3d Printed Bracket  
1N4148 Diode  
0.25w 120ohm Resistor  

# Flashing   
These libraries are needed for the code to work, can be installed inside the Arduino IDE 2.   
- SSD1306Ascii by Bill Greiman   
- WatchDog by Nadav Matalon   

# Physical Connections  
<img src="https://raw.githubusercontent.com/Levi990e/M365-Dashboard/master/pics/diagram.png?token=GHSAT0AAAAAACJEMPG5T6RCCQSDH5CJ2QNIZKA2HAA" width="600" height="600" /> 

# Updating M365 firmware / Disabling the Dashboard
Turn on the scooter and immediately engage and hold the throttle and brake before the logo disappears from the dashboard LCD. You will enter on dashboard disabled mode.
The Arduino TX/RX pins will go to hi impedance state leaving the communication BUS free.   

By this way you can update de M365 firmware without disconnecting the dashboard or any cable.   

A new power cycle will reset the dashboard to normal mode.   

# UI
WIP