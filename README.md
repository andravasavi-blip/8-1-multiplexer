# 8×1 Multiplexer using Verilog

## Project Overview

This project implements an **8×1 Multiplexer (MUX)** using Verilog HDL.

An 8×1 Multiplexer selects one of eight input signals and forwards it to a single output based on the value of three select lines.

---

## Truth Table

| S2 | S1 | S0 | Output |
|----|----|----|--------|
|0|0|0|I0|
|0|0|1|I1|
|0|1|0|I2|
|0|1|1|I3|
|1|0|0|I4|
|1|0|1|I5|
|1|1|0|I6|
|1|1|1|I7|

---

## Files

- `mux8x1.v` – Verilog design
- `mux8x1_tb.v` – Testbench
- `simulation_result.png` – Simulation waveform
- `README.md` – Documentation

---

## Software Used

- ModelSim / Vivado Simulator / Icarus Verilog
- GTKWave (optional)

---

## Simulation Steps

1. Compile the design file.
2. Compile the testbench.
3. Run the simulation.
4. Observe the waveform.

---

## Expected Output

The output follows the selected input according to the select lines.

Example:

S=000 → Y=I0

S=001 → Y=I1

S=010 → Y=I2

...

S=111 → Y=I7

---

## Author

Your Name