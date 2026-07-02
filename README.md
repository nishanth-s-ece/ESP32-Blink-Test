# ESP32 Environment Verification & Hardware Test

This repository documents the foundational setup of my ESP32 development ecosystem, confirming local compiler toolchains, serial communication via UART (COM5), and digital output execution.

## 🚀 Hardware Proof (Onboard Blue LED)

<video src="WhatsApp Video 2026-07-02 at 10.58.51 PM.mp4" controls width="100%"></video>

## 💻 Software Configuration
* **IDE:** Arduino IDE 2.3.10
* **Target Board:** ESP32 Dev Module
* **Connection Interface:** Silicon Labs CP210x / WCH CH340 Serial Bridge

### Arduino IDE Workspace Setup:
![IDE Setup](WhatsApp Image 2026-07-02 at 10.59.45 PM.jpg)

## 🔌 Pin Mapping
| Peripheral | Target Pin | Configuration |
|---|---|---|
| Onboard LED | GPIO 2 | OUTPUT |
