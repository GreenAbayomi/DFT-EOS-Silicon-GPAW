# Electronic Structure of Silicon using DFT (GPAW + ASE)

This project presents a **Density Functional Theory (DFT)** study of crystalline silicon.  
All calculations were performed in **Python** using [GPAW](https://wiki.fysik.dtu.dk/gpaw/) and [ASE](https://wiki.fysik.dtu.dk/ase/).

## 📌 Objectives
- Compute the **Equation of State (EOS)** to extract the bulk modulus and equilibrium volume.
- Calculate the **Density of States (DOS)** to analyze electronic states near the Fermi level.
- Plot the **Band Structure** to confirm the indirect band gap of silicon.

## ⚙️ Methods
- Exchange-correlation functional: **PBE (GGA)**
- Basis: Plane-wave (PW) mode
- k-point sampling: Monkhorst–Pack grid
- Smearing: Gaussian, 0.2 eV
- Tools: Python, GPAW, ASE, NumPy, Matplotlib

## 📊 Results
### 1. Equation of State
- EOS curve fitted with Birch–Murnaghan equation.
- Bulk modulus ≈ **3.4 GPa** (underestimated compared to experiment, as expected for PBE).

### 2. Density of States
- Valence band below Fermi level, conduction states above.
- Clear band gap around Fermi energy.

### 3. Band Structure
- Indirect band gap: VBM at Γ, CBM near X.
- Gap ≈ **0.6 eV**, compared to experimental 1.1 eV.

<p align="center">
  <img src="results/si_eos.png" width="300"/>
  <img src="results/si_dos.png" width="300"/>
  <img src="results/si_band.png" width="300"/>
</p>

## 📚 Conclusion
This project reproduces the **key electronic properties of silicon** using DFT:
- Indirect band gap
- Bulk modulus estimation
- DOS consistent with semiconductor nature

It demonstrates practical use of **GPAW + ASE** for first-principles materials physics research.

## 🚀 How to Run
Clone the repository and open the notebooks in Google Colab or Jupyter:
