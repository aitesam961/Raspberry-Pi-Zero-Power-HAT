# Raspberry Pi Zero Power HAT

A compact power accessory board designed for Raspberry Pi Zero, Zero W, and Zero 2 models. This HAT combines a single-cell Li-ion/LiPo battery power path, USB-C charging, a 5 V boost regulator, and a power switch in a small footprint intended to fit the Raspberry Pi Zero form factor.

The project includes schematic, PCB, mechanical, and manufacturing files so the board can be reviewed, modified, fabricated, or reproduced.

## Features

- 5 V regulated power output for the Raspberry Pi GPIO header
- USB-C charging input
- Single-cell Li-ion/LiPo battery compatibility (3.7 V nominal)
- On-board boost regulator for battery-to-5 V conversion
- Power switch for on/off control
- Compact board size intended for Raspberry Pi Zero-class boards
- Manufacturing data included for PCB fabrication and assembly

## Supported hardware

This board is intended for:

- Raspberry Pi Zero
- Raspberry Pi Zero W
- Raspberry Pi Zero 2 W

## Hardware overview

The board is a power supply accessory that lets a Raspberry Pi run from a battery while still supporting charging through USB-C. In practical use, the board acts as a small UPS-like power stage for the Pi, making it useful for portable and field projects.

Key design characteristics from the project notes:

- Board size: approximately 65 mm × 30 mm
- 2 signal layers
- 24 components
- 4 mounting holes for M2.5 screws
- USB-C charging port and 3.7 V Li-ion compatible power path
- Up to ~3.8 A peak current draw capability in the design notes

## Repository layout

- [CAD Source Files](CAD%20Source%20Files) — source design files and schematic PDF
- [MCAD Files](MCAD%20Files) — mechanical CAD output and DXF data
- [Manufacturing Files](Manufacturing%20Files) — Gerber, BOM, and pick-and-place data
- [Info.txt](Info.txt) — brief project summary and specifications

## Included files

### CAD and schematic

- [CAD Source Files/Schematic_RPI0W Power Hat_2021-05-21.pdf](CAD%20Source%20Files/Schematic_RPI0W%20Power%20Hat_2021-05-21.pdf)
- [CAD Source Files/RPI0W Power Hat_2021-05-21.json](CAD%20Source%20Files/RPI0W%20Power%20Hat_2021-05-21.json)
- [CAD Source Files/PCB_RPI0W Power Hat_2021-05-21.json](CAD%20Source%20Files/PCB_RPI0W%20Power%20Hat_2021-05-21.json)

### Mechanical

- [MCAD Files/PCB_RPI0W Power Hat_2021-05-21.dxf](MCAD%20Files/PCB_RPI0W%20Power%20Hat_2021-05-21.dxf)
- [MCAD Files/OBJ_PCB_RPI0W Power Hat_2021-05-21.zip](MCAD%20Files/OBJ_PCB_RPI0W%20Power%20Hat_2021-05-21.zip)

### Manufacturing data

- [Manufacturing Files/BOM_PCB_RPI0W Power Hat_2021-05-21.csv](Manufacturing%20Files/BOM_PCB_RPI0W%20Power%20Hat_2021-05-21.csv)
- [Manufacturing Files/Gerber_PCB_RPI0W Power Hat.zip](Manufacturing%20Files/Gerber_PCB_RPI0W%20Power%20Hat.zip)
- [Manufacturing Files/PickAndPlace_PCB_RPI0W Power Hat_2021-05-21.csv](Manufacturing%20Files/PickAndPlace_PCB_RPI0W%20Power%20Hat_2021-05-21.csv)

## Manufacturing and assembly notes

This project appears to be a reference hardware design and includes fabrication outputs suitable for PCB manufacturing. If you plan to build or order boards:

1. Review the schematic and board layout before fabrication.
2. Check the BOM for component availability and package types.
3. Confirm the selected battery chemistry and charging current requirements match your use case.
4. Verify the USB-C power path and power-switch wiring against your Raspberry Pi requirements.
5. If using the board in a production or safety-critical system, perform electrical validation and regulator testing before deployment.

## Design status

This repository is a hardware design package rather than a software project. It is best suited for:

- learning about portable Pi power designs
- reproducing or adapting the board for custom builds
- reviewing the schematic and PCB layout for engineering reference

## Notes

The project files are shared as-is for reference and prototyping. This repository does not currently include an explicit software license file, so if you intend to reuse the design commercially or distribute it publicly, confirm the appropriate licensing and compliance requirements for your use case.

## Project summary

Raspberry Pi Zero Power HAT is a compact battery-powered accessory board for Raspberry Pi Zero-class systems, providing regulated 5 V power, charging support, and portable operation from a single Li-ion/LiPo cell.

