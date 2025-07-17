# Smart-Traffic-Management-System

This project implements a **Verilog HDL-based Smart Traffic Management System** using **Finite State Machine (FSM)** design principles. It aims to optimize traffic flow, handle emergency vehicle prioritization, and ensure system resilience during signal failures.

## Features

- **FSM-Based Control Logic:** Efficient RTL-level state machine for traffic signal sequencing.
- **Emergency Vehicle Override:** Ambulance, firetruck, or VIP detection triggers emergency green-light routing for 10 seconds.
- **Failure Detection Mode:** Automatically switches to safe default mode if malfunction occurs.
- **Adaptive Signal Timing:** Dynamically adjusts green signal duration based on real-time traffic density.
- **LCD Display Integration:** Displays signal state, countdown timer, and emergency indicators.
- **Buzzer Alert System:** Activates during emergency mode to warn surrounding vehicles and pedestrians.

## Tech Stack

- **Language:** Verilog HDL
- **Simulation & Verification:** ModelSim
- **Synthesis & Power Analysis:** Xilinx Vivado
- **Target Platform:** RTL simulation (no physical FPGA board required)

## Outcomes

- Designed and verified a robust, real-time traffic controller module.
- Implemented modular FSM logic for different traffic states and emergency handling.
- Conducted power and area analysis using Vivado.
- Contributed to a research publication in a VLSI/Embedded Systems conference.

## 👨‍💻 Contributors

- Dharavath Renu

> Developed under the **Undergraduate Summer Research Fellowship (USRF) 2025** at **Amity University, Noida**, under the mentorship of **Prof. M.K. Dutta**, **Dr. Nidhi Gaur**, and **Dr. Pradeep Kumar**.
