This is a reproducible code repository for paper "Distributed Equilibrium Computation for Constrained Fisher Markets via Stochastic
Envelope Subgradient Methods" written by Long et. al. This version has private datasets owned by CEI (VinUniversity) and VinSmart Future along with processed data and eda notebooks. We also includes so we only include algorithm code, experiment results and visualizations.

## Repository Structure
Stochastic_Subgradient_Methods_Experiment_Results_EV/
│
├── README.md                  # Project overview, setup, usage
├── requirements.txt           # Python dependencies (or environment.yml)
├── .gitignore
├── LICENSE
│
├── data/
│   ├── processed/             # Cleaned / transformed data 
│   ├── raw/                   # Original data
│   └── valuation_matrices/    # Used for testing algos on real cases
|  
├── docs/
│   ├── Experiment Notes.docx
|
├── example_IEEE_papers/       # Template for writing
|
├── experiments/               # Experiment pipelines and outputs
│   ├── eda_notebooks/         # Exploratory Data Analysis notebooks
│   └── figures/               # Visualizarions from experiments
│   └── results/               # Algo results on real cases w/ params
│   └── scripts/               # Experiment codes
|
├── final_figures              # Figures used in main paper
│
├── src/                       # Core source code (modular, reusable)
│   ├── algorithms/            # Centralized solver, SPDS, DPDS
│   │   └── cvxpy_solver.ipynb
│   │   └── dpds_algorithm.ipynb
│   │   └── spds_algorithm.ipynb
|   |
│   ├── helpers/               
│   │   └── compute_valuation.py
│   │   └── valuation_newdata.py
|   |
│   └── original.ipynb