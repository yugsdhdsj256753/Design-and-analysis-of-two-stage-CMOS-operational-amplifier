# Design and Analysis of Two-Stage CMOS Operational Amplifier

This project presents the design and analysis of a **two-stage CMOS
operational amplifier** using **UMC 180 nm CMOS technology** in
**Cadence Virtuoso**.

## Project Specifications

| Parameter | Specification |
|---|---:|
| **Technology** | UMC 180 nm CMOS |
| **EDA Tool** | Cadence Virtuoso |
| **Supply Voltage** | 1.8 V |
| **Gain** | 1000 V/V (60 dB) target |
| **Gain Bandwidth Product (GBW)** | 30 MHz |
| **Slew Rate** | 20 V/µs |
| **Input Common-Mode Range (ICMR)** | 0.8 V – 1.6 V |
| **Power Consumption** | < 0.3 mW |
| **Load Capacitance** | 2 pF |
| **Phase Margin** | ≥ 60° |

## Design Approach

The operational amplifier was designed at the transistor level using
NMOS and PMOS devices. The design involved transistor sizing,
bias-current calculation, compensation capacitor selection, and analysis
of the input common-mode range and phase-margin requirements.


The circuit was evaluated using DC, AC, transient, pole-zero, and noise
analyses in Cadence Virtuoso. The final transistor dimensions were
selected based on the calculated bias currents, transconductance
requirements, and current-mirror ratios.

## Circuit Diagram

The two-stage operational amplifier consists of a differential input
stage, active load/current mirror, second gain stage, and compensation capacitor.
<img width="622" height="429" alt="image" src="https://github.com/user-attachments/assets/98d726aa-b3b2-4ce0-99f0-70eb54459aa5" />

## Analyses Performed

-   DC operating-point analysis
-   AC gain and phase analysis
-   Transient analysis
-   Pole-zero analysis

## Simulation Results
<h3>Schematic for Two stage Opamp</h3>
<img width="1619" height="766" alt="twostageopamp schematic" src="https://github.com/user-attachments/assets/24ffbddc-2997-442c-a1b5-6f905993eedd" />


### Pole Zero Analysis
<img width="1439" height="649" alt="twostageopamp polezero analysis" src="https://github.com/user-attachments/assets/33a18eda-2edc-47fd-8bdb-a3f5d46f03c5" />

<br><br><br>
<h3>DC Operating Point</h3>
<img width="1605" height="747" alt="dc op" src="https://github.com/user-attachments/assets/bcc6059a-7705-4932-aa7d-27e4cb66f644" />
<br><br>
<h3>Phase and Magnitude(with 400 fF) Plot</h3>
<img width="1567" height="799" alt="twostageopamp gain and phase with compensation" src="https://github.com/user-attachments/assets/16ec138b-83e9-4912-904a-a2faea42a3b5" />
<h3>Phase and Magnitude(with 600 fF) Plot</h3>
<img width="1595" height="795" alt="Screenshot 2026-08-24 210826" src="https://github.com/user-attachments/assets/d21f2688-7c69-4993-abb2-bf2752a8f414" />

<br><br>
<h3>Transient Response analysis</h3>
<img width="1745" height="778" alt="twostageopamp transient analysis" src="https://github.com/user-attachments/assets/cf080b09-0cb0-4fa6-970e-4acfafffc3f8" />


<br><br>
The simulated circuit achieved the following measured results:



-   **Maximum Gain:** approximately 58 dB
-   **Gain Bandwidth Product:** 27.13 MHz
-   **3-dB Frequency:** 38.19 kHz
-   **Transient Output:** approximately 8.7 mV peak-to-peak
-   **Transient Input:** approximately 9.9 µV peak-to-peak

## Final Results
| Parameter | Target | Achieved |
|---|---:|---:|
| **Supply Voltage** | 1.8 V | 1.8 V |
| **Gain** | 1000 V/V (60 dB) | ~58 dB |
| **Gain Bandwidth Product (GBW)** | 30 MHz | 27.13 MHz |
| **Slew Rate** | 20 V/µs | Not reported |
| **Input Common-Mode Range (ICMR)** | 0.8 V – 1.6 V | Not reported |
| **Power Consumption** | < 0.3 mW | Not reported |
| **Load Capacitance** | 2 pF | 2 pF |
| **Phase Margin** | ≥ 60° | 70° |


## Tools

- **Cadence Virtuoso \| Cadence Spectre \| UMC 180 nm PDK**

## Key Skills Demonstrated

- **Analog IC Design \| CMOS Circuit Design \| MOSFET Biasing \|
Transistor Sizing \| Operational Amplifier Design \| Frequency Response
Analysis \| Stability Analysis \| Cadence Virtuoso**

## Future Work
- Design and implement the analog layout of the proposed two-stage op-amp using Cadence Virtuoso.
- Perform DRC and LVS verification to ensure layout correctness.
- Extract parasitic components and perform post-layout simulation.
## Contributors

- **Yuvaraj Dhayal D** | **MTech VLSI Design at VIT Vellore** 
