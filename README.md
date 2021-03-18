# zstick2538
USB dongle, that can be used as Zigbee Coordinator in home automation hubs like Home Assistant, ioBroker, OpenHab ect.<p>
Fully compatible with [zigbee2mqtt](https://www.zigbee2mqtt.io/). 

## PCB
Based on [Zigbee Stick v3.1](https://easyeda.com/mercenaruss/zigbee-stick-v3). <p>
I edited it a little so that most of the components of PCB are placed on one side. When ordering at JLCPCB with SMT assembly service, only CC2538+CC2592 breakout board, USB-A connector, programming header and SMA connector has to be soldered manually.
<p>
You can find my project on [EasyEDA here](https://easyeda.com/mmodestas/mm_zigbee_stick_v3-1_copy).

## Case
I designed 3D printed case. Printing with PET-G. Sanding and painting with black matte paint is used for post-processing.
[1551USB3CLR](https://www.hammfg.com/part/1551USB3CLR) case could be used. However, I did not try it.

## Firmware
Zstack 3.0.x <p>
[Coordinator](https://github.com/jethome-ru/zigbee-firmware/tree/master/ti/coordinator/cc2538_cc2592) <p>
[Router](https://github.com/jethome-ru/zigbee-firmware/tree/master/ti/router/cc2538_cc2592) <p>

