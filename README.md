<h1 align="center"> FPGA-Based Real-Time Digital Clock</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-FPGA-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Language-Verilog%20HDL-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Tool-Vivado%2FQuartus-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Display-7--Segment-black?style=for-the-badge">
</p>

---

## Project Overview

A **24-hour digital clock** implemented on an **FPGA development board** using **Verilog HDL**.  
The system tracks **hours, minutes, and seconds**, displays them on a **7-segment display**, and includes **push-button controls** for time adjustment.

> Demonstrates **digital logic design concepts** like clock division, counters, debouncing, and display multiplexing.

---

##  Features

✅ 24-hour format digital clock (HH:MM)  
✅ Clock divider from 100 MHz/50 MHz → 1 Hz pulse  
✅ Debounced push buttons for hour & minute adjustment  
✅ Multiplexed **7-segment display driver**  
✅ Blinking colon/LED for seconds indication  
✅ Modular Verilog design for easy extensions  

---

##  System Workflow

- 🔄 **Clock Divider**: Converts FPGA’s high-frequency clock into a 1 Hz tick  
- ⏱️ **Counters**: Seconds → Minutes → Hours rollover (24-hour format)  
- 🎛️ **Input Control**: Push buttons adjust hours/minutes (debounced for accuracy)  
- 🔢 **Display Driver**: Multiplexes digits onto the 7-segment display  
- ✨ **Colon LED**: Toggles every second for real-time effect  

---

##  Repository Structure
- `src/` – Verilog source files  
- `sim/` – Testbenches for simulation  
- `constraints/` – FPGA board pin mappings (XDC/QSF)  
- `docs/` – Design documentation and block diagrams  
- `output/` – Demo photos and simulation results  

##  Simulation
Run the testbench in ModelSim / Vivado Simulator to verify second → minute → hour rollover.

##  Hardware
- **FPGA Board**: (Basys-3 / Nexys-A7 / DE10-Lite)  
- **Tools**: Xilinx Vivado / Intel Quartus

## Demo
![7-Segment Clock](output/board_running.jpg)

---

## Author
👤 Gagan H 
🔗 [GitHub](https://github.com/Gaganh2403)
