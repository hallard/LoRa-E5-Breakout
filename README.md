LoRa-E5 breakout board
======================

<img src="https://github.com/hallard/LoRa-E5-Breakout/blob/main/pictures/LoRa-E5-Breakout-top.png">

Mainly based on [LoRa-E5 mini](https://www.seeedstudio.com/LoRa-E5-mini-STM32WLE5JC-p-4869.html) board from Seedstudio, but since it was out of stock and I needed some specific wiring, I designed my own based on the Open Source design they made (thank for sharing)

I'm using mainly to flash custom firmware in it, and not using AT default firmware.

**These boards have been received, assembled, and works as expected**

- LoRa-E5 Module
- No USB/Serial, SMD FTDI 6 pins connector (**use 3.3V FTDI One, not 5V**)
- Exposed JTAG pins needed to flash module (PA13-SWDIO / PA14-SWCLK / RESET)
- Green Led on PB10
- Red Led on PB5
- Optional 2 Tactile Switch (boot and reset)
- 2 Antenna connector (u-Fl and SMA), select with 0 Ohm resistor
- I2C 4 pins location for "classic" sensors

Detailed Description
====================

No specific documentation for now, it's just a kind of wiring helper as schematic


Schematic
=========

<img src="https://github.com/hallard/LoRa-E5-Breakout/blob/main/pictures/LoRa-E5-Breakout-sch.png">

Boards 
======

~~You can order PCBs of this board at [PCBs.io][3]~~

- ~~[V1.0](https://PCBs.io/share/zM5GG)~~

 ~~PCBs.io give me some reward when you order my designed boards from their site. This is pretty good, because I can use these rewards to create and design new boards and order boards for a discounted price, so if you don't care about PCB manufacturer please use PCBs.io.~~

Looks like PCBs.io is gone, I do not have any rewards from PCBs.io since August 2020 and my free order placed after are still not received, so my guess they are not on business anymore.

So you can order the board on [oshpark](https://oshpark.com). 

- [V1.0](https://oshpark.com/shared_projects/pMgmywYX) 

It's a pitty after several discuss with OSHPark that I can't have any rewards for each people ordering my boards, this would allow me to order free PCB for shared projects and create new ones. For information my shared boards generated a total of **$285 162.00** orders at PCBs.io in 4 years, not bad at all :-)

Hoping one day OSHparks will thanks me giving them this market. 

Assembled boards
================

**Top & bottom side V1.0**

<img src="https://github.com/hallard/LoRa-E5-Breakout/blob/main/pictures/LoRa-E5-Breakout-top.png">
<img src="https://github.com/hallard/LoRa-E5-Breakout/blob/main/pictures/LoRa-E5-Breakout-bot.png">

Bill Of Material
================

Nothing fancy, all components are 0805 and/or PTH and can be ordered almost anywhere (digikey, mouser, radiospare, ...). 
use only what you need dependings on what you want to do. 

Check Seeed format [BOM](https://github.com/hallard/LoRa-E5-Breakout/blob/main/LoRa-E5-Breakout-BOM.xlsx) File, check on [Seeed OPL](https://www.seeedstudio.com/opl.html) for manufacturer SKU match.

License
=======

<img alt="Creative Commons Attribution-NonCommercial 4.0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png">   

Licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](http://creativecommons.org/licenses/by-nc/4.0/)    


 
