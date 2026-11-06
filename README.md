
# Boardoza ATA2508DA 6-Channel Capacitive Touch Breakout Board

The **Boardoza ATA2508DA Breakout Board** is a capacitive touch input module based on the **ATLab ATA2508DA digital touch controller**. It features six independent touch pads that detect finger contact through changes in capacitance, allowing users to interact with electronic systems without mechanical buttons. 

The board operates with a **3.3V or 5V** power supply and communicates with microcontrollers through an **I²C interface**. It also provides configurable digital I/O pins and a touch interrupt output, allowing integration with Arduino, ESP32, STM32, Raspberry Pi, and other embedded platforms. The board is suitable for **touch-based control panels, home automation, interactive electronics, and embedded user interfaces**.


| Front Side | Back Side |
|:---:|:---:|
| ![Front](./assets/ATA2508DA%20Front.png) | ![Back](./assets/ATA2508DA%20Back.png) |

---

## Key Features

- **6-Channel Capacitive Touch Detection:** Provides six independent touch-sensitive pads for implementing button-free input interfaces.
- **I²C Communication Interface:** Allows touch status and configuration registers to be accessed through a standard two-wire connection.
- **Programmable Touch Sensitivity:** Supports individual sensitivity adjustments for touch channels to accommodate different applications and operating conditions.
- **Automatic Impedance Calibration (AIC):** Helps maintain stable touch detection by compensating for changes in sensor characteristics.
- **Touch Interrupt Output:** Provides a dedicated interrupt signal to notify the host microcontroller when touch status changes.

---

## Technical Specifications

**Model:** ATA2508DA  
**Manufacturer:** Boardoza  
**Manufacturer IC:** ATLab  
**Input Voltage:** 3.3V - 5V  
**Interface:** I²C  
**Functions:** Capacitive Touch Detection  
**Touch Channels:** 6  
**Touch Sensitivity:** Programmable  
**Touch Strength Resolution:** 8-bit  
**Additional Features:** Automatic Impedance Calibration (AIC), Adjacent Pattern Interference Suppression (APIS)  
**Power Management:** Active, Idle, and Sleep Modes  
**Operating Temperature:** -35°C to +90°C     
**Board Dimensions:** 60mm x 60mm

---

## Board Pinout

### ( J1 ) Power, I²C Communication and Digital I/O Pins

| Pin Number | Pin Name | Description |
| :---: | :---: | --- |
| 1 | VCC | Power Supply (3.3V - 5V) |
| 2 | TINT | Touch Interrupt Output, signals changes in touch detection status |
| 3 | SCL | I²C Clock Input from Host Microcontroller |
| 4 | SDA | Bidirectional I²C Data Line |
| 5 | DIO_0 | Configurable Digital I/O, Direct Touch Output, or External Interrupt Input |
| 6 | DIO_8 | Configurable Digital I/O, Direct Touch Output, or External Interrupt Input |
| 7 | GND | Ground Connection |

---

## Board Dimensions

<img src="./assets/ATA2508DA Dimensions.png" alt="ATA2508DA Breakout Board Dimension" width="450"/>

---

## Step Files

[Boardoza ATA2508DA.step](./assets/ATA2508DA%20Step.step)

---

## Sensor Datasheet

[ATA2508DA Datasheet.pdf](./assets/ATA2508DA%20Datasheet.pdf)

---

## Version History

- V1.0.0 - Initial Release

---

## Support

- If you have any questions or need support, please contact <support@boardoza.com>

---

## **License**

This repository contains both hardware and software components:

### **Hardware Design**

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

All hardware design files are licensed under [Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

### **Software/Firmware**

[![BSD-3-Clause][bsd-shield]][bsd]

All software and firmware are licensed under [BSD 3-Clause License][bsd].

[bsd]: https://opensource.org/licenses/BSD-3-Clause
[bsd-shield]: https://img.shields.io/badge/License-BSD%203--Clause-blue.svg

