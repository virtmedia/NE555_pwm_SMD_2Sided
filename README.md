# NE555_pwm_SMD_2Sided
Smallest version of NE555 PWM generator. Designed to make at home.

Here is 2-sided version of [this](https://github.com/virtmedia/NE555_pwm_SMD) project.

## Description
Simple, small and cheap PWM regulator on NE555.
You can use it to drive 12V motor, LED strip, Peltier module, lightbulb etc.
PCB dimensions: 34.29 x 20.63 mm. 
Pulse width regulated by standard potentiometer.
You can use any Mosfet in DPAK (TO-252) case as You like and follow Your requirements. I am using 2SK3918 from old pc motherboard.
As soon as possible i make photos and movie to show prototype.

If You want to make it, just download the pdf files , print it and make thermotransfer.
All SMD resistors and capacitors (except C2 on power input, with is 1206, so you can use higher capacity) are in 0603 cases.
You have to make connection between two layers of copper where the vias are.
You can find partlist in bom.txt file.

## Status
  Tested & works well :)
  Files are prepared for the production. Gerber files are generated. The order was received from the jlcpcb:
  
  ![Photo of the PCB](https://raw.githubusercontent.com/virtmedia/NE555_pwm_SMD_2Sided/master/pcb.jpg)
  

## Schematic:

  ![schematic image](https://raw.githubusercontent.com/virtmedia/NE555_pwm_SMD_2Sided/master/schematic.png)

## PCB layout:

  ![PCB layout image](https://raw.githubusercontent.com/virtmedia/NE555_pwm_SMD_2Sided/master/mount.png)
  
## BOM
  
* C1   100n 0603 case
* C2   100n-10u 0805-1206 case
* C3   10n 0603 case 
* D1   LL4148 MINIMELF
* D2   LL4148 MINIMELF                    
* D3   LL4148 MINIMELF              
* IC1  NE555D SO-8
* PR1  10K linear potentiometer
* Q1   Generic MOSFET-N in TO252 (DPAK) case                                 
* R1   1K 0603 case
* R2   47R 0603 case
  
## Future
The project looks finished, i have no plan to change it.
