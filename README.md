# RISC-V Single Cycle Processor

## Overview
This project presents the design and implementation of a 32-bit single-cycle RISC-V processor using Verilog. The processor executes instructions in a single clock cycle by integrating datapath and control logic efficiently.

##  Features
- Supports arithmetic and logical operations
- Implements load and store instructions
- Handles branch instructions
- Single-cycle datapath design

## Architecture
The processor consists of the following modules:
- ALU (Arithmetic Logic Unit)
- Control Unit
- Register File
- Instruction Memory
- Data Memory

## Tools & Technologies
- Verilog HDL
- Xilinx Vivado / ModelSim

## Verification
- Functional verification performed using testbench simulations
- Waveforms analyzed to ensure correct instruction execution

##  Results
- Successful execution of RISC-V instructions
- Verified datapath and control signal coordination

##  Future Improvements
- Pipeline implementation for performance enhancement
- Hazard detection and forwarding mechanisms
- FPGA implementation and timing analysis
