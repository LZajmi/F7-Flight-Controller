# Flight Controller

## Overview
This repository contains the firmware and hardware design files for a custom flight controller designed for multicopters. The board is built around the **STM32F722RET6** microcontroller, equipped with precise sensors and convenient connectivity options to ensure stable and reliable flight performance.

## Images
![Untitled](https://github.com/user-attachments/assets/53cddce3-8b0f-43a2-a9cb-2b8fdd684c42)

## Features
- **Microcontroller:** STM32F722RET6
- **Gyroscope:** MPU6000
- **Barometer:** BMP384
- **Connectors:**
  - **UART (JST)** for GPS module
  - **I2C (JST)** for additional peripherals (e.g., compass, external sensors)
  - **PWM (JST)** for motor ESC connections
  - **USB C**

## Hardware Design
- The hardware design is created using **Altium Designer**.
- Design files include schematics, PCB layout, and component libraries.
- The design features a 4-layer PCB stack-up to reduce electromagnetic interference and ensure clean signals for sensors and peripherals.

## License
This project is licensed under the **Apache License 2.0**. You may obtain a copy of the License at:

