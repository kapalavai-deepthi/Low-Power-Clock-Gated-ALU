# Low-Power Clock Gated ALU

## Overview

This project implements a Low-Power Arithmetic Logic Unit (ALU) using Clock Gating in Verilog HDL.

The design reduces unnecessary clock switching by enabling the clock only for the functional unit selected by the control logic. This helps reduce dynamic power consumption while maintaining correct ALU functionality.

---

## Features

- Verilog HDL implementation
- Clock Gating for low-power operation
- FSM-based Control Unit
- Arithmetic Unit
- Logic Unit
- Shift Unit
- Multiply/Divide Unit
- Advanced Operations Unit
- Output Multiplexer
- Fully verified using a SystemVerilog Testbench

---

## Functional Units

- Arithmetic Operations
  - Addition
  - Subtraction
  - Increment
  - Decrement

- Logic Operations
  - AND
  - OR
  - XOR
  - NOT
  - NAND
  - NOR
  - XNOR

- Shift Operations
  - Left Shift
  - Right Shift
  - Rotate Left
  - Rotate Right

- Multiply / Divide Operations

- Advanced Operations
  - Maximum
  - Minimum
  - Equality Check

---

## Repository Structure

```
Low-Power-Clock-Gated-ALU/
│
├── README.md
├── Docs/
├── RTL/
├── Testbench/
└── results/
```

---

# Architecture

## Normal ALU Architecture

![Normal ALU](Docs/normal_alu_architecture.png)

## Clock-Gated ALU Architecture

![Clock Gated ALU](Docs/clock_gated_alu_architecture.png)

---

# Simulation Results

## Normal ALU Waveform

![Normal Waveform](results/normal_alu_waveform.png)

## Normal Console Output

![Normal Console](results/normal_console_output.png)

## Clock-Gated ALU Waveform

![Clock Gated Waveform](results/clock_gated_waveform.png)

## Clock-Gated Console Output

![Clock Gated Console](results/clock_gated_console_output.png)

---

# Power Comparison

## Normal ALU Power

![Normal Power](results/power_normal.png)

## Clock-Gated ALU Power

![Clock Gated Power](results/power_clock_gated.png)

---

## Simulation Tool

- ModelSim / QuestaSim

---

## Language

- Verilog HDL
- SystemVerilog (Testbench)

---

## Author

**Deepthi K**
