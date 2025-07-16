# ESP32-C6 USB Dongle

> Compact | Plug & Play | Zigbee | Thread | Matter | BLE | Wi-Fi 6

<img width="913" height="558" alt="Pinout_Diagram" src="https://github.com/user-attachments/assets/8153af29-605f-4f7a-9a87-2fd62890142f" />

## Overview

The **ESP32-C6 USB Dongle** is a compact and powerful development board designed for wireless experimentation and prototyping. Powered by the ESP32-C6-MINI-1-N4 module, it supports the full range of wireless protocols including **Wi-Fi 6**, **Bluetooth 5 LE**, **Zigbee**, and **Thread (802.15.4)**.

It plugs directly into any USB-A port, making it an ideal tool for developers, testers, and tinkerers. Whether you’re building a **Zigbee coordinator**, a **Thread border router**, or experimenting with **Matter** over Thread or Wi-Fi, this dongle has you covered.

## Key Features

* **ESP32-C6-MINI-1-N4** SoC (RISC-V, single-core @ 160 MHz)
* **4 MB Flash**, on-board PCB antenna
* Native **USB 2.0 full-speed** for power, serial, and JTAG
* Compact **USB-A plug** form factor
* **MP28164 3.3V regulator** (ultra-low quiescent current)
* **Reset** and **Boot** buttons for development
* **WS2812B-2020 RGB LED** for visual status and feedback
* **Ultra-low power operation** support (deep sleep)

## Getting Started

1. Plug the dongle into any USB-A port (PC, Raspberry Pi, powered hub)
2. Program it via ESP-IDF or Arduino using the native USB interface
3. Use it as:

   * Zigbee or Thread device
   * Coordinator for Zigbee2MQTT
   * Matter test device or border router
## Video

[![Click for video description](https://img.youtube.com/vi/IeBuSCYYrvg/0.jpg)](https://www.youtube.com/watch?v=IeBuSCYYrvg)


## Raspberry Pi Integration

You can connect multiple dongles to a **Raspberry Pi** for home automation or mesh network testing:

![IMG_3595](https://github.com/user-attachments/assets/1204375f-2c75-4c23-9901-5fc64c5ec443)


Use cases:

* **Zigbee Coordinator + Zigbee End Device**
* Thread border router setup with **Home Assistant**
* Wi-Fi ↔ Zigbee ↔ Thread bridging

## Example Projects (coming soon..)

* Zigbee2MQTT with native ESP32-C6
* ESP-Thread Border Router
* BLE OTA provisioning
* Matter over Thread endpoint

## Open Hardware (coming soon..)

This project is open-source:

* Hardware design (KiCad): `/hardware`
* Firmware examples (ESP-IDF, Arduino): `/firmware`
* Documentation and usage examples: `/docs`

Contributions and forks are welcome!

## License

* Firmware & Docs: **MIT License**

---

## 📦 Repository Structure

```bash
├── docs/            # User guides, usage examples
├── firmware/        # Sample firmware (Zigbee, Thread, Matter)
├── hardware/        # KiCad project files, schematics, 3D
├── images/          # Rendered photos and labeled diagrams
├── LICENSE
└── README.md        # This file
```
---

For full details, see [Crowd Supply product page](#) *(coming soon!)*.

---
