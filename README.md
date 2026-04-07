# Stochastic Subgradient Methods – Experiment Results (EV)

This repository provides a reproducible implementation for the paper:

> **"Distributed Equilibrium Computation for Constrained Fisher Markets via Stochastic Envelope Subgradient Methods"**  
> by Long et al.

⚠️ **Note:**  
This version has private datasets owned by CEI (VinUniversity) and VinSmart Future along with processed data and eda notebooks.
This repository focuses on:
- Algorithm implementations  
- Experiment pipelines  
- Results and visualizations  

---

## 📦 Repository Structure

```text
Stochastic_Subgradient_Methods_Experiment_Results_EV/
│
├── README.md                  # Project overview, setup, usage
├── requirements.txt           # Python dependencies
├── .gitignore
├── LICENSE
│
├── data/
│   ├── processed/             # Cleaned / transformed data
│   ├── raw/                   # Original data (excluded if private)
│   └── valuation_matrices/    # Testing data for algorithms
│
├── docs/
│   └── Experiment Notes.docx
│
├── example_IEEE_papers/       # Paper writing templates
│
├── experiments/               # Experiment pipelines and outputs
│   ├── eda_notebooks/         # Exploratory Data Analysis
│   ├── figures/               # Generated visualizations
│   ├── results/               # Algorithm outputs with parameters
│   └── scripts/               # Experiment scripts
│
├── final_figures/             # Figures used in the paper
│
└── src/                       # Core source code
    ├── algorithms/
    │   ├── cvxpy_solver.ipynb
    │   ├── dpds_algorithm.ipynb
    │   └── spds_algorithm.ipynb
    │
    ├── helpers/
    │   ├── compute_valuation.py
    │   └── valuation_newdata.py
    │
    └── original.ipynb
