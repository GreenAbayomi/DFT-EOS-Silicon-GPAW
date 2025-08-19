# DFT-EOS-Silicon-GPAW
Equation of State (EOS) for Silicon using DFT with GPAW/ASE on Google Colab. Includes Birch–Murnaghan fitting and bulk modulus extraction.
# Silicon Equation of State (DFT with GPAW/ASE)

This project computes the **Equation of State (EOS)** for diamond-structured Silicon using **Density Functional Theory (DFT)** with the GPAW package, run on **Google Colab**.  
We fit the DFT energy–volume data to the **3rd-order Birch–Murnaghan equation of state** to extract the **equilibrium volume and bulk modulus**.

## Steps
1. Built diamond-Si primitive cell with ASE.
2. Performed GPAW/PBE plane-wave DFT calculations at different volumes.
3. Fitted EOS curve and extracted bulk modulus.
4. Produced publication-quality plots with matplotlib.

## Results
- Equilibrium volume V₀ ≈ XX Å³  
- Bulk modulus B₀ ≈ YY GPa (in agreement with literature ~100 GPa)  

## Requirements
- Python 3
- ASE
- GPAW
- numpy, scipy, matplotlib, pandas
