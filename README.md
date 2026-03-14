<h1 align="center"> 💻 Varjula Balakrishna </h1>

<h3 align="center"> Aspiring Digital Design & Verification Engineer | RTL • RISC-V • FPGA • ASIC </h3>

---

<p align="center">
  <img src="https://img.shields.io/badge/RTL%20Design-Verilog-green?style=for-the-badge&logo=verilog" />
  <img src="https://img.shields.io/badge/EDA%20Tools-Vivado%20%7C%20OpenLane%20%7C%20Cadence-yellowgreen?style=for-the-badge&logo=gnu" />
  <img src="https://img.shields.io/badge/PDK-SkyWater%20130nm-blue?style=for-the-badge" />
</p>

---

## 🔧 About Me

I’m passionate about **Digital System Design, RISC-V Architecture, FPGA Development, and Physical Design**.  
I enjoy translating hardware ideas into **clean RTL**, validating them through simulation, and pushing them all the way to physical silicon layouts.

Actively preparing for roles in:

- **ASIC / FPGA Design**
- **RISC-V Processor Development**
- **Physical Design (Synthesis & STA)**
- **SoC / Subsystem Design**

---

## 🛠️ Skills & Tools

- **HDL & Programming:** `Verilog HDL`, `C / C++`, `Python`
- **Digital Design:** RTL Design, FSMs, Datapath & Control, Pipelining, Approximate Computing
- **Computer Architecture:** RISC-V RV32I, 5-Stage Pipeline, Data & Control Hazards
- **FPGA Tools:** Xilinx Vivado, Intel Quartus Prime
- **ASIC / Physical Design:** OpenLane RTL-to-GDSII Flow, Cadence Encounter, Synthesis (Yosys/ABC), Floorplanning, STA, SkyWater 130nm PDK
- **EDA & Simulation:** Cadence Virtuoso, ModelSim / QuestaSim, GTKWave, KLayout, Magic
- **Analog & Mixed-Signal Tools:** LTspice, NI Multisim, MATLAB
- **Scripting & Automation:** TCL, Bash
- **Version Control & Docs:** Git, GitHub, Markdown

---

## 🚀 Projects

### 🔹 RISC-V 32-bit 5-Stage Pipelined Processor  
**Verilog HDL | Xilinx Vivado**

- Designed an RV32I processor with IF, ID, EX, MEM, and WB pipeline stages.
- Implemented ALU, register file, control unit, pipeline registers, and memory interfaces.
- Handled **data hazards** using forwarding logic and **control hazards** using stalling and flushing.
- Verified functionality using instruction-level simulation and self-checking testbenches.

---

### 🔹 Hybrid-Approx-FIR-ASIC: RTL to GDSII  
**Verilog HDL | OpenLane | SkyWater 130nm | Xilinx Vivado**

- Designed Exact, 1-Error, and 2-Error Approximate 4:2 Compressors using sorting networks for MAC pipelines.
- Executed a complete open-source **RTL-to-GDSII physical design flow** using OpenLane and the Sky130 High-Density PDK.
- Discovered the physical CMOS **"XOR Trap"** where mathematically smaller 2-Error architectures consume more ASIC standard-cell area than 1-Error variants due to complex routing penalties.
- Proved the 2-Error design achieves **99% higher system-level accuracy** via statistical error decorrelation, making it the superior architecture for FPGAs (LUTs) and high-fidelity DSP applications.

---

### 🔹 ASIC Implementation of 16-bit ALU (RTL → GDSII)  
**Verilog HDL | Cadence Encounter | TCL**

- Designed a 16-bit ALU supporting arithmetic, logical, and shift operations.
- Completed full **RTL-to-GDSII flow** including synthesis, floorplanning, placement, routing, and STA.
- Automated backend flow using TCL scripts and validated post-synthesis timing.

---

### 🔹 Synchronous FIFO  
**Verilog HDL**

- Designed a parameterized synchronous FIFO with configurable depth and data width.
- Implemented full, empty, and almost-full/empty flags.
- Verified correct operation using directed and self-checking testbenches.

---

### 🔹 Data Transfer FSM  
**Verilog HDL**

- Designed a finite state machine for controlled data transfer between modules.
- Ensured proper handshaking, sequencing, and error-free state transitions.
- Simulated and validated all operating conditions.

---

### 🔹 Stream Cipher  
**Verilog HDL**

- Implemented a stream cipher for secure data encryption and decryption.
- Designed key scheduling and keystream generation logic.
- Verified functional correctness through simulation with multiple test vectors.

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=VBK0-0&show_icons=true&theme=dark" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=VBK0-0&layout=compact&theme=dark" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=VBK0-0&theme=react-dark" />
</p>

---

## 📫 Connect With Me

- 📧 **Email:** varjulabalakrishna2002@gmail.com  
- 💼 **LinkedIn:** https://www.linkedin.com/in/varjula-balakrishna-5422861a6/  

---

<p align="center">
  ⚡ <i>Designing and debugging digital logic — one module at a time.</i>
</p>
