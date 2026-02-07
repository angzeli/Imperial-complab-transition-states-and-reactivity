# ⚛️ Imperial CompLab — Transition States & Reactivity

## 📌 Overview

This repository documents a **systematic computational investigation of reaction mechanisms and transition states** for selected pericyclic reactions, conducted as part of the *Transition State and Reactivity laboratory* at **Imperial College London**.

Using **Gaussian**, the project examines how **method choice** influences predicted **reaction pathways, activation barriers, and transition-state geometries**, with particular emphasis on comparisons between **semi-empirical (PM6)** and **density functional (B3LYP/6-31G(d))** treatments.

--- 

## 🔬 Scientific Focus

The computational study investigates:
- **Pericyclic reactions mechanism**, including:
  - Diels–Alder reactions
  - Cheletropic reactions
- **Transition state location and validation**, using:
  - Frequency analysis (single imaginary mode)
  - Intrinsic Reaction Coordinate (IRC) calculations
- **Methodological comparison** of:
  - PM6 (semi-empirical)
  - B3LYP/6-31G(d) (DFT)

The analysis highlights **qualitative and quantitative differences** in reactivity predictions arising from electronic structure approximations.

---

## 🧪 Key Computational Tasks
- Optimisation of:
  - Reactants
  - Products
  - Transition states
- Transition state validation via:
  - Frequency analysis (single imaginary mode)
  - IRC calculations
  - Energy comparison between PM6 and DFT results
- Visualisation and analysis of:
  - Molecular orbitals (MOs)
  - Reaction coordinates
  - Structural changes along the reaction path

---

## 🗂 Repository Structure

```python
├── Analysed Data/             # Extracted energies and processed results
├── LaTeX Source Files/        # Final report source files
├── MO Diagrams/               # Visualised molecular orbitals
├── Python and Plotted Figures/# Analysis scripts and generated plots
├── Reaction Schemes/          # Reaction diagrams and mechanisms
├── Simulated MOs/             # Gaussian MO outputs
├── Simulated Structures/      # Optimised geometries and TS structures
├── CompLab_TSR.pdf            # Final submitted report
```

---

## ⚙️ Software & Methods
- Gaussian for electronic structure calculations
  - PM6 for rapid semi-empirical screening
  - B3LYP/6-31G(d) for higher-accuracy DFT analysis
- LaTeX for report preparation

--- 

## 🔁 Reproducibility
- All Gaussian input files are included
- Output files support independent verification
- Analysis scripts are fully traceable to reported figures
- Directory structure mirrors the computational workflow

---

## 🎓 Academic Context

This work was completed for the Imperial College Computational Chemistry Laboratory (Transition State & Reactivity) and is intended to demonstrate:
- Rigorous transition state validation
- Critical comparison of electronic structure methods
- Mechanistic interpretation grounded in quantum chemistry
- Clear, reproducible computational practice

---

## Author

Angze Li (Imperial College London)
  
