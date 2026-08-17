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
<img width="1629" height="762" alt="white sc" src="https://github.com/user-attachments/assets/c6a18b48-e556-4a6d-baa6-57adb6c8872f" />

### Pole Zero Analysis
<img width="1131" height="789" alt="pz" src="https://github.com/user-attachments/assets/ccf04acf-2c9d-4aa3-9d38-72e9ee964354" />
<br><br><br>
<h3>DC Operating Point</h3>
<img width="1605" height="747" alt="dc op" src="https://github.com/user-attachments/assets/bcc6059a-7705-4932-aa7d-27e4cb66f644" />
<br><br>
<h3>Phase and Magnitude Plot</h3>
<img width="1919" height="846" alt="db" src="https://github.com/user-attachments/assets/71eadbb0-c9b1-43c4-b3fe-8e2ce7a5be5b" />

<br><br>
<h3>Transient Response analysis</h3>
<img width="1388" height="714" alt="image" src="https://github.com/user-attachments/assets/b199f38a-951c-4b40-88fe-c6ce45f62e69" />
<br><br>
The simulated circuit achieved the following measured results:



-   **Maximum Gain:** approximately 74 dB
-   **0-dB Gain Crossover Frequency:** 7.5 MHz
-   **3-dB Frequency:** 1.5 kHz
-   **Transient Output:** approximately 41.7 mV peak-to-peak
-   **Transient Input:** approximately 21 µV peak-to-peak

The AC analysis plot shows the gain and phase response, while the
transient analysis verifies the time-domain response of the amplifier.




## Tools

- **Cadence Virtuoso \| Cadence Spectre \| UMC 180 nm PDK**

## Key Skills Demonstrated

- **Analog IC Design \| CMOS Circuit Design \| MOSFET Biasing \|
Transistor Sizing \| Operational Amplifier Design \| Frequency Response
Analysis \| Stability Analysis \| Cadence Virtuoso**

## Contributors

- **Yuvaraj Dhayal D** | **MTech VLSI Design at VIT Vellore** 
