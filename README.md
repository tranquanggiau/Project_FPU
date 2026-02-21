# **Floating Point Unit (FPU) – FPGA Implementation (Quartus II)**
## Project Summary

Designed and implemented a 32-bit IEEE 754 Floating Point Unit (FPU) using Quartus II targeting FPGA hardware.

This project focuses on hardware architecture design, synthesis, timing analysis, and functional verification, demonstrating practical FPGA development workflow suitable for Hardware / FPGA Engineer roles.

## Key Highlights

✔ Implemented IEEE 754 Single-Precision arithmetic on FPGA

✔ Designed system using schematic / block-based architecture

✔ Performed synthesis and timing analysis

✔ Verified functionality via simulation

✔ Evaluated resource utilization and optimization trade-offs

Technical Specifications

Floating Point Standard: IEEE 754 (32-bit)

Sign:	1 bit
Exponent:	8 bits
Mantissa:	23 bits

Bias = 127
Normalized representation with hidden leading bit.

## Supported Operations

Floating Point Addition

Floating Point Subtraction

Floating Point Multiplication

## Hardware Architecture

The FPU design consists of the following hardware stages:

1️⃣ Operand Decomposition

Extract sign, exponent, mantissa

Hidden-bit reconstruction

2️⃣ Exponent Alignment (Add/Sub)

Exponent comparison

Mantissa shifting

3️⃣ Arithmetic Core

Signed mantissa addition/subtraction

Mantissa multiplication

4️⃣ Normalization & Exponent Adjustment

Leading-zero detection

Mantissa shift correction

Exponent update

5️⃣ Result Packing

Reassemble IEEE 754 output format

## Development Environment

Design Tool: Quartus II

Simulation: ModelSim-Altera

Target FPGA: (e.g., Cyclone IV – update accordingly)

## Implementation Results
✔ Functional Verification

Tested with multiple operand combinations

Verified correct normalization behavior

Validated sign handling for different cases

✔ Synthesis & Timing

Completed full compilation in Quartus II

Reviewed timing report and critical paths

Verified design meets timing constraints

✔ Resource Utilization

Logic Elements usage analyzed

DSP block usage (if applicable)

Area vs performance trade-off considered
