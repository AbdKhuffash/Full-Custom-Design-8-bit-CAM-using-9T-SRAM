# Full Custom Design 8 bit CAM using 9T SRAM

## Project Overview
This repository contains the design and development of an 8-bit Content Addressable Memory (CAM) utilizing a 9T SRAM configuration.

## Abstract
The objective of this project was to design and implement an efficient 8-bit CAM system with a focus on power efficiency and area optimization. Key features of the design include the use of 9T SRAM cells, low power considerations, and effective read and write functionalities. The project also integrates parallel searching mechanisms for enhanced performance in various applications.

## Introduction
The integration of 9-transistor Static Random-Access Memory (SRAM) in Content Addressable Memory (CAM) represents a significant advancement in computer memory technology. This repository documents the design process, implementation, and simulation results of an 8-bit CAM system utilizing 9T SRAM cells.

## System Components
9T SRAM: The project utilizes a custom-designed 9T SRAM cell for efficient memory utilization and power-saving.
CAM Cell: The CAM cell is implemented using 9T SRAM, XOR gates, and decoding mechanisms.
8-Bit CAM: Comprised of 16 1-bit CAM cells and two decoders, the 8-bit CAM facilitates parallel searching and fast data retrieval.
## System Design
The system design encompasses the following key components:

#### 9T SRAM
Schematic and layout designs for the 9T SRAM cell tailored for 14nm CMOS technology.

Optimization for power efficiency and minimized area requirement.

Integration of read and write functionalities with inputs and outputs.

#### 1-Bit CAM Cell
Transformation of 9T SRAM into a 1-bit CAM cell using XOR gates.

Schematic and layout designs for efficient data comparison and retrieval.

#### 8-Bit CAM
Assembly of 16 individual 1-bit CAM cells organized to handle 8 bits of data.

Integration of decoders for selecting and directing data flow.

Design and implementation of essential components including NAND gate, decoders, and encoders.

## Conclusion
The development of the 8-bit CAM system using 9T SRAM cells demonstrates significant advancements in memory technology. The project successfully achieves the objectives of power efficiency and area optimization while maintaining effective read and write functionalities. Further research and optimization efforts have led to substantial improvements in power consumption and delay reduction, marking a significant milestone in the field of computer memory systems.

For detailed schematics, layouts, and simulation results, please refer to the attached files in the repository.
