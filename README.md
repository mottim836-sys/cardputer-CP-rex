# cardputer-CP-rex

Custom PCB and housing design for the **M5Stack Cardputer ADV**.

This board enhances the capabilities of the M5Stack Cardputer for network auditing, RFID cloning, and monitoring 433 MHz / 2.4 GHz frequencies.

## Features
* **Network Auditing:** Advanced tools for testing Wi-Fi security.
* **RFID Support:** Capability to read and copy access keys.
* **Radio Monitoring:** Support for 433 MHz and 2.4 GHz bands.

## Hardware Requirements
To assemble this project, you will need:
* **Base:** M5Stack Cardputer ADV [Aliexpress](https://www.aliexpress.com/item/1005009896470580.html?spm=a2g0o.order_list.order_list_main.5.32bb1802YxDRel)
* **Capacitors:** 2x 50-100uF 0805, 1x 10uF 0805
* **Resistor:** 1x 1kΩ
* **Stabilizer:** 1x AMS1117-3.3
* **LED:** 1x YL-ED0805YG
* **Switch:** 1x dip*5

## Modules
* **PN532**-rfid Aliexpress
* **cc1101**-433Mhz Aliexpress
* **nrf24**-2.4Ghz Aliexpress
* **W5500**-LAN Aliexpress

## Board Layout
![PCB Design](view/pcb.jpg)

> **Current Status (v2.2):** We are currently optimizing power tracks, fixing minor short circuits, and polishing the final layout.
