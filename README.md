# Uchchhash Sarkar

📍 Sector 14, Uttara, Dhaka 1230, Bangladesh  
📞 +8801778944122  
📧 uchchhash.sarkar@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/uchchhash) 
🔗 [GitHub](https://github.com/uchchhash)
🔗 [ResearchGate](https://www.researchgate.net/profile/Uchchhash_Sarkar)


## 🎓 Academic Credentials

**Bachelor of Science (B.Sc.) in Electrical and Electronic Engineering**  
*Ahsanullah University of Science and Technology (AUST), Dhaka, Bangladesh*  
📅 **Duration:** Nov 2016 – Aug 2021  
📊 **CGPA:** 3.584 / 4.00  
📈 **Last Four Semesters:** 3.854 / 4.00 

**Relevant Coursework & Labs:**  
- VLSI I & Lab – A+, A+ (4.00)  
- VLSI II & Lab – A+, A+ (4.00)  
- Computer Architecture – A+ (4.00)  
- Microprocessor & System Design & Lab – A+, A+ (4.00)  
- Digital Logic Design – A+ (4.00)  
- Digital Signal Processing I & Lab – A+, A+ (4.00)  
- Analog Integrated Circuit – A (3.75)
- Project & Thesis - A+ (4.00)


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


## 📄 Publication

**Noman, M. A. N., Majumder, P., Sarkar, U., & Karmaker, S.** (2023).  
*Optimizing Threshold Voltage Performance in AlGaN/GaN MIS-HEMTs through GaON Integration*.  
Presented at the **9th IEEE International Women in Engineering (WIE) Conference on Electrical and Computer Engineering (WIECON-ECE)**.  
🔗 [View on IEEE Xplore](https://ieeexplore.ieee.org/document/10456403)


## 🧪 Selected Projects

---

### 🔌 High-Speed Interface and Protocol Verification

#### ✅ Functional Verification of HBM4 PHY Layer  
**Organization:** Synopsys Inc | 📅 Duration: Jun 2024 – Present  
**Objective:** Implement and verify HBM4 PHY initialization and training sequences for mission mode readiness.  
**Contributions:**
- Implemented key initialization steps, including power-up, clock setup, CSR configuration, and PHY initialization.  
- Analyzed specifications to determine correct sequences for lane repair, impedance calibration, and training.  
- Debugged and resolved design issues through collaboration with designers.  
**Result:** Successfully implemented PHY initialization sequences, resolved critical bugs, and progressed to advanced training sequences as part of the ongoing project.

#### ✅ Functional Coverage Checkers Development for LPDDR54x  
**Organization:** Synopsys Inc | 📅 Duration: Apr 2024 – Present  
**Objective:** Develop a portable functional coverage checker for LPDDR54x interfaces, ensuring protocol compliance and scalability.  
**Contributions:**
- Implemented illegal bin coverage for LPDDR4 and LPDDR5, focusing on critical scenarios such as frequency changes, low power states, snooping, and sideband operations.
- Developed a modular architecture using macros to support incremental updates and compatibility across DDR/LPDDR IPs, including LPDDR6.
- Designed targeted negative test cases to ensure accurate detection of illegal conditions and enhance protocol compliance validation.
- Currently working on extending coverage for additional scenarios as part of the ongoing project.
**Result:** Delivered a scalable and reusable coverage checker, significantly improving verification efficiency for multiple DDR/LPDDR designs.

#### ✅ Functional Verification of OTP and Clock/Reset Modules in a USB PD Controller  
**Organization:** Texas Instruments
**Objective:** Verify OTP operations and clock/reset functionalities in a USB Power Delivery (PD) controller to ensure compliance with design specifications.  
**Contributions:**
- Verified OTP operations, including read, burn, and standby, achieving comprehensive functional coverage.
- Developed UVM testbench components and implemented SystemVerilog assertions for critical timing and state transitions.
- Debugged clock/reset sequences for power-on reset (POR) and soft reset functionality, resolving design issues collaboratively with the design team.
**Result:** Verified OTP and clock/reset functionalities, resolved design bugs, and achieved 100% functional coverage.

#### ✅ Functional Verification of Standard Bus Protocol IPs (APB, AHB, AXI, I2C, SPI, UART)  
**Organization:** Ulkasemi Internal 
**Objective:** Develop UVM-based environments to verify protocol-specific IPs.  
**Contributions:**
- Extracted design features from specifications and developed testbenches with protocol-specific agents, BFMs (drivers/monitors), test cases, assertions, and coverage plans.
- Implemented constrained random testing and developed corner-case scenarios to validate all functional aspects.
- Verified protocol sequences using SystemVerilog assertions for robustness and compliance.
**Result:** Achieved 100% functional and code coverage, ensuring thorough protocol verification and compliance with design specifications.

---

### 💻 Digital Design and Functional Verification

#### ✅ RTL Design and Functional Verification of AHB to APB Bridge  
**Organization:** Ulkasemi Internal  
**Objective:** Design and verify an AHB to APB protocol bridge to enable communication between high-speed AHB and low-speed APB peripherals in SoC systems.  
**Contributions:**
- Developed RTL for AHB slave and APB master using Verilog, with control FSMs and asynchronous dual-clock FIFOs for CDC (400 MHz ↔ 100 MHz).
- Built a UVM-based testbench with reusable agents, sequencers, monitors, and config classes.
- Created directed and randomized tests for protocol correctness, invalid accesses, and transfer edge cases.
**Result:** Verified protocol conversion and CDC logic via simulation; achieved full code and functional coverage.. Synthesis and timing closure were not within the scope of this project.

#### ✅ RTL Design and Functional Verification of Foundational Digital Modules (Traffic Light Controller, 4-bit Binary Counter and Universal Shift Register)
**Organization:** Ulkasemi Internal 
**Objective:** Design and verify sequential digital modules using Verilog and SystemVerilog.  
**Contributions:**
- Designed synthesizable RTL for a binary counter, shift register, and FSM-based traffic light controller.
- Built modular testbenches with reusable components; verified functionality using directed and randomized tests with full coverage.
**Result:** Completed RTL design and functional verification of all modules, reinforcing skills in FSM design, RTL coding, and SV-based verification.

---

### 🎛️ Mixed-Signal Modeling & AMS Verification

#### ✅ Development and Integration of DMS Models and Testbench for SoC Verification  
**Organization:** Designer’s Guide 
**Objective:** Develop and integrate DMS models for analog-digital co-simulation.  
**Contributions:**
- Built discrete mixed-signal (DMS) models for blocks such as PLL, PMIC, and data converters using Real-Number Modeling (RNM) and User-Defined Nettypes (UDN).
- Validated analog models against schematics using Verilog-AMS testbenches to ensure functional accuracy.
- Integrated DMS models into a UVM-based testbench for seamless analog-digital verification.
**Result:** Delivered validated DMS models and reduced simulation time by 90%, enabling efficient co-simulation and verification. Recognized for contributions in the paper "**Advanced UVM-Based Chip Verification Methodologies with Full Analog Functionality.**"

#### ✅ Behavioral Modeling and AMS Verification of SoC Subsystems  
**Organizations:** SigmaSense, ETA Wireless 
**Objective:** To develop and verify analog IPs in a touch controller and a wireless baseband generator using Real-Number Modeling and Verilog-AMS, enabling efficient mixed-signal simulation and seamless integration in SoC subsystems. 
**Contributions:**
- Developed behavioral models for a wide range of analog components—including Power-on Reset (POR), Thermal Shutdown Detect (TSD), Ultra-Low Voltage Detect (UVLO), Bias Circuits, LDO, Bandgap Reference (BGR), Data Converters, Oscillators, and Clock Generators using SystemVerilog RNM and Verilog-AMS.
- Created self-checking Verilog-AMS testbenches to validate model behavior against design specifications and schematic functionality.
- Verified power-up sequences and ensured functional accuracy through mixed-signal co-simulation, enabling seamless SoC subsystem integration
**Result:** Delivered validated RNM models, Verilog-AMS testbenches, and verified schematics, ensuring accurate digital-analog integration, improved AMS verification coverage, and significantly reduced simulation time.

---

### 🧠 Applied Machine Learning & Computer Vision

#### 🎯 Crowd Density Monitoring for COVID-Aware Navigation Using YOLOv4-Based Real-Time Object Detection (Undergrad Capstone Project)  
**Organization:** Ahsanullah University of Science and Technology 
**Objective:** Develop a real-time people detection system using YOLOv4 to monitor crowd density in public spaces and promote safer navigation during the COVID-19 pandemic.  
**Contributions:**
- Trained and optimized a YOLOv4-based deep learning model to detect individuals in video streams.
- Integrated the detection system into a web-based interface for real-time visualization of crowd density.
- Implemented a pipeline for data acquisition, model inference, and user-facing visualization to support social distancing.
**Result:** Delivered a fully functional prototype combining deep learning, computer vision, and full-stack web integration, gaining hands-on experience in end-to-end AI system deployment.


#### 🎯 Predictive Modelling Using Supervised Learning Techniques  
**Organization:** Quantum.AI, BD
**Objective:** Apply supervised machine learning algorithms to solve regression and classification problems using real-world datasets.  
**Contributions:**
- Preprocessed and analyzed datasets (bike sharing, Titanic) using Pandas and Seaborn.
- Built regression and classification models (Linear/Logistic Regression, Random Forest, KNN) with Scikit-learn.
- Evaluated performance with RMSE, R², Accuracy, and visualized model behavior.
**Result:** Developed validated ML models and demonstrated end-to-end workflows from data processing to evaluation. 









