# Flight Controller

![Untitled](https://github.com/user-attachments/assets/ed957ba2-66d4-4fec-a814-4ab70ba61eb2)


## Overview
This repository contains the firmware and hardware design files for a custom flight controller designed for multicopters. The board is built around the **STM32F722RET6** microcontroller, equipped with precise sensors and convenient connectivity options to ensure stable and reliable flight performance.

## Features
- **Microcontroller:** STM32F722RET6
- **Gyroscope:** MPU6000
- **Barometer:** BMP384
- **Connectors:**
  - **UART (JST)** for GPS module
  - **I2C (JST)** for additional peripherals (e.g., compass, external sensors)
  - **PWM (JST)** for motor ESC connections
