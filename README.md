<div align="center">

# Karthik Manda

**Computer Engineering @ NTU Singapore · Gold Tier Alpha Researcher @ WorldQuant BRAIN · Apple Swift Student Challenge 2026 Winner**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://portfolio)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:mkarthik1725215@gmail.com)
[![WorldQuant BRAIN](https://img.shields.io/badge/WorldQuant_BRAIN-Gold_Tier_%F0%9F%8F%85-FFD700?style=flat-square)](https://worldquant.com)

</div>

---

## About

Penultimate-year Computer Engineering student at NTU Singapore with a crossover profile spanning **embedded systems**, **deep reinforcement learning**, **quantitative alpha research**, and **full-stack development**. Singapore PR.

- 🏅 **WorldQuant BRAIN Gold Tier** — top ~5% globally in quantitative alpha research
- 🍎 **Apple Swift Student Challenge 2026** — Global Top 300 winner
- 🏆 **HTX HackX 2025 Finalist** — Top 15 of 60 shortlisted teams (SCDF plume response dashboard)
- 🔬 Currently building: MADDPG multi-agent trading system, STM32 bare-metal gimbal, CodeRecon static analysis engine

---

## Technical Stack

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-FA7343?style=flat-square&logo=swift&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog-4B0082?style=flat-square)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Assembly](https://img.shields.io/badge/8086_Assembly-525252?style=flat-square)

### Embedded & Hardware
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-8CC84B?style=flat-square)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![MSP432](https://img.shields.io/badge/MSP432-C75000?style=flat-square)
![I2C](https://img.shields.io/badge/I2C-555555?style=flat-square)
![SPI](https://img.shields.io/badge/SPI-555555?style=flat-square)
![UART](https://img.shields.io/badge/UART-555555?style=flat-square)
![CAN Bus](https://img.shields.io/badge/CAN_Bus-555555?style=flat-square)
![PWM](https://img.shields.io/badge/PWM-555555?style=flat-square)

### ML / AI / Quant
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

### Web & Dev Tools
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Vivado](https://img.shields.io/badge/Vivado_HDL-E01F27?style=flat-square)

### Lab Instruments
Oscilloscope · Logic Analyzer · DC Power Supply

---

## Projects

### 🤖 Multi-Agent RL Trading System
`Python` `PyTorch` `MADDPG` `Pandas`

Designed a PyTorch-based MADDPG architecture for coordinated autonomous trading across 50+ assets simultaneously.
- Outperforms single-agent baselines with **Sharpe ratio of 1.5–2.0**
- OHLCV-based feature pipelines with portfolio-level reward shaping

---

### ⚙️ STM32 Gimbal Self-Levelling System
`Bare-Metal C` `STM32` `FreeRTOS` `MPU-6050` `I2C/SPI/UART/PWM`

Self-levelling gimbal with full bare-metal register configuration — no HAL abstraction.
- PID control with **Kalman + complementary filtering** for IMU sensor fusion over I2C
- Direct TIM, RCC, GPIO register configuration for PWM-based servo/DC motor control
- FreeRTOS tasks, queues, and semaphores for concurrent sensor polling, motor actuation, and UART telemetry

---

### 🔍 CodeRecon: Modular Static Analysis Engine
`Python` `AST` `Ollama` `GitHub Actions`

Repository-scale static analysis engine with local-first LLM inference.
- AST parser detects structural anti-patterns: dead code, complexity hotspots, coupling violations
- Local Ollama/Llama3 pipeline generates architecture-level refactor suggestions with **zero cloud data exposure**
- Automated CI/CD via GitHub Actions; published to **PyPI**

---

### 📡 Embedded Linux Client-Server & Defuse System
`C` `Raspberry Pi` `TCP Sockets` `GPIO`

Real-time embedded Linux system with hardware-software integration.
- TCP socket client-server for live sensor data streaming
- GPIO button input, buzzer/LED output, timer-based countdown logic with pass/fail event handling

---

### 🤖 RSLK-MAX Mobile Robot
`C` `MSP432` `DC Motor Control` `Timer Interrupts`

Line-following and closed-loop DC motor control on MSP432.
- Sensor feedback, duty-cycle adjustments, and hardware timer interrupt-driven control loop

---

### 🔢 8-bit ALU Design
`Verilog HDL` `Vivado` `8086 Assembly`

- 8-bit adder and multiplier in Verilog HDL
- Behaviour verified via Vivado waveform simulation and assembly-level arithmetic

---

### 🌐 Full-Stack Web Projects

| Project | Stack | Description |
|---|---|---|
| **Conspiracy Theory Research Datasite** | React, JavaScript | 4 production pages, WCAG 2.1 AA compliant, full SDLC — built during NTU internship |
| **HelioDesk** | React, JS, PostgreSQL, Supabase | Personal productivity dashboard; cross-platform storage reduces access time by 25% |
| **ParkLah** | React, TypeScript, PostgreSQL | Geolocation-based carpark finder with REST API integration |
| **Internship Placement Management System** | Java | CLI-based system; OOP-compliant across a multi-developer codebase |

---

### 🎨 UI/UX Design Projects

| Project | Description |
|---|---|
| **SeniorConnect™** | Mobile app concept tackling senior social isolation via CC event discovery and incentive system |
| **SCDF Risk Analysis Dashboard** | Operational risk dashboard for critical decision-making under pressure (HTX HackX context) |
| **StudyHavn** | UX research → wireframe → high-fidelity prototype for study location discovery |
| **CityDrip** | WCAG-aligned e-commerce experience with iterative user feedback integration |

---

## Experience

### 🟡 Alpha Researcher — Gold Tier · WorldQuant BRAIN *(2026 – Present)*
- Engineered data-driven alpha factors using financial signals and operational income parameters
- Applied cross-sectional normalisation to construct low-correlation alphas targeting quantitative equity markets
- Gold Tier = sustained alpha performance in top ~5% of global BRAIN consultants

### 💻 Web Development Intern · Wee Kim Wee School of Comm. & Info, NTU *(Feb – Mar 2026)*
- Architected and deployed full-stack Conspiracy Theory Research Datasite in React/JavaScript
- Delivered 4 production pages across complete SDLC; WCAG 2.1 AA compliant throughout

### 🔧 Wheeled Vehicle Technician · Singapore Armed Forces *(Jan 2023 – Aug 2024)*
- Maintained and diagnosed wheeled military platforms across engine, drivetrain, hydraulic, and electrical subsystems
- ECU-based fault diagnosis using scan tools; practical exposure to CAN-based vehicle communication networks

---

## Awards & Certifications

| Award | Detail |
|---|---|
| 🍎 Apple Swift Student Challenge 2026 | Global Top 300 — ArchLab system design simulator (Swift 6 concurrency) |
| 🏆 HTX HackX 2025 Finalist | Top 15 / 60 teams — SCDF hazardous chemical plume response dashboard |
| 📜 ML Specialization | DeepLearning.AI / Stanford Online — Andrew Ng full curriculum |
| 📜 J.P. Morgan Forage | Software Engineering, Investment Banking (DCF/WACC/M&A), Quantitative Research tracks |
| 📜 AMD AI Developer Programme | AI app development & LLM fine-tuning on ROCm/AMD GPU ecosystem |
| 📜 Web Design for Everybody | University of Michigan |
| 📜 UI/UX Design | CalArts |
| 📜 UX Research | University of Michigan |
| 📜 Cisco CCNA | Networking fundamentals |

---

## Leadership

| Role | Organisation | Period |
|---|---|---|
| Head of Events | NTU Indian Society | May 2025 – Present |
| Chief Programmer | NTU CCDS Transition & Orientation Programme | Sep 2025 |
| Program Planner | NTU Students of Computing & Data Science Club | Sep 2024 – Sep 2025 |
| English Club Leader | Narayana English Club | Oct 2018 – Jun 2020 |

---

## Education

**B.Eng (Hons), Computer Engineering** · Nanyang Technological University, Singapore *(Aug 2024 – Present)*

Coursework: Data Structures & Algorithms · Object Oriented Programming · Operating Systems · Microprocessor System Design · Embedded Programming · Digital Logic · Digital System Design · Signals & Transforms · Sensor Interfacing & Digital Control · C/C++

---

<div align="center">
<sub>Singapore PR · Open to internship opportunities in quant finance, embedded systems, and full-stack engineering</sub>
</div>
