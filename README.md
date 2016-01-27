# 15 Port USB Power Supply using an ATX Power Supply

## Problem Statement
I’m continuously using all of my wall outlets to plug-in a USB wall wart power supply to use for all of my development boards (e.g. Raspberry Pi, Arduino, etc).  Over time I needed two 6 port power strips just to have enough outlets for the USB wall wart.  To address this issue, I designed a very simple 15 Power USB power supply using an ATX Power Supply.

## Introduction
This design is a passive USB power supply, meaning this design directly connects the ATX Power Supply +5DCV directly to the +5DCV pin of a USB connector.  I was considering adding a USB charging port controller and current limiting power switch such as the [TSP2511](http://www.ti.com/product/TPS2511).  But I wanted to keep this design simple.

## Parts List
| Name          | Description          | Distrubutor | Price | URL                                                                                                       |
|---------------|----------------------|-------------|-------|-----------------------------------------------------------------------------------------------------------|
| USB Connector | 3 Stack USB          | Mouser      | $4.24 | [Link](http://www.mouser.com/Search/ProductDetail.aspx?R=33UBAR-TSN1Rvirtualkey63110000virtualkey706-33UBAR-TSN1) |
| Binding Post  | For the power supply | Sparkfun    | $0.35 | [Link](https://www.sparkfun.com/products/9739)                                                                    |
| Fuse Holder   | Fuse Clip 5mm        | Sparkfun    | $0.25 | [Link](https://www.sparkfun.com/products/9773)                                                                    |
| PCB           | 15 Port USB          | DirtyPCBs   | $25   | [Link](https://dirtypcbs.com)                                                                                     |


## Assembly

PCB Layout Design
![PCB](http://odelayio.github.io/atx_power/images/pcb.jpg)

I had an old ATX Power Supply, so I just used this one.  This ATX Power Supply cost around $15 on Amazon.com
![Step 1](http://odelayio.github.io/atx_power/images/1.jpg)

This is the ATX Power Supply with the cover off.  As you can see, there is room in this ATX Power Supply to fit the PCB.
![Step 2](http://odelayio.github.io/atx_power/images/2.jpg)

This design doesn't use an ATX connect to save money on the BOM. So I trimmed the wires to the desired length.
![Step 3](http://odelayio.github.io/atx_power/images/3.jpg)

Solder the ATX wires to the designated power rail of the PCB.  The voltage is labeled on the silkscreen.
![Step 4](http://odelayio.github.io/atx_power/images/4.jpg)

Modified the ATX Power Supply, so the PCB can be mounted
![Step 5](http://odelayio.github.io/atx_power/images/5.jpg)

Fully assembled 15 Port USB Power Supply.  
![Step 6](http://odelayio.github.io/atx_power/images/6.jpg)

