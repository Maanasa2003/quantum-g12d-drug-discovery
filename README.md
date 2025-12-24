# Quantum‑Enhanced Generative AI for Drug Discovery Targeting KRAS G12D

## Overview
This project explores whether quantum‑enhanced generative AI can accelerate the discovery of small‑molecule inhibitors targeting the KRAS G12D mutation in pancreatic cancer. It integrates classical generative models with quantum machine learning components to evaluate improvements in molecular design, optimization, and binding prediction.

## Goals
- Generate novel KRAS G12D inhibitor candidates.
- Integrate quantum kernels or variational circuits into generative models.
- Build a full docking + scoring pipeline.
- Compare quantum vs classical performance.

## Repository Structure
- `data/` — datasets (raw, processed, external)
- `models/` — classical, quantum, and hybrid models
- `src/` — core code for generation, quantum modules, docking, scoring
- `notebooks/` — exploratory analysis and experiments
- `results/` — generated molecules, docking scores, evaluations
- `docs/` — project documentation
- `tests/` — unit tests







Project structure

quantum-g12d-drug-discovery/

├── data/
│   ├── raw/
│   ├── processed/
│   └── external/

├── models/
│   ├── classical/
│   ├── quantum/
│   └── hybrid/

├── src/
│   ├── data_processing/
│   ├── generative_models/
│   ├── quantum_modules/
│   ├── docking/
│   ├── scoring/
│   └── utils/

├── notebooks/
│   ├── exploration/
│   ├── experiments/
│   └── results/

├── results/
│   ├── molecules/
│   ├── docking_scores/
│   └── analysis/

├── docs/
│   ├── project_overview.md
│   ├── methodology.md
│   └── results_summary.md

├── tests/

├── README.md
├── LICENSE  # (left unchanged as you indicated you modified licenses)
└── requirements.txt

Quick start

1. Clone:

   git clone https://github.com/Maanasa2003/quantum-g12d-drug-discovery.git
   cd quantum-g12d-drug-discovery

2. Create a virtual environment and install dependencies:

   python -m venv .venv
   source .venv/bin/activate  # or .venv\\Scripts\\activate on Windows
   pip install -r requirements.txt

3. Directory layout is present with .gitkeep files in empty folders. Fill `data/raw` with source datasets and follow docs/ for methodology.

License

This project uses the LICENSE file in the repository. Do not overwrite it without confirmation.
