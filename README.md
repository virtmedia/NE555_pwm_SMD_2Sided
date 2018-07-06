# NE555_pwm_SMD_2Sided
Smallest version of NE555 PWM generator. Designed to make at home.

Here is 2-sided version of [this](https://github.com/virtmedia/NE555_pwm_SMD) project.

## Description
Simple, small and cheap PWM regulator on NE555.
You can use it to drive 12V motor, LED strip, Peltier module, lightbulb etc.
PCB dimensions: 16.18 x 18.42 mm. 
Pulse width regulated by standard potentiometer.
You can use any Mosfet in DPAK (TO-252) case as You like and follow your requirements. I am using 2SK3918 from old pc motherboard.

If you want to make it, just download the pdf files , print it and make thermotransfer.
All SMD resistors and capacitors (except C2 on power input, with is 1206, so you can use higher capacity) are in 0603 cases.
You have to make connection between two layers of copper where the vias are.

Supply Voltage: 4.5 - 16V
Current consumption: about 20mA with no load
Output current: depending of used mosfet, limited by traces width - you can reinforce it with wire for more current.
PWM frequency: about 1KHz for the parts values as in schematic. You can adjust them, just keep the conciderations in NE555 datasheet.

Note that due to the construction, there is no full 0-100% regulation. The output goes to the almost 100%, but the bottom limit is a little bit above 0%. 

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
