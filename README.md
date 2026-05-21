# Hybrid-Approximate-Dadda-Multiplier
Quality-Scalable Hybrid Approximate 8×8 Dadda Multiplier for Image Processing Applications using Verilog HDL, FPGA Synthesis, MATLAB and Python-based Error Analysis.


# Hybrid Approximate Dadda Multiplier for Image Processing Applications

## Overview

This project presents a **Quality-Scalable Hybrid Approximate 8×8 Dadda Multiplier** designed for low-power and high-speed image processing applications.

The architecture combines:
- Accurate computation for Most Significant Bits (MSBs)
- Approximate computation for Least Significant Bits (LSBs)

This hybrid strategy reduces:
- Hardware complexity
- Power consumption
- Critical path delay

while maintaining acceptable image quality.

---

## Features

- 8×8 Hybrid Approximate Dadda Multiplier
- Verilog HDL Implementation
- FPGA Synthesis using Xilinx Vivado
- MATLAB-Based Image Processing Analysis
- Python-Based Error Metric Evaluation
- Quality-Scalable Approximation Modes
- Low Power and Reduced LUT Utilization

---

## Approximation Modes

| Mode | Description |
|------|-------------|
| Accurate Mode | Exact multiplication |
| Mode 1 | 3-bit LSB truncation |
| Mode 2 | 4-bit LSB truncation |

---

## Architecture

### Block Diagram

![Architecture](docs/images/architecture.png)

---

## FPGA Resource Utilization

| Parameter | Accurate | Mode 1 | Mode 2 |
|---|---|---|---|
| LUT Count | 118 | 94 | 82 |
| Delay (ns) | 8.42 | 7.18 | 6.73 |
| Power (mW) | 22.4 | 18.8 | 17.0 |

---

## Error Metrics

| Metric | Mode 1 | Mode 2 |
|---|---|---|
| MED | 1.750 | 3.500 |
| NMED | 0.0000267 | 0.0000534 |
| MSE | 4.083 | 16.333 |
| Accuracy | 99.997% | 99.995% |

---

## Image Quality Results

| Mode | PSNR | SSIM |
|---|---|---|
| Mode 1 | 38.7 dB | 0.982 |
| Mode 2 | 32.4 dB | 0.961 |

---

## Simulation Results

### Accurate Dadda Multiplier

![Accurate](docs/images/accurate_waveform.png)

### Approximate Dadda Multiplier

![Approximate](docs/images/approx_waveform.png)

---

## MATLAB and Python Outputs

### Mode 1 Output

![Mode1](docs/images/mode1_output.png)

### Mode 2 Output

![Mode2](docs/images/mode2_output.png)

---

## Technologies Used

- Verilog HDL
- Xilinx Vivado
- MATLAB
- Python
- FPGA Design
- Digital VLSI Design

---

## Folder Structure

```text
verilog/          -> Verilog HDL source files
testbench/        -> Testbench files
matlab/           -> MATLAB simulation scripts
python/           -> Python analysis scripts
vivado_reports/   -> Synthesis and timing reports
docs/images/      -> Project images and waveforms
docs/results/     -> Final results and comparisons
```

---

## Applications

- Image Processing
- DSP Systems
- Edge Detection
- Gaussian Filtering
- Embedded Systems
- Low Power Hardware Accelerators
- AI Accelerators

---

## Future Scope

- 16×16 and 32×32 Approximate Multipliers
- CNN Accelerator Integration
- Dynamic Quality Scaling
- ASIC Implementation
- Edge AI Hardware

---

## Author

Anuga Laasika Reddy  
ECE | VLSI | FPGA | AI Hardware Research
