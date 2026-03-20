# Two-Stage-CMOS-Op-Amp-GPDK90-
Two Stage CMOS Op-Amp simulation and analysis in Cadence Virtuoso IC 6.1.7 , this is a basic operational amplifier with a basic differential amplifier , a CMOS output stage , a basic current mirror and Miler Compensation .
The Op-Amp meets the following specifications : 
ICMR(+) = 1.6 V
ICMR(-) = 800 mV
Gain Bandwidth Product = 32.145 M Hz
Gain = 70.7749 dB = 3457.36
Phase Margin = 46.9 °
DC Power = 193.361 μW
Unity Gain Frequency = 35.1013 M Hz a

The Op-Amp was built using mosfets from GPDK090  (90nm PDK) and basic analog devices from basic and analogLib .
The length chosen L = 500nm
The width of the mos devices were then calculated by hand and modified by intuition to prioritise gain and meet a minimum of 45 Degree phase margin .
The schematic and setup to analyse DC and AC parameters :
![schematic with wl](https://github.com/user-attachments/assets/152214cf-786b-4e78-8c7e-351e1c7e1d9a)
The Analog Design Environment Setup used : 
![ADE](https://github.com/user-attachments/assets/91349e8d-55bc-4760-ae7f-311172fdbfab)
AC Gain and Phase Graph

![ac gain phase](https://github.com/user-attachments/assets/b2300a25-9bad-447c-ab4f-52b6f098c3ca)

DC Power Graph 
![Power Graph](https://github.com/user-attachments/assets/c380867b-dcdd-49bf-9c36-b00edd08e30b)
