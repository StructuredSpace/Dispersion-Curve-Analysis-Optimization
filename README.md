# Dispersion Curve Analysis & Optimization

This repository contains the project files for **Dispersion Curve Analysis & Optimization**, conducted during the first year of my Master’s in Structural Engineering. The goal was to design and optimize a metamaterial unit cell that maximises vibration absorption by exploiting phononic band gaps.

## Project overview

- **Floquet–Bloch simulations (COMSOL):** Built a 2D unit-cell model and applied Floquet–Bloch periodicity to compute dispersion curves along the irreducible Brillouin contour. Generated the first 10 dispersion curves using a parametric sweep of the wave vectors.
- **Mesh convergence study:** Performed a systematic mesh refinement until the frequencies of the third dispersion curve changed by less than 30 Hz between successive mesh sizes, ensuring reliable eigenfrequency results.
- **Band-gap identification:** Analysed the converged dispersion diagram to locate complete and directional band gaps. Calculated gap-to-mid-gap ratios and highlighted the ranges of suppressed wave propagation.
- **Mode-shape visualisation:** Plotted mode shapes for selected points on the second dispersion curve to visualise displacement fields at wavelengths 4× and 2× the unit-cell size.
- **Unit-cell optimisation:** Adjusted geometric parameter `tBeam` and evaluated different polymer materials (PMMA, ABS, PLA, PP) to maximise band-gap widths within 100 Hz–3 kHz while keeping the unit-cell footprint under 5 cm. Compared performance metrics such as Young’s modulus, Poisson’s ratio and density.
- **Outcome:** The optimised metamaterial unit cell exhibited directional band gaps that increased vibration absorption efficiency by approximately **5–10 %** compared with the original configuration.

## Contents

- `24ECM_Abhishek_Neikar.pdf`: Comprehensive report detailing the simulation setup, mesh convergence study, dispersion analysis, band-gap calculations and optimisation results.
- `Data Analysis.xlsx`: Numerical data from the dispersion simulations and material comparison studies.
- `ProjectWork24.pdf`: Assignment brief describing the project tasks and evaluation criteria.

## How to use

1. Review the `ProjectWork24.pdf` document to understand the assignment requirements.
2. Follow the methodology described in the report (`24ECM_Abhishek_Neikar.pdf`) to reproduce the simulations and plots in COMSOL.
3. Examine the `Data Analysis.xlsx` file for raw results of dispersion curves and optimisation sweeps across different materials and mesh sizes.

Feel free to build upon this work for further research in phononic metamaterials, structural optimization or vibration control.
