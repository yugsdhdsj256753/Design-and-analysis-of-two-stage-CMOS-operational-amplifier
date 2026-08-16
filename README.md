# Design and Analysis of Two-Stage CMOS Operational Amplifier

This project presents the design and analysis of a **two-stage CMOS
operational amplifier** using **UMC 180 nm CMOS technology** in
**Cadence Virtuoso**.

## Project Specifications

-   **Technology:** UMC 180 nm CMOS
-   **EDA Tool:** Cadence Virtuoso
-   **Supply Voltage:** 1.8 V
-   **Gain:** 1000 V/V (60 dB) target
-   **Gain Bandwidth Product:** 30 MHz
-   **Slew Rate:** 20 V/µs
-   **Input Common-Mode Range:** 0.8 V to 1.6 V
-   **Power Consumption:** \< 0.3 mW
-   **Load Capacitance:** 2 pF
-   **Phase Margin:** ≥ 60°

## Design Approach

The operational amplifier was designed at the transistor level using
NMOS and PMOS devices. The design involved transistor sizing,
bias-current calculation, compensation capacitor selection, and analysis
of the input common-mode range and phase-margin requirements.

The circuit was evaluated using DC, AC, transient, pole-zero, and noise
analyses in Cadence Virtuoso. The final transistor dimensions were
selected based on the calculated bias currents, transconductance
requirements, and current-mirror ratios.

## Circuit

The two-stage operational amplifier consists of a differential input
stage, active load/current mirror, second gain stage, and compensation capacitor.
<img width="622" height="429" alt="image" src="https://github.com/user-attachments/assets/98d726aa-b3b2-4ce0-99f0-70eb54459aa5" />

## Analyses Performed

-   DC operating-point analysis
-   AC gain and phase analysis
-   Transient analysis
-   Pole-zero analysis
-   Noise analysis

## Simulation Results
<img width="1401" height="706" alt="image" src="https://github.com/user-attachments/assets/7a39710f-4e4a-471d-aa21-bb6b584305e7" />

<img width="1375" height="638" alt="image" src="https://github.com/user-attachments/assets/572960c7-f6d6-4fef-8313-33c39ce9ed13" />

<img width="1388" height="714" alt="image" src="https://github.com/user-attachments/assets/b199f38a-951c-4b40-88fe-c6ce45f62e69" />

The simulated circuit achieved the following measured results:



-   **Maximum Gain:** approximately 68 dB
-   **0-dB Gain Crossover Frequency:** 16.20 MHz
-   **3-dB Frequency:** 9.38 kHz
-   **Transient Output:** approximately 41.7 mV peak-to-peak
-   **Transient Input:** approximately 21 µV peak-to-peak

The AC analysis plot shows the gain and phase response, while the
transient analysis verifies the time-domain response of the amplifier.




## Tools

**Cadence Virtuoso \| Cadence Spectre \| UMC 180 nm PDK**

## Key Skills Demonstrated

**Analog IC Design \| CMOS Circuit Design \| MOSFET Biasing \|
Transistor Sizing \| Operational Amplifier Design \| Frequency Response
Analysis \| Stability Analysis \| Cadence Virtuoso**
