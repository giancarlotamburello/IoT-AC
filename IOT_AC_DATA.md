# IoT-AC: Internet of Things - Accumulation Chamber

This project provides the documentation and source files to build a low-cost, IoT-based accumulation chamber (**IoT-AC**) for measuring diffuse $CO_2$ fluxes.

## Overview

The **IoT-AC** is designed for environmental monitoring, with a focus on soil and volcanic degassing. The system leverages an ESP32 microcontroller to manage gas sensing and internal air homogenization, offering a portable, cost-effective alternative to professional scientific instrumentation.

## Hardware Components

### Electronics

- **Microcontroller:** [ESP32](https://www.espressif.com/en/products/socs/esp32) (Dual-core, Wi-Fi/Bluetooth enabled).
- **CO2 Sensor:** [Sensirion SCD30](https://sensirion.com/products/catalog/SCD30) – A high-precision NDIR (Non-Dispersive Infrared) module.
- **Fan Motor:** Parallax Inc. bidirectional continuous rotation servomotor (0-50 RPM, 4.6 V).

### Chamber Specifications
