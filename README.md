# CareBridge – Smart Health Companion
### ESP32-S3 Based Wearable Badge and Wristband

## Overview

CareBridge is a wearable health-companion project designed around a smart badge and wristband. The system explores the integration of embedded electronics, environmental sensing and GPS-based location tracking into a compact wearable solution.

The project aims to make essential environmental and location-related information more accessible through a portable, user-friendly device.

## Project Objectives

- Develop a compact wearable badge and wristband system.
- Integrate sensors and microcontrollers for data acquisition.
- Explore environmental monitoring through embedded sensors.
- Incorporate GPS-based location tracking.
- Design a practical hardware system with potential applications in personal safety and health monitoring.

## System Architecture

The project is organised into two wearable components:

### 1. Smart Badge

The badge is designed as the primary electronics unit, incorporating the microcontroller and supporting sensor modules.

Key hardware:
- ESP32-S3 microcontroller
- BME688 environmental sensor
- GPS module for location-related functionality

### 2. Smart Wristband

The wristband is designed as the complementary wearable component of the system.

Its role and electronics integration are part of the overall wearable system design.

## Hardware Components

| Component | Purpose |
|---|---|
| ESP32-S3 | Main microcontroller |
| BME688 | Environmental sensing |
| GPS Module | Location tracking |
| Smart Badge | Wearable electronics unit |
| Wristband | Complementary wearable unit |

## Tools and Technologies

- KiCad – Circuit schematic and PCB design
- ESP32-S3 – Embedded hardware platform
- Embedded C/C++ – Firmware development, where applicable
- Sensor interfacing and hardware integration

## Repository Structure

```text
CareBridge/
│
├── README.md
│
├── KiCad/
│   ├── project.kicad_pro
│   ├── project.kicad_sch
│   └── project.kicad_pcb
│
├── Images/
│   ├── badge-design.png
│   ├── wristband-design.png
│   └── pcb-3d-view.png
│
├── Documentation/
│   └── component-details.md
│
└── Firmware/
    └── source-code/
```

## Design and Development

The development process involves:

1. Identifying the functional requirements of the wearable system.
2. Selecting suitable microcontrollers and sensor modules.
3. Developing circuit schematics using KiCad.
4. Designing the PCB layout and organising component placement.
5. Exploring integration between the badge and wristband.
6. Developing and testing the embedded system.

## Current Project Status

The project involves the hardware design and development of a smart badge and wristband system. Individual implementation stages, including PCB design, firmware integration and hardware testing, are documented as development progresses.

## Future Scope

- Complete hardware integration of the badge and wristband.
- Expand sensor-based monitoring capabilities.
- Develop communication between wearable components.
- Improve power management and wearable form factor.
- Explore a companion application for displaying collected information.

## My Contribution

Worked on the hardware-oriented development of the wearable health-companion concept, including ESP32-S3 based system design, sensor integration considerations and PCB design using KiCad.

---

*Project: CareBridge – Smart Health Companion*  
*Platform: ESP32-S3 | Design Tool: KiCad*
