**# ProdTrack Touch**

An intelligent production tracking terminal combining RFID identification, a touchscreen interface, and on-device TinyML.

## Overview

ProdTrack Touch is a custom ESP32-based PCB designed for real-time production tracking and direct communication with operators. It captures workstation activity and delivers notifications, work requests, and instructions directly to the touchscreen, reducing waiting time and dependence on verbal coordination.

## Key Features

- **Real-Time Production Tracking:** Records production events and operator updates to monitor workstation progress.
- **RFID Identification:** Identifies tagged items or operators within the production workflow.
- **Touchscreen Interface:** Displays instructions and production information while allowing operators to enter updates.
- **Live Notifications & Work Orders:** Receives work requests, instructions, and notifications directly from the connected system in real time.
- **On-Device TinyML:** Runs lightweight machine learning models locally, with functions determined by the deployed model and firmware.
- **Integrated Hardware:** Combines processing, power management, and peripheral interfaces on a custom PCB designed in KiCad.

## Operating Workflow

1. Scan an RFID tag to identify an item or operator.
2. Receive work orders and notifications directly at the workstation.
3. View instructions and enter production updates through the touchscreen.
4. Report production events to the monitoring system.
5. Process local inputs using the deployed TinyML model.

## Purpose

Connect production monitoring with workstation activity, accelerate the delivery of instructions, and reduce delays caused by manual information relays.

## Available Files

The electronic schematic is publicly available in this repository.

Additional engineering files are available upon request, including:

- PCB design and layout
- Component libraries and 3D models
- Bill of Materials (BOM)
- Gerber and manufacturing files
- Additional technical documentation

## Contact

For hardware engineering services, technical collaboration, or requests for additional design files, feel free to contact me via [LinkedIn: Youness TAIK](https://www.linkedin.com/in/youness-taik-434166200/) or [Email: younesstaik0@gmail.com](mailto:younesstaik0@gmail.com).
