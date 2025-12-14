# 🧠 Bus and Peripheral Verification Using SystemVerilog

## 📘 Overview
This project demonstrates the **design and verification** of AXI LIte and D-flip flop modules using **SystemVerilog**.  
Each module is implemented with its corresponding testbench, focusing on **functional correctness**, **protocol-level verification**, and **test-driven development** practices.

---

## 📁 Project Structure
```yaml
Bus_and_Peripheral_Verification_Using_SV/
├── SV_Verification_Projects/
│   ├── AXI_LITE/
│   │   ├── axi_lite.sv
│   │   └── tb_axi_lite.sv
│   └── D-FLIP_FLOP/
│       ├── d_flip_flop.sv
│       └── tb_d_flip_flop.sv
└── README.md

---
```
## ⚙️ Features
- ✅ Verification of  AXI Lite 
- ✅ Verification of D Flip-Flop and 4-bit Multiplier 
- ✅ Modular and reusable testbench architecture  
- ✅ Developed using **SystemVerilog (IEEE 1800-2017)**  

---

## 🧩 Tools Used
- **Icarus Verilog** or **Synopsys VCS** — for simulation  
- **GTKWave** — for waveform analysis  
- **Makefiles** *(optional)* — for simulation automation  

---

## 🚀 How to Run
1. Navigate to the desired project folder, e.g.:
   ```bash
   cd SV_Verification_Projects/AXI_LITE
## 🚀 How to Run

```yaml
# Step 1: Compile the design and testbench files
iverilog -o simv axi_lite.sv tb_axi_lite.sv

# Step 2: Run the simulation
vvp simv

# Step 3: View the waveform
gtkwave dump.vcd


- Gain hands-on experience with SystemVerilog verification
- Develop modular, reusable verification environments

