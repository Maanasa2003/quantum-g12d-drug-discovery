# Pipeline Overview
This document describes the high-level workflow of the project
**Quantum-Enhanced Generative AI for Drug Discovery Targeting KRAS G12D**.

The pipeline is designed to be modular, reproducible, and easy to extend.
Each stage is implemented inside the `src/` directory.

## 1. Data Loading
Fetch datasets from online sources using scripts in `src/data_processing/`.
Data sources include:
- PDB (KRAS G12D structures)
- ChEMBL (known inhibitors)
- PubChem (compound properties)
- ZINC (large molecule space)
- MOSES / GuacaMol (benchmark datasets)
- ADMET datasets
Output: raw data stored in `data/raw/`.

## 2. Data Preprocessing
Clean and standardize molecules for model training.
Tasks include:
- SMILES cleaning
- Removing invalid molecules
- Train/validation/test splits
- Feature extraction
Output: processed data stored in `data/processed/`.

## 3. Generative Model Training
Train classical and quantum-enhanced generative models.
Models may include:
- VAE / GAN / Diffusion models
- Quantum Variational Circuits
- Hybrid quantum-classical architectures
Output: trained model weights.

## 4. Molecule Generation
Use the trained model to generate new candidate molecules.
Tasks include:
- Sampling molecules
- Validity checks
- Diversity filtering
Output: generated molecule list.

## 5. Docking
Dock generated molecules against KRAS G12D.
Tasks include:
- Preparing receptor structure
- Preparing ligands
- Running docking (AutoDock Vina or similar)
Output: docking scores and poses.

## 6. Scoring and Filtering
Evaluate molecules using:
- Binding affinity
- ADMET predictions
- Synthetic accessibility
- Drug-likeness metrics
Output: ranked list of candidate molecules.

## 7. Saving Results
Store final results in:
- `results/` folder
- CSV files
- Visualizations

## Summary
This pipeline provides a complete workflow from:
**data → model → generation → docking → scoring → results**.

Each step is modular and can be improved independently.
