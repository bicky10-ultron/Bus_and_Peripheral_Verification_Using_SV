# 🧠 Bus and Peripheral Verification Using SystemVerilog

## 📘 Overview
This project demonstrates the **design and verification** of common digital communication buses and peripheral modules using **SystemVerilog**.  
Each module is implemented with its corresponding testbench, focusing on **functional correctness**, **protocol-level verification**, and **test-driven development** practices.

---

## 📁 Project Structure
```yaml
Bus_and_Peripheral_Verification_Using_SV/
├── SV_Verification_Projects/
│   ├── AHB_Memory/
│   │   ├── ahb.sv
│   │   └── tb_ahb.sv
│   ├── APB_RAM/
│   │   ├── apb_ram.sv
│   │   └── tb_apb_ram.sv
│   ├── AXI_LITE/
│   │   ├── axi_lite.sv
│   │   └── tb_axi_lite.sv
│   ├── FIFO/
│   │   ├── fifo.sv
│   │   └── tb_fifo.sv
│   ├── UART/
│   │   ├── uart.sv
│   │   └── tb_uart.sv
│   ├── I2C/
│   │   ├── i2c.sv
│   │   └── tb_i2c.sv
│   ├── SPI/
│   │   ├── spi.sv
│   │   ├── spi_with_slave.sv
│   │   ├── tb_spi.sv
│   │   └── tb_spi_with_slave.sv
│   └── WHISHBONE_MEMORY/
│       ├── whishbone_mem.sv
│       └── tb_whishbone_mem.sv
└── README.md

---

## ⚙️ Features
- ✅ Verification of **standard bus protocols** — AHB, APB, AXI, and Wishbone  
- ✅ Verification of **peripheral modules** — UART, SPI, I²C  
- ✅ Examples for **FIFO** and **D Flip-Flop** designs  
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
- Understand and verify SoC interconnect protocols:
    - AHB
    - AXI
    - APB
    - Wishbone
- Gain hands-on experience with SystemVerilog verification
- Develop modular, reusable verification environments
- Strengthen understanding of digital communication systems

