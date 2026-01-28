# GatePi 6CH - RP2040 Ethernet



A compact Ethernet controller powered by the RP2040, delivering reliable real-time control and network connectivity.
## OVERVIEW 

GatePi 6CH – RP2040 Ethernet is a compact controller powered by the RP2040 microcontroller and equipped with Ethernet connectivity via the WIZnet. It is designed to deliver reliable performance for wired network applications and control systems. The board integrates 6 Channel Relay Unit, RS485 communication,visual status indicators, and an onboard buzzer, making it well suited for PLC-style control systems, building systems, and Ethernet-based gateway projects.

This repository provides getting started instructions, firmware examples, and configuration details for the GatePi 6CH RP2040 Ethernet board.

## Features 
  * **Powered by RP2040 microcontroller**
      * Dual-core ARM Cortex-M0+ for reliable real-time control
  * **Ethernet Connectivity via WIZnet W5100S**
      * Stable wired network communication
      * SPI-based Ethernet controller
  * **6-Channel Relay Unit**
      * Supports NO / COM / NC connections
      * Suitable for AC/DC load control
  * **RS485 Interface**
      * Industrial-grade communication for sensors, meters, and PLC devices
  * **Onboard Buzzer**
      * Audible alerts for events and fault indication
  * **Power Management**
      * XL1509-5.0 (C2902368) DC-DC buck converter
      * Efficient and stable 5V power supply
   
  * **External Power Input**
      * Input  power connection
   
  * **USB Programming Support**
      * Boot button for RP2040 programming
   
  *  **RGB LED**



## Hardware Overview
### Pinout


## Interfacing details

Following GPIOs of RP2040 interfaced with onboard hardware components,

 | RP2040 | Hardware | Function |
 |--------|----------|----------|
 |  GPI0/TXD0 | RS485_RX | UART Communication interface |
  |  GPI0/RXD1 | RS485_TX | UART Communication interface |
   |  GPIO24 | Relay1 | Relay interface |
   |  GPIO25 | Relay2 | Relay interface |
   |  GPIO26 | Relay3 | Relay interface |
   |  GPIO27 | Relay4 | Relay interface |
   |  GPIO28 | Relay5 | Relay interface |
   |  GPIO22 | Relay6 | Relay interface |
   |  GPIO16 ETH_MISO  | WiZnet_MISO |SPI Communication interface |
   |  GPIO19 ETH_MOSI | WiZnet_MOSI| SPI Communication interface |
   | GPIO18 ETH_SCK  | WiZnet_SCK | SPI Communication interface |
   |  GPIO17 ETH_CSn  | WiZnet_CSn | SPI Communication interface |
   | GPIO4 | RGB_LED | RGB LED  |
   |  GPIO2 | BUZZER  | Audible alerts |

   ## Getting Started with GatePi LoRaWAN 4CH/8CH
   
   ### Step 1: Boot Firmware installation 
  Download the first firmware from
[Here](firmware.uf2)

 ### Step 1: Connect Board With PC/Laptop
 Press and hold onboard BOOT button and plug dongle into the USB port of your PC/Laptop. Release the BOOT button once dongle is connected to system. Also, make sure jumper setting as shown below,

                                      














