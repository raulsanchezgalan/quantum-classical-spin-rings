# Quantum-classical crossover in finite spin-1/2 rings

This repository contains the explanatory notebook and supporting output files
used to generate the numerical figures for the paper:

**Quantum-classical crossover in finite spin-1/2 rings with Dzyaloshinsky--Moriya interaction**

The notebook studies finite spin-1/2 rings with nearest-neighbor Heisenberg
exchange, Dzyaloshinsky--Moriya interaction, and an external magnetic field.
It computes the relaxed magnetization, connected spin correlations,
single-site entropy, and critical-field formulas for rings with N = 3,...,8.

## Main notebook

`Heisenberg_DM_paper_computations_N3_to_N8.ipynb`

## Parameters used in the paper

- J = 1.0
- D = 0.2
- B = 0.0
- alpha = 0.15
- time step = 0.03
- number of time steps = 3000
- random product initial states per beta value = 4

## Output files

The generated figures and data are stored in `paper_outputs/`.

## Requirements

Install the required Python packages with:

```bash
pip install -r requirements.txt
