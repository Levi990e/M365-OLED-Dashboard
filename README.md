# Xiaomi M365 Display
<img src="https://cdn.discordapp.com/attachments/1082291382305169510/1168512901280186468/IMG_20231030_122312.jpg" width="200" height="264" />
Original code from: https://github.com/augisbud/m365_dashboard
Modified for my own usage and liking, original uses a Ardunio Mini, but I could never get that to work.

# Products Used
Arduino Pro Micro
I2C OLED 0.96" or 1.3" Screen
3d Printed Bracket
1N4148 Diode
0.25w 120ohm Resistor

Knowing the price is around 20$ you can get the Xiaomi M365 Pro top panel from aliexpress for around the same price and a better look, unless you need additional features just go for the pro display.

# Flashing   
Please install the libraries I provided in the files, install them to you arduino library folder, usually              
  C:\Users\\%username%\Documents\Arduino\libraries  
I'd recommend you to use Arduino 1.6.6  
https://www.arduino.cc/en/Main/OldSoftwareReleases  

# Physical Connections  
WIP

# Updating M365 firmware / Disabling the Dashboard
Turn on the scooter and immediately engage and hold the throttle and brake before the logo disappears from the dashboard LCD. You will enter on dashboard disabled mode.
The Arduino TX/RX pins will go to hi impedance state leaving the communication BUS free.

By this way you can update de M365 firmware without disconnecting the dashboard or any cable.

A new power cycle will reset the dashboard to normal mode.

# Known Issues  
Sometimes the Arduino Freezes, a watchdog is in place but doesn't always trigger.  

# Screen caps
# Soldering, soldered directly to the cable coming from the MCU
5V To Red    
GND To Black  
BUS To Yellow  

# UI
WIP