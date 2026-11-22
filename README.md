# VLSI_design_EEM614

<p align="center">
  <b>B.Tech – Electrical Engineering (Electronics Specialization)</b><br>
  <b>6th Semester | VLSI Laboratory</b>
</p>

---

## 📌 About This Repository

This repository contains the laboratory experiments, circuit designs, simulation files, observations, and project work completed as part of the **VLSI Laboratory (EEM614)** course during the 6th semester of B.Tech.

The primary objective of this laboratory is to develop practical understanding of Very Large Scale Integration (VLSI) design, CMOS technology, semiconductor device characteristics, digital logic circuits, sequential circuits, and performance analysis through circuit design and simulation.

The repository includes experiment-wise PDF documentation, LTspice circuit files (`.asc`), simulation waveforms, analysis, and a separate laboratory project involving CMOS ring oscillators across different technology nodes.

## 🎯 Course Objectives

- Understand the fundamentals of CMOS technology and VLSI design.
- Study NMOS and CMOS inverter characteristics.
- Analyze the effect of technology scaling on circuit performance.
- Design and simulate CMOS combinational logic gates.
- Understand pass-transistor logic and transmission gate circuits.
- Analyze power consumption and propagation delay.
- Study CMOS ring oscillators and frequency characteristics.
- Understand Schmitt triggers and hysteresis behaviour.
- Design and analyze sequential circuits such as latches and flip-flops.
- Evaluate the relationship between power, delay, and technology scaling.

---

## 📚 Experiments

### Experiment No. 01 – NMOS Inverter with Resistive Load Using CD4007

**Objective:** Study the NMOS inverter with a resistive load ranging from 100 Ω to 33 kΩ.

**Topics Covered:**
- NMOS Resistive Load Inverter
- DC Analysis
- Transient Analysis
- Output Characteristics
- Effect of Load Resistance
- Rise Time and Propagation Delay
- Noise Margin Analysis
- Dynamic Power Dissipation
- Effect of Load Capacitance

### Experiment No. 02 – CMOS Inverter Performance Comparison at 180 nm and 90 nm

**Objective:** Compare the performance of CMOS inverters at 180 nm and 90 nm bulk CMOS technology nodes.

**Topics Covered:**
- CMOS Inverter Design
- 180 nm Technology Node
- 90 nm Technology Node
- Voltage Transfer Characteristics
- Transient Response
- Propagation Delay
- Rise Time and Fall Time
- Static Power Dissipation
- Dynamic Power Dissipation
- Technology Scaling and Performance Comparison

### Experiment No. 03 – Design and Analysis of 2-Input CMOS NAND Gate

**Objective:** Design a 2-input CMOS NAND gate at the 180 nm technology node and perform static and dynamic analysis for different input patterns.

**Topics Covered:**
- CMOS NAND Gate Design
- 180 nm Technology Node
- Static Analysis
- Voltage Transfer Characteristics (VTC)
- Static Power Dissipation
- Dynamic Analysis
- Dynamic Power Dissipation
- Propagation Delay
- Effect of Load Capacitance (40 fF and 80 fF)

### Experiment No. 04 – Design and Analysis of 2-Input CMOS NOR Gate

**Objective:** Design a 2-input CMOS NOR gate at the 180 nm technology node and perform complete static and dynamic analysis.

**Topics Covered:**
- CMOS NOR Gate Design
- 180 nm Technology Node
- Static Analysis
- Voltage Transfer Characteristics
- Static Power Dissipation
- Dynamic Power Dissipation
- Propagation Delay
- Effect of Load Capacitance (40 fF and 80 fF)
- Switching Behaviour

### Experiment No. 05 – Pass-Transistor AND Gate Using CD4007 and 180 nm Technology

**Objective:** Obtain the Voltage Transfer Characteristics (VTC) of a pass-transistor AND gate and analyze power consumption using CD4007 and 180 nm technology.

**Topics Covered:**
- Pass-Transistor Logic
- AND Gate Design
- CD4007 Implementation
- 180 nm CMOS Implementation
- Different Input Patterns
- Voltage Transfer Characteristics
- Threshold Voltage Degradation
- Power Consumption
- Technology-Based Performance Comparison

### Experiment No. 06 – Design and Analysis of 2-Input XOR Gates

**Objective:** Design pass-transistor-based and transmission-gate-based 2-input XOR gates and analyze their dynamic behaviour.

**Topics Covered:**
- Pass-Transistor-Based XOR Gate
- Transmission-Gate-Based XOR Gate
- CMOS Logic Design
- Transient Analysis
- Dynamic Power Dissipation
- Output Voltage Swing
- Threshold Voltage Degradation
- Comparison of Circuit Implementations
- Area and Power Considerations

### Experiment No. 07 – CMOS Inverter and 3-Stage Ring Oscillator Using CD4007

**Objective:**
1. Realize a CMOS inverter using CD4007 IC and perform transient analysis with and without load at different input frequencies.
2. Realize a 3-stage CMOS ring oscillator and calculate its oscillation frequency.

**Topics Covered:**
- CD4007 CMOS Inverter
- Loaded and Unloaded Inverter
- Transient Analysis
- Input Frequency Variation
- Rise Time and Fall Time
- Propagation Delay
- 3-Stage CMOS Ring Oscillator
- Feedback-Based Oscillation
- Oscillation Frequency Measurement

**Observed Oscillation Frequency:** 1.069 MHz

### Experiment No. 09 – Design and Analysis of Schmitt Trigger Using CD4007

**Objective:** Simulate and realize a Schmitt trigger using CD4007 IC, convert random input signals into pulses, and study different threshold voltages and hysteresis loop widths through transistor sizing.

**Topics Covered:**
- Schmitt Trigger Design
- CD4007 CMOS Implementation
- Positive Feedback
- Upper and Lower Threshold Voltages
- Hysteresis Characteristics
- Hysteresis Loop Width
- Transistor Sizing
- Input and Output Waveform Analysis
- Noise Immunity
- Signal Conditioning

### Experiment No. 10 – Design and Analysis of D-Latch and Positive Edge-Triggered D Flip-Flop

**Objective:** Design a one-bit D-Latch and positive edge-triggered D Flip-Flop using CD4007 and 180 nm technology.

**Topics Covered:**
- D-Latch Design
- CD4007 Implementation
- 180 nm CMOS Implementation
- Level-Sensitive Operation
- Positive Edge-Triggered D Flip-Flop
- Clock and Data Signals
- Sequential Circuit Design
- Transient Analysis
- Output Waveform Analysis
- Comparison of Different Technology Implementations

---

## 🔬 Laboratory Project (Lab PT Project)

### Design and Performance Analysis of 3-Stage and 5-Stage CMOS Ring Oscillators

**Objective:** Design 3-stage and 5-stage CMOS ring oscillators at 90 nm, 45 nm, and 22 nm technology nodes using a constant supply voltage of 1 V, and investigate their performance.

**Topics Covered:**

**Part 1 – Technology Scaling Analysis**
- 3-Stage CMOS Ring Oscillator
- 5-Stage CMOS Ring Oscillator
- 90 nm, 45 nm and 22 nm Technology Nodes
- Oscillation Frequency Measurement
- Propagation Delay vs. Channel Length
- Power-Delay Product (PDP)
- Comparison of Oscillator Configurations

**Part 2 – Supply Voltage Analysis**
- 5-Stage Ring Oscillator at 90 nm
- Supply Voltage Variation: 1 V, 1.5 V, 2 V and 2.5 V
- Propagation Delay vs. VDD
- Gate Power-Delay Product vs. VDD
- Frequency and Power Behaviour
- Supply Voltage and Performance Trade-offs

**Project Analysis:**
- Comparison of 3-stage and 5-stage oscillator performance.
- Effect of technology scaling on propagation delay and oscillation frequency.
- Effect of supply voltage on switching speed and power consumption.
- Evaluation of power-delay product across different operating conditions.

---

## 🛠️ Tools and Technologies

- **LTspice** – Circuit design, simulation and waveform analysis.
- **CD4007 CMOS IC** – Practical CMOS circuit implementation.
- **180 nm / 90 nm / 45 nm / 22 nm Technology Nodes** – CMOS technology analysis.
- **PDF Documentation** – Experiment reports and project documentation.
- **Simulation Files (.asc)** – LTspice circuit schematics.

## 📁 Repository Structure

```text
 VLSI_design_EEM614/
│
├── Experiment No. 01/
│   ├── Experiment Report.pdf
│   └── NMOS Resistive Inverter.asc
│
├── Experiment No. 02/
│   ├── Experiment Report.pdf
│   ├── CMOS Inverter 180nm.asc
│   └── CMOS Inverter 90nm.asc
│
├── Experiment No. 03/
│   ├── Experiment Report.pdf
│   └── NAND GATE CMOS.asc
│
├── Experiment No. 04/
│   ├── Experiment Report.pdf
│   └── CMOS NOR GATE.asc
│
├── Experiment No. 05/
│   ├── Experiment Report.pdf
│   └── Pass Transistor AND Gate.asc
│
├── Experiment No. 06/
│   ├── Experiment Report.pdf
│   ├── Pass Transistor XOR.asc
│   └── Transmission Gate XOR.asc
│
├── Experiment No. 07/
│   ├── Experiment Report.pdf
│   ├── CD4007 CMOS Inverter.asc
│   └── 3-Stage Ring Oscillator.asc
│
├── Experiment No. 08/
│   └── (No separate individual experiment folder in the supplied archive)
│
├── Experiment No. 09/
│   ├── Experiment Report.pdf
│   └── Schmitt Trigger Using CD4007.asc
│
├── Experiment No. 10/
│   ├── Experiment Report.pdf
│   ├── CD4007 D Latch.asc
│   ├── 180nm D Latch.asc
│   └── D FF.asc
│
├── Lab PT Project/
│   ├── Project Report.pdf
│   ├── Three Stage CMOS Ring Oscillator.asc
│   └── Five Stage CMOS Ring Oscillator.asc
│
├── Complete Lab Record/
│   └── Complete Lab Record.pdf
│
└── README.md
```

*Note: The above is a recommended logical structure. Actual filenames may differ. Experiment numbering in the complete lab record differs from the individual experiment folders for the Schmitt Trigger and D-Latch/D-FF experiments.*

## 📖 Learning Outcomes

Through these experiments and project work, practical understanding was developed in:

- CMOS inverter design and semiconductor device behaviour.
- Static and dynamic characteristics of CMOS logic gates.
- Technology scaling and its impact on circuit performance.
- Power consumption and propagation delay analysis.
- Pass-transistor and transmission-gate logic.
- CMOS ring oscillator design and frequency analysis.
- Schmitt trigger operation and hysteresis characteristics.
- Sequential circuit design using latches and flip-flops.
- Performance evaluation using power-delay product.
- LTspice-based circuit simulation and waveform interpretation.

## 👨‍🎓 Student Information

| Detail | Information |
|---|---|
| Name | Shubham Mahor |
| Roll Number | 2104690 |
| Branch | Electrical Engineering (Electronics) |
| Semester | 6th Semester |
| Batch | 2023-2027 |
| Course Code | EEM614 |
| Course | VLSI Laboratory |
| Institute | Dayalbagh Educational Institute, Agra |

---

## ⚠️ Disclaimer

This repository is maintained for academic and educational purposes. The circuit designs, simulation files, observations, and reports are part of laboratory coursework and project activities.

Simulation results may vary depending on transistor models, technology parameters, circuit configurations, supply voltage, load conditions, and simulation settings.

---

<p align="center">
  <b>VLSI Laboratory | EEM614</b><br>
  <i>Exploring CMOS Design, Technology Scaling and Digital Circuit Performance.</i>
</p>
