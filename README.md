# STM32 KiCad Weather Station

KiCad-based PCB project for an STM32-powered IoT weather station with environmental sensing, real-time clock support, battery charging, and e-paper display connectivity.

> 3D render:
<img width="943" height="813" alt="image" src="https://github.com/user-attachments/assets/db9741dc-e883-4119-b716-20bb4c4afeab" />

## Overview

This project is a custom two-layer PCB designed in KiCad for a compact embedded weather station.  
The board is built around the **STM32F103C8T6** microcontroller and integrates power management, sensing, display, and timekeeping components into a single design.

The main goal of the project was to practice the complete PCB design workflow: schematic capture, component selection, board layout, and preparation of production files.

## Main features

- STM32F103C8T6 microcontroller
- BME280 environmental sensor
- DS3231S real-time clock
- E-paper display connector
- TP4056 Li-ion battery charging circuit
- AMS1117-3.3 voltage regulator
- USB-C power input
- 5 control buttons
- Status LEDs

## Hardware components

### Core components
- **U1** — STM32F103C8T6
- **U2** — BME280
- **U3** — TP4056
- **U4** — AMS1117-3.3
- **U5** — DS3231S

### Connectors and interfaces
- **P1** — USB_C_Plug
- **J1** — Battery
- **J2** — Prog
- **J3** — E-Paper_Display

### User interface
- **SW1–SW5** — buttons
- **D1** — Blue LED
- **D2** — Green LED
- **D3** — Red LED

## Design files

> Schematic:
<img width="3507" height="2480" alt="image" src="https://github.com/user-attachments/assets/7e92ec83-d099-4381-915f-93ba4d51dd94" />

> PCB layout:
<img width="784" height="868" alt="image" src="https://github.com/user-attachments/assets/b293526b-c636-4d77-a4ef-50f1edae9d7c" />

## Notes

This repository focuses mainly on the PCB design itself rather than firmware implementation.  
The project includes the main design files, screenshots, and fabrication outputs for documentation purposes.

## Tools used

- **KiCad** for schematic and PCB design
- Optional 3D viewer/export from KiCad for board rendering

## Author

**Vladyslav Kyshchun**
