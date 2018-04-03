# Micro Soldering Station

*The cheapest Micro soldering Station ever*

![BOX](https://github.com/peekpt/MicroSolderingStation/raw/master/media/DSCF9575.JPG)

![BOX](https://github.com/peekpt/MicroSolderingStation/raw/master/media/box.png)

## Features

- Cheap & easy build under 10$
- Temperature controled (PID)
- Micro soldering tip
- Serial command interface
- Ploter (outputs usefull data)
- User Interface
- Open Source Arduino based
- Firmware Updates
- 3D Printed Case
- In use, pickup detection (by temperature sensing)

## Materials

- 1x Arduino Uno
- 1x Nokia LCD Module
- 1x USB Soldering Iron
- 1x Thermistor 100k 3950
- 1x 4 wire wire cable(usb cable works)
- 1x 5mm Led
- 2x 1k resistor
- 1x 4,7k resitor
- 1x 10n Capacitor
- Kapton tape 10-20mm
- 1x N MosFet (or use the Iron's pcb one)
- 1x rocker switch
- 10 x small screws 2.5x5mm large head

## Schematic

![Schematic](https://github.com/peekpt/MicroSolderingStation/raw/master/media/Schematic_MicroSolderingStation.png)



## Soldering Tip Diagram
![Diagram](https://github.com/peekpt/MicroSolderingStation/raw/master/media/soldering%20tip.png)

## UNO R3 CH340 Power Hack
![BOX](https://github.com/peekpt/MicroSolderingStation/raw/master/media/UNO%20CH340%20hack.jpg)

_Cut Power the trace underneath the PCB and connect a rocker switch in series._

## Fritzing
![Fritzing](https://github.com/peekpt/MicroSolderingStation/raw/master/media/fritzing_bb.png)

Remove the pcb from the soldering iron and grab a cable with 4 wires (2 for thermistor, 2 for the heater).
Poke an hole in the side of the iron's case, near the yellow nut, to pass the 2 wires and solder them to the thermistor.
Use kapton tape to isolate the thermistor pins and to fix the thermistor's glass tip to the iron end with some kapton turns.
The other 2 wires connect to the heater and the led with a resistor in series. (watch the polarity of the led)
Remove the ball bearing and connect the led in the hole, break the spring post from the other side of the case.


## User Interface Screenshots
![UNO](https://github.com/peekpt/MicroSolderingStation/raw/master/media/interface_small.png)


## Operation

**main view**

- \< >                   temp up down
- [click]                cycle memories
- [click & hold]         store mem mode
- [double click]         settings mode

**stand by mode**
- [click]                  leave standby mode

**store mem**
- \< >                   select memory to store
- [click]                store

**settings mode submenus**
 - \< >                   navigate submenus
 - [click]                edit submenu

**edit submenu**
- \< >                   change value up down
- [click]                exit submenu



## Parts & Modules

_100k thermistor (3950):_
![](https://github.com/peekpt/MicroSolderingStation/raw/master/media/thermistor_100k_3950.jpg)


_Arduino Uno R3 ch340:_
![](https://github.com/peekpt/MicroSolderingStation/raw/master/media/uno_r3_ch340.jpg)


_Rotary Encoder:_
![](https://github.com/peekpt/MicroSolderingStation/raw/master/media/rotary_encoder.jpg)

_USB Soldering Iron:_
![](https://github.com/peekpt/MicroSolderingStation/raw/master/media/soldering_iron.jpg)

_LCD:_
![](https://github.com/peekpt/MicroSolderingStation/raw/master/media/lcd.jpg)


















