# Nano Processor – VHDL Project

A custom-designed **4-bit Nano Processor** built as part of a university-level digital systems and processor design module. Developed using **VHDL** and simulated using **Xilinx Vivado**, this project introduces the core concepts of processor architecture, instruction execution, and hardware simulation.

---

## 📚 Project Overview

Over a 14-week academic module, we incrementally designed and built the components of a simple **Nano Processor**:

- 4-bit ALU (Arithmetic & Logic Unit)
- Register Bank (8 registers)
- Instruction Decoder
- Program Counter
- Program ROM
- Multiplexers
- Clock Divider
- 7-Segment Display Output

Each module was verified individually and then integrated to build a functional processor that can execute a small instruction set.

---

## 🏗️ Architecture

The processor architecture supports:

- **Move** immediate value to register
- **Add/Subtract** values from registers
- **Multiply** register values
- **Conditional Jump** instructions
- **7-Segment display** output
- 3-bit **Program Counter**

The system is clocked using a slow clock to match timing for visual simulation and hardware testing.

## Features
- 4-bit arithmetic unit
- Register Bank
- Instruction decoder
- ROM program execution
- VHDL simulation with Vivado

## Authors
- Iran Samarasekara
- Janindu Disanayaka
- Pavan Epa
- Chameera K.H.D

## Simulation
All testbenches written in VHDL and simulated using Vivado.

## Document
The final report is in `doc/Nano_Processor Final Lab Report.pdf`

