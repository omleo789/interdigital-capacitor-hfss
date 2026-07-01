# 4-Layer Interdigital Capacitor (IDC)

A four-layer Interdigital Capacitor (IDC) designed and simulated using **Ansys HFSS** for high-performance capacitive applications. The project investigates the electrical characteristics of a multilayer IDC structure, including capacitance and quality factor over a range of frequencies.

---

## Project Information

- **Project:** 4-Layer IDC Capacitor
- **Authors:**
  - Om Patil
  - Krish Kumar Kedia
- **Simulation Software:** Ansys HFSS

---

## Overview

Interdigital Capacitors (IDCs) are planar capacitors formed by interleaving conductive fingers on dielectric substrates. Compared to conventional capacitors, IDCs provide high capacitance density, excellent sensitivity, and compatibility with PCB and MEMS fabrication.

This project presents the design and electromagnetic simulation of a **4-layer IDC capacitor**. The multilayer configuration increases the effective electric field interaction and enhances capacitance while maintaining a compact footprint.

---

## Model

The project includes:

- 3D IDC model
- Four-layer stack-up
- Side-view cross-sectional structure
- Electromagnetic simulation
- Capacitance analysis
- Quality factor analysis

---

## Design Specifications

### Finger Dimensions

| Parameter | Value |
|-----------|-------|
| Length | 5 mm |
| Width | 0.5 mm |
| Thickness | 10 μm |
| Finger Gap | 0.5 mm |

### Substrate Dimensions

| Parameter | Value |
|-----------|-------|
| Length | 23 mm |
| Width | 17 mm |
| Thickness | 0.0254 mm |

---

## Simulation Results

### Capacitance

| Parameter | Value |
|-----------|-------|
| Frequency | 604.8 MHz |
| Capacitance | 1.8396 pF |

### Quality Factor

| Parameter | Value |
|-----------|-------|
| Frequency | 18.28 MHz |
| Quality Factor | 346.1326 |

---

## Features

- Four-layer IDC architecture
- Compact planar capacitor design
- High-quality electromagnetic simulation
- Capacitance vs Frequency analysis
- Quality Factor analysis
- Parametric geometry suitable for further optimization

---

## Software Used

- Ansys Electronics Desktop (HFSS)
- Git
- GitHub

---

## Repository Structure

```
IDC-4Layer-Capacitor/
│
├── README.md
├── HFSS_Model/
│   ├── IDC.aedt
│   └── Simulation Files
│
├── Images/
│   ├── 3D_Model.png
│   ├── Side_View.png
│   ├── Capacitance_Plot.png
│   └── Quality_Factor_Plot.png
│
├── Report/
│   └── IDC_Capacitor_Report.pdf
│
└── Results/
    ├── Capacitance.csv
    └── Q_Factor.csv
```

---

## Applications

- RF Circuit Design
- Microwave Components
- Capacitive Sensors
- MEMS Devices
- Biomedical Electronics
- Wireless Communication Systems
- PCB Integrated Passive Devices

---

## Future Work

- Fabrication of the multilayer IDC
- Experimental validation
- Parameter optimization
- Comparison with conventional IDC structures
- Integration into RF sensing applications

---

## Authors

**Om Patil**  
Electronics and Communication Engineering  
VIT Chennai

**Krish Kumar Kedia**

---

## License

This project is intended for academic and research purposes. Feel free to use and modify it with proper attribution.
