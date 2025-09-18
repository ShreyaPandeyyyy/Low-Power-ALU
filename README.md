# ⚡ Low Power and Area-Efficient ALU (Verilog, FPGA)

## 📌 Overview
Designed and implemented a **1-bit, 8-function Arithmetic Logic Unit (ALU)** in Verilog HDL, optimized for **low power** and **minimal area**, and validated through **FPGA simulation**. Applies **advanced VLSI design techniques** to achieve high efficiency with compact hardware.

---

## 🔑 Key Highlights
- Arithmetic: ADD, SUB  
- Logic: AND, OR, NAND, NOR, XOR, XNOR  
- **99.998% power reduction** vs baseline design  
- **30% area savings** on silicon footprint  
- **148 ps speed** (ultra-fast operation)  
- Verified functionality on **FPGA hardware**  

---

## 🛠️ Tools & Technologies
- Verilog HDL, Xilinx ISE / Vivado, FPGA board  
- 45nm CMOS technology with GDI (Gate Diffusion Input)  

---

## 🚀 Impact
- Demonstrates **ultra-low power VLSI design** for embedded/IoT applications  
- Architecture suitable for **mobile processors, IoT, and edge devices**  

---

## 📊 Results & Simulation

### 🔧 Schematic
![ALU Schematic](images/alu_schematic.png)  
*Fig. 1. Schematic diagram of 1-bit ALU using optimized full adders*

### 📈 Simulation Outputs
![Multiplexer Output](images/mux_output.png)  
*Fig. 2. Produced output of 2x1 Multiplexer*

![ALU Output](images/alu_output.png)  
*Fig. 3. Produced output of 4-bit ALU using optimized techniques*

### 📉 Power Consumption Comparison
| Design Technique | Transistors | Delay (ns) | Power (nW) |
|------------------|-------------|------------|------------|
| ALU with GDI     | 60          | 1 ns       | 37.533 nW  |
| ALU with 2T XNOR | 60          | 1 ns       | 36.844 nW  |
| ALU with 2T XOR  | 60          | 1 ns       | 36.933 nW  |
| ALU with Pass T  | 60          | 1 ns       | 37.268 nW  |

*Table 1. Comparison of power consumption across different ALU designs*

---

👩‍💻 **Author:** Shreya Pandey (B.E. ECE, BMSCE)  
