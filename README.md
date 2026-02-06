# 30-60 GHz Ultra-Wideband Vivaldi Antenna Design

This repository contains the design and simulation files for an ultra-wideband (UWB) Vivaldi antenna, developed using **CST Studio Suite 2025**. The antenna is specifically optimized for millimeter-wave (mmWave) applications, covering the 30-60 GHz frequency range.

## 🚀 Project Overview
Vivaldi antennas (Tapered Slot Antennas) are known for their high gain and stable radiation patterns over a very wide bandwidth. This project focuses on a microstrip-fed Vivaldi structure designed on a high-frequency substrate to achieve high efficiency in the Ka and V bands.

### Technical Specifications
* **Frequency Range:** 30 GHz - 60 GHz
* **Substrate:** Taconic RF-60A (lossy)
    * **Permittivity ($\epsilon_r$):** 6.15
    * **Loss Tangent ($\tan \delta$):** 0.0028
    * **Thickness:** 0.2 mm
* **Feed Mechanism:** Microstrip line transition to exponential taper.
* **Mesh Count:** ~13,440 cells (Optimized for accuracy/speed).

## 📊 Simulation Results

### S-Parameters ($S_{11}$)
The antenna shows excellent impedance matching, particularly in the lower end of the band (30-34 GHz) with $S_{11}$ levels dropping below -40 dB, and a resonance point near 48 GHz.


### Design Geometry
The exponential taper was carefully parameterized to ensure a smooth impedance transition from the microstrip feed to free space.


## 🛠 Features
* **Parametric Design:** All dimensions (length, width, slot rate) are defined as variables for easy optimization.
* **High-Frequency Performance:** Specialized substrate selection for minimal dielectric loss at mmWave frequencies.
* **Ready-to-Simulate:** CST project file included with pre-configured solver settings and field monitors.






