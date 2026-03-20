# Two-Stage-CMOS-Op-Amp-GPDK90-
Two Stage CMOS Op-Amp simulation and analysis in Cadence Virtuoso IC 6.1.7 , this is a basic operational amplifier with a basic differential amplifier , a CMOS output stage , a basic current mirror and Miler Compensation .
The Op-Amp meets the following specifications : 
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
