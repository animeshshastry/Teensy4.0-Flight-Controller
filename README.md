# Teensy4.0-Flight-Controller
PCB Design files for the Teensy 4.0 flight controller. Designed with EasyEDA.
The 2-layer PCB measures 37 × 36 mm and has the standardized 30.5 x 30.5 mm M3 mounting holes with JST-SH connectors. It features multiple IMU options and power via USB or external 7-30V battery.
<p float="left">
  <img src="https://github.com/animeshshastry/Teensy4.0-Flight-Controller/blob/main/Images/Front.svg?sanitize=true" width="400" height="400">
  <img src="https://github.com/animeshshastry/Teensy4.0-Flight-Controller/blob/main/Images/Back.svg?sanitize=true" width="400" height="400">
</p>

In addition to the PCB You'll need the following components to complete the flight controller
1. Teensy 4.0 ( make it castellated by manually sanding or grinding the edges with dremel or tool of your choice )
2. ICM-20948 and/or ICM-42688 ( QFN packages are hard to find and so you might have to take it out of breakout boards )
3. Three 0.1 uF 0402 SMD capacitors
4. Two 10k Ω and two 4.7k Ω 0402 SMD Resistors
5. Four JST-SH female 4-pin connectors ( Female Qwiic connectors will work )
6. (Optional) Polulu 5V, 600mA Step-Down Voltage Regulator D36V6F5 ( if you wish to use external power from 7-30V battery )
7. (Optional) NW-MOT-ICM42686P IMU breakout board for another IMU ( make it castellated similar to teensy )
8. (Optional) One to four 0402 LEDs
