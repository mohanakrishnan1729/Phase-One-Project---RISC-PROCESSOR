
# Design and Simulation of a 32-bit RISC Processor Using Verilog

## 📌 Project Overview
This project involves the design and simulation of a 32-bit Reduced Instruction Set Computer (RISC) processor using Verilog HDL. The processor is built from scratch and simulates the key principles of RISC architecture, focusing on simplicity, speed, and efficient instruction execution. The design supports essential R-type, I-type, and load/store instructions and was verified through simulation in Xilinx Vivado.

## ⚙️ Key Features
- 32-bit data path with support for signed arithmetic operations
- Custom instruction set architecture (ISA)
- Modular design including ALU, control unit, register file, and memory units
- Write-back enabled register file for data storage
- Separate instruction and data memory
- Verified through behavioral simulation

## 🛠️ Tools & Technologies Used
- **Hardware Description Language:** Verilog HDL
- **Simulation Tool:** Xilinx Vivado Design Suite
- **Target Platform:** ZedBoard (Xilinx Zynq-7000 series) — for future hardware implementation

## 📄 Design Methodology
The processor is implemented using a modular approach. Each module performs a specific task and integrates seamlessly with the others to enable smooth instruction execution. The core modules include:

- **ALU** – Performs arithmetic and logical operations
- **Control Unit** – Decodes instructions and generates control signals
- **Register File** – Stores and updates operands and results
- **Instruction Memory** – Stores program instructions
- **Data Memory** – Handles load and store operations

This architecture demonstrates the instruction fetch, decode, execute, memory access, and write-back stages of a typical RISC processor.

