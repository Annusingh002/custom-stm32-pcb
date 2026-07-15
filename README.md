# custom-stm32-pcb

## Overview

This project is a custom STM32 development board designed using KiCad. The board provides the essential hardware required to program and operate an STM32 microcontroller, making it suitable for embedded systems development and prototyping.

## Features

- Custom schematic designed in KiCad
- 2-layer PCB layout
- STM32 microcontroller
- 3.3 V power supply
- SWD programming interface
- Reset circuit
- Decoupling capacitors
- GPIO expansion headers
- Crystal oscillator 
- Power status LED 

## Software Used

- KiCad

## Hardware Components

| Component | Description |
|----------|-------------|
| STM32 MCU | Main microcontroller |
| Voltage Regulator | 3.3 V supply |
| Crystal Oscillator | System clock (if used) |
| Reset Button | Manual reset |
| SWD Header | Programming and debugging |
| LEDs | Status indication |

## Project Structure

```
custom-stm32-pcb/
│
├── Images/
├── KiCad/
├── Gerber/
├── BOM/
└── README.md
```

## Design Checks

- ERC (Electrical Rules Check) completed
- DRC (Design Rules Check) completed
- Gerber files generated for PCB fabrication

## Learning Outcomes

Through this project, I gained experience in:

- Schematic capture
- PCB layout and routing
- Component placement
- Power supply design
- Embedded hardware design
- Gerber file generation
- PCB design verification using ERC and DRC

## Future Improvements

- USB programming support
- On-board sensors
- Communication interfaces (UART, SPI, I2C)
- Power optimization

## Author

Annu

B.Tech in Electronics and Communication Engineering(AI/ML)
NSUT(DELHI)
