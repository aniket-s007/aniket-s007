<div align="center">

# Aniket Singh

**Electrical & Computer Engineering | VLSI & RTL Design | FPGA to ASIC**

🔗 [LinkedIn]([https://www.linkedin.com/in/aniket-singh/](https://www.linkedin.com/in/aniket-singh-a0026029a/)) &nbsp;·&nbsp; 💻 [GitHub](https://github.com/aniket-s007) &nbsp;·&nbsp; ✉️ [Email](mailto:as756@snu.edu.in)

</div>

---

> I'm a final-year Electrical and Computer Engineering student at Shiv Nadar University, specializing in VLSI and RTL design. I've worked across the ASIC design flow — writing and verifying RTL in Verilog, carrying it through synthesis, floorplanning, and place-and-route in the Synopsys toolchain, and physically validating PCBs as a research intern at IIT Delhi's PEARL Lab.
>
> I like getting close to the hardware: closing timing, reading a QoR report, and understanding what a netlist actually does on silicon, rather than treating the EDA toolchain as a black box.

---

## 🧩 Technical Skills

**Languages:** Verilog · Python

**EDA & CAD Tools:** Xilinx Vivado · Synopsys Design Compiler (DC) · Verdi · IC Compiler II (ICC2) · Cadence Virtuoso · Altium Designer

**VLSI & Hardware Concepts:** RTL-to-GDS Flow · Static Timing Analysis · FFT Architecture · PCB Design

---

## 💼 Experience & Education

**Research Intern — PEARL Lab, IIT Delhi**
*May 2025 – July 2025*

- Developed and physically validated 2 custom PCBs in Altium Designer: a buck converter (5–15 V) and a high-voltage (500 V) / high-current (20 A) sensing board.
- Engineered a single-phase IGBT inverter setup, converting 400 V DC to 220 V AC.

**B.Tech, Electrical and Computer Engineering**
*Shiv Nadar University, Greater Noida — Expected 2027 · CGPA 8.21/10*

---

## 🚀 Featured Projects

<details open>
<summary><b>🔬 Real_FFT — 4-Parallel Pipelined Real-Valued FFT</b></summary>
<br/>

Hardware for the FFT of real-valued signals, implementing a 2013 IEEE architecture (Salehi, Amirfattahi & Parhi) that exploits the Hermitian symmetry of real-signal spectra to skip the redundant arithmetic a general complex FFT wastes — real datapaths, real butterflies, no unnecessary complex multipliers. Built stage-by-stage in synthesizable Verilog, with every stage first derived and validated as a Python golden model (checked against `numpy.fft.rfft`) before being ported to bit-exact fixed-point RTL and verified in self-checking testbenches.

Applied to a real-world case study — detecting bearing faults from CWRU vibration data — to answer how few fixed-point bits the design can use before the fault signature disappears.

**Status:** Stage 4 of 4 built and verified; final shuffle/butterfly stage, full synthesis numbers, and design modifications in progress.

**Stack:** Verilog · Xilinx Vivado · Python

**[→ View Repository](https://github.com/aniket-s007/Real_FFT)**

</details>

<details>
<summary><b>📡 Architecture for DIF FFT — 16-Point Radix-2 DIF FFT</b></summary>
<br/>

A 16-point Radix-2 Decimation-in-Frequency FFT architecture written in Verilog using Q1.15 fixed-point arithmetic. Built a mux-based addressable readout wrapper to resolve I/O pin overutilization (534 vs. 210 pins available), cutting the top-level interface down to ~58 pins and enabling full synthesis and implementation on the target FPGA.

**Result:** Post-route usage of 1565 LUTs, 578 FFs, 4 DSPs, 0 BRAMs — timing closed at 80 MHz with WNS = 0.197 ns, zero violations.

**Stack:** Verilog · Xilinx Vivado

</details>

<details>
<summary><b>🏗️ ASIC Design Flow Implementation (RTL to GDS)</b></summary>
<br/>

Designed and verified a parameterized synchronous FIFO in Verilog, with a testbench covering write-only, read-only, simultaneous read/write, full, and empty conditions. Carried it through the full physical design flow — synthesis, floorplanning, power planning, placement, clock tree synthesis, and routing — and analyzed QoR metrics including timing slack and area utilization.

**Stack:** Verilog · Synopsys Design Compiler · IC Compiler II

</details>

<details>
<summary><b>💾 4×4 DRAM — Transistor-Level Memory Array</b></summary>
<br/>

Architected a full transistor-level 4×4 DRAM using 1T1C (one-transistor one-capacitor) cells in 180 nm CMOS technology. Built the peripheral circuits — row decoder, column MUX/DEMUX, word line drivers, and write drivers — and verified read/write functionality and data retention through simulation.

**Stack:** Cadence Virtuoso

</details>

<details>
<summary><b>📁 Verilog codes</b></summary>
<br/>

A collection of smaller Verilog designs and digital logic exercises.

**[→ View Repository](https://github.com/aniket-s007/Verilog_projects)**

</details>

---

## 🎯 Leadership & Involvement

- **Class Representative, B.Tech ECE '27** — Elected by 73% majority vote to represent the ECE cohort, bridging students and faculty/administration.
- **Electrical Team Member, Team Genesis SAE (2024–2025)** — Built PCBs and validated electrical circuits for the team's vehicle, Beast X.
- **Clubs & Societies:** IEEE Student Branch · Cultural Committee · Summit 2.0, Shiv Nadar University (2024–Present)

---

## 🎓 Current Focus

Finishing my final year of B.Tech while building out `Real_FFT` — a 4-parallel pipelined real-valued FFT core — stage by stage in Verilog, and going deeper into the RTL-to-GDS flow. Open to opportunities in VLSI, RTL/digital design, and ASIC physical design.

---

## 📊 GitHub Stats

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/aniket-s007/aniket-s007/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/aniket-s007/aniket-s007/output/github-contribution-grid-snake.svg">
  <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/aniket-s007/aniket-s007/output/github-contribution-grid-snake.svg" width="100%"/>
</picture>

<br/><br/>

<img src="https://streak-stats.demolab.com/?user=aniket-s007&theme=radical&hide_border=true&background=0D1117&stroke=2E9EF7&ring=2E9EF7&fire=2E9EF7" alt="GitHub Streak" />

</div>

---

<div align="center">

**Let's connect** — [LinkedIn](https://www.linkedin.com/in/aniket-singh/) · [GitHub](https://github.com/aniket-s007) · [Email](mailto:as756@snu.edu.in)

</div>
