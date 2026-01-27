# 30-60 GHz Wideband Vivaldi Antenna Design

This repository contains the design, modeling, and simulation results of a wideband Vivaldi antenna, developed using **CST Studio Suite 2025**. [cite_start]The design is optimized for mmWave (millimeter-wave) frequency bands, specifically targeting high-performance communication systems. [cite: 81]

## Technical Overview
[cite_start]The antenna is designed on a substrate with a dielectric constant of **4.1** and a thickness of **0.2 mm**. [cite: 1, 6] [cite_start]The design utilizes exponential tapering to achieve wideband impedance matching across the 30-60 GHz spectrum. [cite: 1, 15]

### Key Parameters (Parameter List)
[cite_start]The design is fully parameterized to allow for easy optimization: [cite: 1, 80]
* [cite_start]**subw (Substrate Width):** 3 mm [cite: 1]
* [cite_start]**sL (Slot Length):** 1 mm [cite: 1]
* [cite_start]**h (Substrate Thickness):** 0.2 mm [cite: 1]
* [cite_start]**k (Dielectric Constant):** 4.1 [cite: 1]
* [cite_start]**Frequency Range:** 30 GHz to 60 GHz [cite: 15]

## Simulation Results
[cite_start]The simulation was performed using the **Transient Solver** in CST Studio Suite. [cite: 1]

### S-Parameters (Return Loss)
[cite_start]The $S_{1,1}$ results demonstrate: [cite: 15]
* [cite_start]Strong impedance matching (below -10 dB) across the primary operating band. [cite: 15]
* [cite_start]A significant resonance peak observed at approximately **48.7 GHz** with a return loss better than -20 dB. [cite: 15]
* [cite_start]Broadband characteristics suitable for 5G and radar applications. [cite: 15]

*(Note: You can insert your screenshots here using the following syntax after uploading them to the 'media' folder)*
![S-Parameter Plot](media/s_parameter_plot.png)

## Repository Structure
* [cite_start]`vivaldiantenna.cst`: The main project file (CST Studio Suite 2025). [cite: 81]
* `/media`: Contains screenshots of the 3D model and S-parameter plots.
* [cite_start]`.gitignore`: Configured to exclude heavy simulation data (ModelCache, Result folders). [cite: 80]

## How to Run
1. Clone the repository.
2. [cite_start]Open `vivaldiantenna.cst` with **CST Studio Suite 2025** or later. [cite: 81]
3. [cite_start]Run the **Transient Solver** to recalculate the results if necessary. [cite: 1]
