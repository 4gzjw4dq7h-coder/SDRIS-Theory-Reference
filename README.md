# SDRIS Theory: Vacuum Hydrodynamics & Galactic Rotation

> **Reference implementation of the SDRIS framework: Deriving Galactic Rotation Curves via Vacuum Viscosity ($a_0$) instead of Dark Matter.**

[![License: AGPLv3]
[![Status: Experimental](https://img.shields.io/badge/Status-Experimental-orange.svg)](https://github.com/USERNAME/SDRIS)

## 🌌 Abstract

Standard cosmology relies on the hypothesis of **Dark Matter** to explain the flat rotation curves of spiral galaxies. The **SDRIS (Structured Dimension Resonance Isotropic System)** framework proposes a topological alternative:

**The rotation anomaly is a hydrodynamic effect of the vacuum itself.**

This repository contains the mathematical proof and Python simulations demonstrating that a 19-dimensional vacuum structure exerts a specific "back-pressure" (viscosity $a_0$) on baryonic matter. This viscosity stabilizes galactic rotation velocities without the need for invisible mass.

## 🔑 Key Features

* **Vacuum Viscosity ($a_0$):** Derivation of the critical acceleration floor solely from topological limits ($N_P=408$).
* **Hydrodynamic Gravity:** Mass is treated not as an intrinsic property, but as hydrodynamic drag within a superfluid vacuum.
* **Proton-Electron Mass Ratio ($\mu$):**
    * SDRIS Prediction: **1830.65** (Geometric limit)
    * Standard Model: **1836.15** (Including electromagnetic self-energy)
    * *Agreement: 99.7%*
* **Black Hole Topology:** Modeling singularities not as infinite density points, but as dimensional solitons saturated at Dimension 19.

## 📂 Repository Structure

```text
SDRIS-Project/
├── README.md              # Project Documentation
├── LICENSE                # MIT License
├── simulation/            # Python Code & Proofs
│   ├── SDRIS_Galaxy.ipynb # Main Simulation Notebook (Rotation Curves)
│   └── SDRIS_Core.py      # Core Physics Engine & Constants
└── paper/                 # LaTeX Source & Documentation
    ├── sdris_theory.tex   # Scientific Paper
    └── images/            # Generated Plots (galaxy.png, etc.)
