# FPGA-Based Digital Clock ⏰

A 24-hour digital clock implemented in **Verilog HDL** on an FPGA board.  
The design demonstrates clock division, counters, debouncing, and 7-segment multiplexing.

## 🔧 Features
- 24-hour clock (HH:MM) with seconds tracked internally
- Clock divider generates 1 Hz, 100 Hz, and 1 kHz signals
- Debounced push buttons for hour/minute adjustment
- Multiplexed 7-segment display driver
- Blinking colon/LED indicator for seconds

## 📂 Repository Structure
- `src/` – Verilog source files  
- `sim/` – Testbenches for simulation  
- `constraints/` – FPGA board pin mappings (XDC/QSF)  
- `docs/` – Design documentation and block diagrams  
- `output/` – Demo photos and simulation results  

## ▶️ Simulation
Run the testbench in ModelSim / Vivado Simulator to verify second → minute → hour rollover.

## 🖥️ Hardware
- **FPGA Board**: (Basys-3 / Nexys-A7 / DE10-Lite)  
- **Tools**: Xilinx Vivado / Intel Quartus

## 📸 Demo
![7-Segment Clock](output/board_running.jpg)

---

## Author
👤 Your Name  
📧 your.email@example.com  
🔗 [LinkedIn](https://linkedin.com/in/yourprofile) | [GitHub](https://github.com/yourusername)
