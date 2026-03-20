> Two-Stage-CMOS-Op-Amp-GPDK090-
<img width="1823" height="893" alt="image" src="https://github.com/user-attachments/assets/d526325c-6a6c-4a1a-b6d0-3225beb8b11d" /># 
Two Stage CMOS Op-Amp simulation and analysis in Cadence Virtuoso IC 6.1.7 , this is a basic operational amplifier with a basic differential amplifier , a CMOS output stage , a basic current mirror and Miler Compensation .
The Op-Amp meets the following specifications : 
ICMR(+) = 1.6 V
ICMR(-) = 800 mV
Bias Current Ibias = 30 μA
Gain Bandwidth Product = 32.145 M Hz
Gain = 70.7749 dB = 3457.36
Phase Margin = 46.9 °
DC Power = 193.361 μW
Unity Gain Frequency = 35.1013 M Hz a
Input Offset Voltage = 34.01μV

The Op-Amp was built using mosfets from GPDK090  (90nm PDK) and basic analog devices from basic and analogLib .
The length chosen L = 500nm
The width of the mos devices were then calculated by hand and modified by intuition to prioritise gain and meet a minimum of 45 Degree phase margin .
The schematic and setup to analyse DC and AC parameters :

![schematic with wl](https://github.com/user-attachments/assets/152214cf-786b-4e78-8c7e-351e1c7e1d9a)

The Analog Design Environment Setup used : 

![ADE](https://github.com/user-attachments/assets/91349e8d-55bc-4760-ae7f-311172fdbfab)

AC Gain and Phase Graph:


![ac gain phase](https://github.com/user-attachments/assets/b2300a25-9bad-447c-ab4f-52b6f098c3ca)

DC Power Graph :

![Power Graph](https://github.com/user-attachments/assets/c380867b-dcdd-49bf-9c36-b00edd08e30b)

Schematic with annotated DC Operating Points 
![schematic with operating points](https://github.com/user-attachments/assets/c841fb29-dc73-4dd3-88cc-8ddb3bf530bb)

Calculated Slew Rate :

![slewrate](https://github.com/user-attachments/assets/d1acd1a1-2f06-4add-90df-57200381a58c)

Schematic Modified for Symbol Representation :

![schematic for symbol 1](https://github.com/user-attachments/assets/e3ed8c97-29c6-4460-99c0-c3fa1e2f5867)

Power Supply Rejection Ratio Calculation Setup Schematic , ADE and Values:

![psrr setup](https://github.com/user-attachments/assets/fed8bb42-d5f9-4cd3-9328-71d3fe03d2a7)
![psrr ade](https://github.com/user-attachments/assets/0579426b-b4f3-4bbc-8305-d9e070874cdc)
![psrr GRAPH](https://github.com/user-attachments/assets/cfd914a8-9da6-4a5f-bf10-5bb3bb6689cb)

Common Mode Rejection Ratio Calculation Schematic Setup , ADE and Values:


![cmrr setup](https://github.com/user-attachments/assets/a5094f7d-1184-442d-ad9d-c47ae4770a45)

![cmrr ade](https://github.com/user-attachments/assets/19206b68-703c-4bbf-a3fd-4da1ba331642)

Input Offset Voltage Graph:

![input offset ](https://github.com/user-attachments/assets/592be063-1cbb-4090-9b1a-4654053d6be1)



