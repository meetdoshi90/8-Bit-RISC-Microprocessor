
<h1 align="center">:desktop_computer: 8 Bit RISC Processor in Verilog :desktop_computer:</h1>
<h3 align="center">An 8-bit RISC based processor designed in verilog with x86 instructions</h3>

![Verilog](https://img.shields.io/badge/Verilog-Verilog--2001%20(IEEE%20Standard%201364--2001)-blue) 
![HDL Design](https://img.shields.io/badge/Quartus%20Pro%2021.2%20-Cyclone%2010-green) 
![Simulation](https://img.shields.io/badge/Model%20Sim-Intel%20FPGA%20Edition-lightgrey) 

## Features
<img src="https://user-images.githubusercontent.com/57676220/132168301-f67a5b83-57a4-497b-b523-0a09e9258919.png" width = 400>

## Architecture

### Processor
<img src="https://user-images.githubusercontent.com/57676220/132168071-533ecd34-3ef8-4dab-8fa4-406dfe81cd74.PNG" width = 400>

### ALU Block
<img src="https://user-images.githubusercontent.com/57676220/132168228-2d6a9789-ab0c-4465-b704-36c701c93c10.PNG" width = 400>

### Internal Buses
<img src="https://user-images.githubusercontent.com/57676220/132168389-b2416d2e-0460-4ed7-a03f-d18f0099b750.png" width = 400>

### Control Signals

<details>
<summary>List of internal control signals</summary>

1. `INSGRP`
2. `INSOPC`
3. `RDIM`
4. `RDDM`
5. `WRDM`
6. `OPERANDS1`
7. `OPERANDS2`
8. `OPERANDS3`
9. `ALU`
10. `RDLOAD`
11. `RDSTORE`
12. `ASSIGN`
13. `MOV`
14. `BRANCH`
15. `SPC`
16. `RSPC`
17. `SWRESET`
18. `STOP`
 
</details>

### Instruction Pipeline
<img src="https://user-images.githubusercontent.com/57676220/132168159-072b56d6-7e95-436e-a00c-9369ccff26ff.PNG" width = 400>

## Directory
```graphql
./src/* 
  ├─ src/images - # Processor modules and driver simulation results
  ├─ src/ALU.txt - # ALU Module of the processor
  ├─ src/DATAMEM.txt - # 16 Kilo Byte Data Memory
  ├─ src/GROUP00TEST-Driver.txt - # Testing Driver Code for Group 00 Instruction set
  ├─ src/GRP01&11TEST-Driver.txt - # Testing Driver Code for Group 01 && 11 Instruction set
  ├─ src/INSMEM.txt - # Instruction memory with 256 x 24 Bit instruction capability
  ├─ src/PROCESSOR.txt - # Processor module which assembles all sub-modules of the processor
  └─ src/PROCESSOR-STIMULUS.txt - # Processor Driver Code example
./Instruction-Set.pdf - # Driver instructions for the processor
./Doc.pdf - # Architecture and instruction formats
```
