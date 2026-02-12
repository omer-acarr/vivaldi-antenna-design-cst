# 📡 mmWave Vivaldi Antenna Design & Optimization (40-60 GHz)

This repository showcases a professional electromagnetic simulation project featuring a high-performance **Vivaldi (Tapered Slot) Antenna**. Designed for the millimeter-wave (mmWave) spectrum, the project was developed and analyzed using **CST Studio Suite 2025**.

## 📝 Description
The project focuses on the engineering transition from a standard transmission line to a directive radiating element on a high-dielectric substrate. The primary objective was to optimize the antenna geometry to achieve stable radiation characteristics and impedance matching at **48.7 GHz**. The design utilizes a microstrip-to-slotline transition, leveraging the **Taconic RF-60A** substrate for its stability in high-frequency applications.

Key milestones achieved in this project include:
* Successful elimination of background PEC errors to enable Farfield analysis.
* Parametric optimization of the exponential taper (k-factor) and flare aperture.
* Correlation of E-Field distribution with physical radiation mechanisms.

---

## 🛠 Technical Specifications
* **Substrate:** Taconic RF-60A (Lossy)
    * **Relative Permittivity ($\epsilon_r$):** 6.15
    * **Thickness (h):** 0.2 mm
* **Design Frequency:** 48.7 GHz (Center)
* **Operational Band:** 30 GHz - 60 GHz
* **Solver:** Transient (Time Domain) Solver



## 📐 Optimized Parameters
| Parameter | Value | Description |
| :--- | :--- | :--- |
| **subw** | 8.0 mm | Substrate Width (Aperture size) |
| **sL** | 12.0 mm | Substrate Length (Directional focus) |
| **k** | 0.3 | Exponential Taper Factor |
| **MW** | 0.30 mm | Microstrip Width (50 Ohm Matching) |

---

## 📊 Simulation Highlights

### 🔹 S-Parameters (Return Loss)
The optimized design demonstrates multiple resonance points, achieving an S11 value below **-10 dB** throughout the 30-45 GHz band. This confirms efficient power delivery to the radiating aperture.
* **Peak Performance:** -13.2 dB at ~44 GHz.



### 🔹 Farfield & Radiation Patterns
The Farfield analysis confirms an **End-fire** radiation pattern, crucial for directional communication.
* **Directivity:** 4.908 dBi
* **Main Lobe Direction:** 88.0°
* **Angular Width (3 dB):** 89.0°
* **Side Lobe Level:** -4.7 dB



### 🔹 E-Field Visualization
E-Field monitors at 40 GHz and 45 GHz verify the coupling mechanism where energy is guided through the tapered slot and radiated into free space.

