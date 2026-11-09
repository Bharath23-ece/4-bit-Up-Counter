# 4-bit Synchronous Up Counter

## Project Overview
A 4-bit synchronous up counter designed using Verilog HDL. The counter increments its value on every falling edge of the clock.

## Features
- 4-bit binary up counter
- Negative-edge-triggered clock
- Synchronous active-high reset
- Counts from 0 to 15
- Automatically rolls over from 15 to 0

## Counting Sequence

`0000 → 0001 → 0010 → 0011 → ... → 1111 → 0000`

## Design Details
- Number of flip-flops: 4
- Number of possible states: 16
- Counting type: Up counter
- Reset type: Synchronous active-high
- Clock triggering: Negative edge

## Simulation Tools
- Verilog HDL
- Visual Studio Code
- Icarus Verilog
- GTKWave

## Project Files

| File | Description |
|---|---|
| `counter_4bit.v` | RTL design |
| `tb_counter_4bit.v` | Simulation testbench |
| `counter.vcd` | Simulation waveform data |
| `counter_waveform.png` | GTKWave waveform screenshot |

## Simulation
The RTL design is simulated using Icarus Verilog. The generated VCD waveform is viewed using GTKWave to verify the counter operation, reset behaviour, and counting sequence.

## Learning Outcomes
- Sequential circuit design
- Negative-edge-triggered operation
- Synchronous reset implementation
- Modulo-16 counting
- RTL simulation and waveform analysis

## Author
Bharath S  
Electronics and Communication Engineering
