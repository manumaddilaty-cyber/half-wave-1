# Half Wave Rectifier using Verilog HDL

## Overview

This project implements a digital model of a Half Wave Rectifier using Verilog HDL.

A Half Wave Rectifier allows only the positive half of an input waveform to appear at the output while blocking the negative half.
## Features

- Verilog HDL implementation
- Testbench included
- Easy to simulate in ModelSim, Vivado or Icarus Verilog
- Suitable for FPGA learning

## Project Files

- half_wave_rectifier.v
- half_wave_rectifier_tb.v
- simulation_results.md

## Working Principle

If Input > 0
    Output = Input

Else
    Output = 0

## Expected Output

Input | Output
------|-------
20 | 20
40 | 40
-15 | 0
-50 | 0
30 | 30
-10 | 0
60 | 60

## Simulation

Compile

```
iverilog half_wave_rectifier.v half_wave_rectifier_tb.v
```

Run

```
vvp a.out
```

Generate waveform

```
gtkwave waveform.vcd
```

## Applications

- Signal Processing
- FPGA Design
- Digital Electronics
- Learning Verilog HDL

## Author

Your Name