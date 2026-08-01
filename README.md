# RV64I RISC-V Processor

A Verilog implementation of **Single-Cycle** and **5-Stage Pipelined** RV64I RISC-V processors developed as part of the *Introduction to Processor Architecture* course.

## Repository Structure

```
.
├── pipe_processor/              # 5-stage pipelined processor implementation
├── seq_processor/               # Single-cycle processor implementation
├── IPA_Pipelined_Project_Doc.pdf
├── IPA_Sequential_Project_Doc.pdf
└── README.md
```

## Features

### Single-Cycle Processor
- Complete RV64I datapath
- ALU and Control Unit
- Register File
- Instruction & Data Memory

### 5-Stage Pipelined Processor
- IF, ID, EX, MEM, WB pipeline stages
- Pipeline registers
- Data forwarding
- Hazard detection and stall control
- Branch handling with pipeline flush

## Tools

- Verilog HDL
- Icarus Verilog
- GTKWave

## Documentation

The project specifications are included in the repository:

- `IPA_Sequential_Project_Doc.pdf`
- `IPA_Pipelined_Project_Doc.pdf`

