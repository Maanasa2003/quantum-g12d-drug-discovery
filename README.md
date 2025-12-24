# quantum-g12d-drug-discovery

Repository scaffold for an integrated classical/quantum drug discovery pipeline targeting G12D-mutant systems.

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
