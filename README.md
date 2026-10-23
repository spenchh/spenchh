# Spencer Kogoma

I'm studying **Computer Engineering and Violin Performance at Northwestern University**, graduating in June 2028. I work on FPGA datapaths, RTL verification, and digital hardware, with interests in chip design and hardware acceleration.

I'm currently a **Digital Design Engineer Intern with Amentum at NASA**, working on VHDL interfaces, cocotb verification, and a mixed-signal telemetry PCB. At Northwestern, I lead digital design for the **NU Silicon Initiative** and low-voltage electrical work for the **Northwestern Solar Car Team**.

[Portfolio](https://portfolio-beta-ebon-62.vercel.app) · [LinkedIn](https://www.linkedin.com/in/spencerkogoma)

## Selected work

| Project | What I've built |
| --- | --- |
| [FPGA Field-Oriented Motor Control](https://github.com/spenchh/FPGA-foc-motor-control) | Fixed-point motor-control RTL with current-loop simulation in Vivado/xsim. Pipelined control and protection paths to meet 100 MHz post-route timing with **+0.557 ns WNS** in the implementation wrapper. |
| [3×3 Systolic MAC Array](https://portfolio-beta-ebon-62.vercel.app/projects/systolic-mac-array.html) | Nine processing elements with signed 8-bit operands and 20-bit accumulators. Completed RTL and gate-level simulation, synthesis, and place-and-route in Nangate 45 nm, meeting a **500 MHz constraint with +0.241 ns setup slack**. |
| [FPGA Stream Stress Tester](https://github.com/spenchh/FPGA-Stream-Stress-Tester) | Parameterized 64-bit synchronous FIFO with directed cocotb tests for ordering, wraparound, and full/empty boundaries. Traffic generation, backpressure, and fault injection are ongoing work. |
| [Two-Lane Market Quote Checker](https://github.com/spenchh/Two-Lane-Market-Quote-Checker) | A SystemVerilog design exercise that checks bid/ask ordering and spread limits on two quotes in parallel. RTL is in progress; the testbench is a placeholder. |
| [Solar Car Rear-Vision System](https://github.com/spenchh/NUSol-Rear-View-Camera-Proj) | Vehicle-integrated camera system with measured glass-to-glass latency below 30 ms, plus Linux startup and automatic recovery services. |

## Current focus

- Building streaming RTL and self-checking testbenches, with attention to reset behavior, data retention, and queue boundaries.
- Exploring performance-guided on-chip fuzzing using queue occupancy and dependency stalls to find datapath latency bottlenecks.
- Teaching digital design through SystemVerilog exercises and RTL code reviews.

## Technical Stack

### Hardware and FPGA

![SystemVerilog](https://img.shields.io/badge/SystemVerilog-RTL-2F4F4F?style=flat-square)
![Verilog](https://img.shields.io/badge/Verilog-RTL-2F4F4F?style=flat-square)
![FPGA](https://img.shields.io/badge/FPGA-Digital%20Design-1F6FEB?style=flat-square)
![Vivado](https://img.shields.io/badge/Vivado-FPGA%20Toolchain-FFB000?style=flat-square)
![MATLAB](https://img.shields.io/badge/MATLAB-Modeling-0076A8?style=flat-square)

### Programming

![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

### Software and Tools

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![NPM](https://img.shields.io/badge/NPM-CB3837?style=flat-square&logo=npm&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chart.js&logoColor=white)

### Design and Verification

VHDL, Tcl, Bash, Xcelium, Genus, Innovus, cocotb, Verilator, Icarus Verilog, Xpedition, Altium Designer, Linux, Git

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Spencer%20Kogoma-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/spencerkogoma)

## GitHub Activity

![GitHub Stats](https://github-readme-stats.shion.dev/api?username=spenchh&theme=gotham&hide_border=true&include_all_commits=true&count_private=true)

![Top Languages](https://github-readme-stats.shion.dev/api/top-langs/?username=spenchh&theme=gotham&hide_border=true&include_all_commits=true&count_private=true&layout=compact)
