# cardputer-CP-rex

Custom PCB and housing design for the **M5Stack Cardputer ADV**.

This board enhances the capabilities of the M5Stack Cardputer for network auditing, RFID cloning, and monitoring 433 MHz / 2.4 GHz frequencies.

## Features
* **Network Auditing:** Advanced tools for testing Wi-Fi security.
* **RFID Support:** Capability to read and copy access keys.
* **Radio Monitoring:** Support for 433 MHz and 2.4 GHz bands.

## Hardware Requirements
To assemble this project, you will need:
* **Base:** M5Stack Cardputer ADV
* **Capacitors:** 2x 50-100uF 0805, 1x 10uF 0805
* **Resistor:** 1x 1kΩ
* **Stabilizer:** 1x AMS1117-3.3
* **LED:** YL-ED0805YG

## Modules
* **PN532**-rfid
* **cc1101**-433Mhz
* **nrf24**-2.4Ghz
* **W5500**-LAN

## Board Layout
![PCB Design](view/pcb.jpg)

> **Current Status (v2.2):** We are currently optimizing power tracks, fixing minor short circuits, and polishing the final layout.
