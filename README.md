# Uchchhash Sarkar

📍 Sector 14, Uttara, Dhaka 1230, Bangladesh  
📞 +8801778944122  
📧 uchchhash.sarkar@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/uchchhash) 
🔗 [GitHub](https://github.com/uchchhash)
🔗 [ResearchGate](https://www.researchgate.net/profile/Uchchhash_Sarkar)

---

## 🎓 Academic Credentials

**Bachelor of Science (B.Sc.) in Electrical and Electronic Engineering**  
*Ahsanullah University of Science and Technology (AUST), Dhaka, Bangladesh*  
📅 **Duration:** Nov 2016 – Aug 2021  
📊 **CGPA:** 3.584 / 4.00  
📈 **Last Four Semesters:** 3.854 / 4.00 

<details>
<summary><strong>📘 Relevant Coursework & Grades</strong></summary>

- VLSI I & Lab – A+, A+ (4.00)  
- VLSI II & Lab – A+, A+ (4.00)  
- Computer Architecture – A+ (4.00)  
- Microprocessor & System Design & Lab – A+, A+ (4.00)  
- Digital Logic Design – A+ (4.00)  
- Digital Signal Processing I & Lab – A+, A+ (4.00)  
- Analog Integrated Circuit – A (3.75)  
- Project & Thesis – A+ (4.00)  

</details>

---

## 💼 Professional Experience

**Contingent Worker – Contracted to Synopsys, Inc.**  
*Ulkasemi Private Limited, Dhaka, Bangladesh*  
📅 **Duration:** Mar 2024 – Present  
- Contributing to RTL design verification, focusing on high-speed protocols such as LPDDR and HBM.
- Conducting debugging, coverage analysis, and protocol checks to ensure design compliance with specifications.
- Ensuring design compliance through collaboration with global DV teams.

**Senior Engineer – Design Verification, Silicon Engineering Department**  
*Ulkasemi Private Limited, Dhaka, Bangladesh*  
📅 **Duration:** Dec 2021 – Present  
- Developing test plans, implementing self-checking testbenches, and conducting debugging, coverage analysis, and protocol verification for IP-level RTL designs using SystemVerilog and UVM.
- Modeling and validating mixed-signal designs by creating self-checking testbenches and verifying schematics against design specifications.
- Designing synthesizable RTL modules and control logic for interface and sequential systems, aligned with protocol specifications.
- Leading technical recruitment and conducting training on HDL, testbench development, and verification methodologies to align new hires with industry standards.

---

## 📄 Publication

**Noman, M. A. N., Majumder, P., Sarkar, U., & Karmaker, S.** (2023).  
*Optimizing Threshold Voltage Performance in AlGaN/GaN MIS-HEMTs through GaON Integration*.  
Presented at the **9th IEEE International Women in Engineering (WIE) Conference on Electrical and Computer Engineering (WIECON-ECE)**.  
🔗 [View on IEEE Xplore](https://ieeexplore.ieee.org/document/10456403)

---

## 🧪 Selected Projects


### 🔌 High-Speed Interface and Protocol Verification

<details>
<summary><strong>✅ Functional Verification of HBM4 PHY Layer</strong></summary>

**Organization:** Synopsys Inc | 📅 Duration: Jun 2024 – Present  
**Objective:** Implement and verify HBM4 PHY initialization and training sequences for mission mode readiness.  

**Contributions:**
- Implemented key initialization steps, including power-up, clock setup, CSR configuration, and PHY initialization.  
- Analyzed specifications to determine correct sequences for lane repair, impedance calibration, and training.  
- Debugged and resolved design issues through collaboration with designers.  

**Result:** Successfully implemented PHY initialization sequences, resolved critical bugs, and progressed to advanced training sequences as part of the ongoing project.

</details>


<details>
<summary><strong>✅ Functional Coverage Checkers Development for LPDDR54x</strong></summary>

**Organization:** Synopsys Inc | 📅 Duration: Apr 2024 – Present  
**Objective:** Develop a portable functional coverage checker for LPDDR54x interfaces, ensuring protocol compliance and scalability.  

**Contributions:**
- Implemented illegal bin coverage for LPDDR4 and LPDDR5, focusing on critical scenarios such as frequency changes, low power states, snooping, and sideband operations.  
- Developed a modular architecture using macros to support incremental updates and compatibility across DDR/LPDDR IPs, including LPDDR6.  
- Designed targeted negative test cases to ensure accurate detection of illegal conditions and enhance protocol compliance validation.  
- Currently working on extending coverage for additional scenarios as part of the ongoing project.  

**Result:** Delivered a scalable and reusable coverage checker, significantly improving verification efficiency for multiple DDR/LPDDR designs.

</details>



<details>
<summary><strong>✅ Functional Verification of OTP and Clock/Reset Modules in a USB PD Controller</strong></summary>

**Organization:** Texas Instruments  
**Objective:** Verify OTP operations and clock/reset functionalities in a USB Power Delivery (PD) controller to ensure compliance with design specifications.  

**Contributions:**
- Verified OTP operations, including read, burn, and standby, achieving comprehensive functional coverage.  
- Developed UVM testbench components and implemented SystemVerilog assertions for critical timing and state transitions.  
- Debugged clock/reset sequences for power-on reset (POR) and soft reset functionality, resolving design issues collaboratively with the design team.  

**Result:** Verified OTP and clock/reset functionalities, resolved design bugs, and achieved 100% functional coverage.

</details>



<details>
<summary><strong>✅ Functional Verification of Standard Bus Protocol IPs (APB, AHB, AXI, I2C, SPI, UART)</strong></summary>

**Organization:** Ulkasemi Internal  
**Objective:** Develop UVM-based environments to verify protocol-specific IPs.  

**Contributions:**
- Extracted design features from specifications and developed testbenches with protocol-specific agents, BFMs (drivers/monitors), test cases, assertions, and coverage plans.  
- Implemented constrained random testing and developed corner-case scenarios to validate all functional aspects.  
- Verified protocol sequences using SystemVerilog assertions for robustness and compliance.  

**Result:** Achieved 100% functional and code coverage, ensuring thorough protocol verification and compliance with design specifications.

</details>


### 💻 Digital Design and Functional Verification

<details>
<summary><strong>✅ RTL Design and Functional Verification of AHB to APB Bridge</strong></summary>

**Organization:** Ulkasemi Internal  
**Objective:** Design and verify an AHB to APB protocol bridge to enable communication between high-speed AHB and low-speed APB peripherals in SoC systems.  

**Contributions:**
- Developed RTL for AHB slave and APB master using Verilog, with control FSMs and asynchronous dual-clock FIFOs for CDC (400 MHz ↔ 100 MHz).  
- Built a UVM-based testbench with reusable agents, sequencers, monitors, and config classes.  
- Created directed and randomized tests for protocol correctness, invalid accesses, and transfer edge cases.  

**Result:** Verified protocol conversion and CDC logic via simulation; achieved full code and functional coverage.  
*Synthesis and timing closure were not within the scope of this project.*

</details>



<details>
<summary><strong>✅ RTL Design and Functional Verification of Foundational Digital Modules (Traffic Light Controller, 4-bit Binary Counter, and Universal Shift Register)</strong></summary>

**Organization:** Ulkasemi Internal  
**Objective:** Design and verify sequential digital modules using Verilog and SystemVerilog.  

**Contributions:**
- Designed synthesizable RTL for a binary counter, shift register, and FSM-based traffic light controller.  
- Built modular testbenches with reusable components; verified functionality using directed and randomized tests with full coverage.  

**Result:** Completed RTL design and functional verification of all modules, reinforcing skills in FSM design, RTL coding, and SV-based verification.

</details>


### 🎛️ Mixed-Signal Modeling & AMS Verification

<details>
<summary><strong>✅ Development and Integration of DMS Models and Testbench for SoC Verification</strong></summary>

**Organization:** Designer’s Guide  
**Objective:** Develop and integrate DMS models for analog-digital co-simulation.  

**Contributions:**
- Built discrete mixed-signal (DMS) models for blocks such as PLL, PMIC, and data converters using Real-Number Modeling (RNM) and User-Defined Nettypes (UDN).  
- Validated analog models against schematics using Verilog-AMS testbenches to ensure functional accuracy.  
- Integrated DMS models into a UVM-based testbench for seamless analog-digital verification.  

**Result:** Delivered validated DMS models and reduced simulation time by 90%, enabling efficient co-simulation and verification.  
Recognized for contributions in the paper "**Advanced UVM-Based Chip Verification Methodologies with Full Analog Functionality.**"

</details>



<details>
<summary><strong>✅ Behavioral Modeling and AMS Verification of SoC Subsystems</strong></summary>

**Organizations:** SigmaSense, ETA Wireless  
**Objective:** To develop and verify analog IPs in a touch controller and a wireless baseband generator using Real-Number Modeling and Verilog-AMS, enabling efficient mixed-signal simulation and seamless integration in SoC subsystems.  

**Contributions:**
- Developed behavioral models for a wide range of analog components—including Power-on Reset (POR), Thermal Shutdown Detect (TSD), Ultra-Low Voltage Detect (UVLO), Bias Circuits, LDO, Bandgap Reference (BGR), Data Converters, Oscillators, and Clock Generators using SystemVerilog RNM and Verilog-AMS.  
- Created self-checking Verilog-AMS testbenches to validate model behavior against design specifications and schematic functionality.  
- Verified power-up sequences and ensured functional accuracy through mixed-signal co-simulation, enabling seamless SoC subsystem integration.  

**Result:** Delivered validated RNM models, Verilog-AMS testbenches, and verified schematics, ensuring accurate digital-analog integration, improved AMS verification coverage, and significantly reduced simulation time.

</details>


### 🧠 Applied Machine Learning & Computer Vision

<details>
<summary><strong>🎯 Crowd Density Monitoring for COVID-Aware Navigation Using YOLOv4-Based Real-Time Object Detection (Undergrad Capstone Project)</strong></summary>

**Organization:** Ahsanullah University of Science and Technology  
**Objective:** Develop a real-time people detection system using YOLOv4 to monitor crowd density in public spaces and promote safer navigation during the COVID-19 pandemic.  

**Contributions:**
- Trained and optimized a YOLOv4-based deep learning model to detect individuals in video streams.  
- Integrated the detection system into a web-based interface for real-time visualization of crowd density.  
- Implemented a pipeline for data acquisition, model inference, and user-facing visualization to support social distancing.  

**Result:** Delivered a fully functional prototype combining deep learning, computer vision, and full-stack web integration, gaining hands-on experience in end-to-end AI system deployment.

</details>



<details>
<summary><strong>🎯 Predictive Modelling Using Supervised Learning Techniques</strong></summary>

**Organization:** Quantum.AI, BD  
**Objective:** Apply supervised machine learning algorithms to solve regression and classification problems using real-world datasets.  

**Contributions:**
- Preprocessed and analyzed datasets (bike sharing, Titanic) using Pandas and Seaborn.  
- Built regression and classification models (Linear/Logistic Regression, Random Forest, KNN) with Scikit-learn.  
- Evaluated performance with RMSE, R², Accuracy, and visualized model behavior.  

**Result:** Developed validated ML models and demonstrated end-to-end workflows from data processing to evaluation.

</details>

---

## 🛠️ Technical Skills

<details>
<summary>🧪 <strong>Functional Verification</strong></summary>

- Constraint Random Testbenches  
- Coverage-Driven Verification  
- Assertion-Based Verification (ABV)  
- Co-Simulation  
- Gate-Level Simulation (GLS)  
- Behavioral & Real-Number Modeling (RNM)  
- Mixed-Signal Verification  

</details>

<details>
<summary>🔧 <strong>RTL Design</strong></summary>

- FSM Design  
- Sequential & Combinational Logic Design  
- High-Level Synthesis (HLS)  

</details>

<details>
<summary>🧰 <strong>EDA Tools</strong></summary>

- Cadence (Xcelium, Virtuoso, IMC, vManager)  
- Synopsys (Verdi, VCS)  
- Xilinx (Vivado, Vitis-HLS)  

</details>

<details>
<summary>📡 <strong>Protocols & Interfaces</strong></summary>

- AMBA (APB, AHB, AXI)  
- SPI, I2C, UART  
- DFI, DDR, HBM4 PHY  

</details>

<details>
<summary>💻 <strong>Hardware Description Languages</strong></summary>

- Verilog  
- SystemVerilog  
- SystemVerilog Assertions (SVA)  
- Verilog-AMS  
- UVM  

</details>

<details>
<summary>💡 <strong>Programming & Scripting</strong></summary>

- C++  
- Python  
- Bash  

</details>

<details>
<summary>🤖 <strong>ML & Computer Vision</strong></summary>

- Supervised Learning  
- Neural Networks  
- CNNs (YOLO)  
- Scikit-learn, Matplotlib, Seaborn  

</details>

<details>
<summary>📁 <strong>Version Control & Collaboration</strong></summary>

- Git, Perforce  
- JIRA, Confluence  

</details>


---

## 🧾 Certifications

<details>
<summary><strong>🎓 High-Level Synthesis for FPGA, Logic Design with Vitis-HLS</strong></summary>

*Udemy, 2024* | [Combinational Circuits Certificate](#) | [Sequential Circuits Certificate](#)  
- Gained expertise in designing, debugging, and implementing combinational and sequential circuits on FPGAs using C++.  
- Utilized Xilinx Vitis-HLS and Vivado to generate RTL IPs, develop C-based testbenches, and simulate designs for functional verification.  

</details>

<details>
<summary><strong>🤖 Neural Networks and Deep Learning</strong></summary>

*DeepLearning.AI on Coursera, Sept 2020* | [Certificate](#)  
- Covered deep learning fundamentals, artificial neural networks, backpropagation, and network architectures.  

</details>

<details>
<summary><strong>📊 Data Science with Python</strong></summary>

*Quantum.ai, Bangladesh, June 2021* | [Certificate](#)  
- Explored Python programming, statistics, web scraping, data preprocessing, analysis, and supervised machine learning.  

</details>


---

## 👨‍🏫 Mentorship & Training

<details>
<summary><strong>🧑‍🏫 Instructor – VLSI Training Academy</strong></summary>

*United International University, Dhaka, Bangladesh*  
- Conducted training on HDL, SystemVerilog, and Verilog.  
- Taught RTL design flow covering synthesis, simulation, and verification.  
- Guided students in testbench development and adoption of industry-standard VLSI methodologies.  

</details>

<details>
<summary><strong>🛠️ Technical Recruitment & Training</strong></summary>

*Ulkasemi Private Limited, Dhaka, Bangladesh*  
- Developed recruitment assessments and led technical interviews on SystemVerilog, RTL design, and VLSI fundamentals.  
- Conducted structured onboarding sessions covering HDL, testbench development, and verification flows.  

</details>


---

## 🌐 Language Proficiency

- **IELTS (Dec 01, 2024)**  
  🟢 **Overall Band Score:** 7.5  
  📖 **Reading:** 8 🎧 **Listening:** 8 ✍️ **Writing:** 7 🗣️ **Speaking:** 6.5








