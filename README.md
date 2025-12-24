# Quantum‑Enhanced Generative AI for Drug Discovery Targeting KRAS G12D

## Overview
This project explores whether quantum‑enhanced generative AI can accelerate the discovery of small‑molecule inhibitors targeting the KRAS G12D mutation in pancreatic cancer. It integrates classical generative models with quantum machine learning components to evaluate improvements in molecular design, optimization, and binding prediction.

KRAS G12D is one of the most aggressive oncogenic drivers in pancreatic cancer, and discovering potent inhibitors remains a major scientific challenge. This project aims to build a reproducible, open‑source pipeline that investigates whether quantum computing can meaningfully contribute to early‑stage drug discovery.

## Goals
- Generate novel KRAS G12D inhibitor candidates.
- Integrate quantum kernels or variational circuits into generative models.
- Build a full docking + scoring pipeline.
- Compare quantum vs classical performance across:
   1. Molecular diversity
	2. Binding affinity
	3. Latent space structure
	4. Optimization efficiency
- Produce a fully reproducible research framework.

## Research Questions:
1. Can quantum‑enhanced generative models produce better or more diverse KRAS G12D inhibitor candidates?
2. Do quantum methods improve molecular similarity modeling or latent space structure?
3. Can a hybrid quantum–classical pipeline outperform classical baselines in early‑stage drug discovery?

## Repository Structure
- `data/` — datasets (raw, processed, external)
- `models/` — classical, quantum, and hybrid models
- `src/` — core code for generation, quantum modules, docking, scoring
- `notebooks/` — exploratory analysis and experiments
- `results/` — generated molecules, docking scores, evaluations
- `docs/` — project documentation
- `tests/` — unit tests

## Methodology 
1. Data Preparation
   - Collect KRAS G12D structural data
	- Prepare ligand datasets
	- Generate 3D conformers
2. Generative Model
   - Diffusion / graph‑based / transformer‑based generator
	- Quantum‑enhanced latent encoding or kernel
3. Quantum Module
   - Variational quantum circuits
	- Quantum similarity kernels
	- Quantum feature maps
4. Scoring Pipeline
   - Docking against KRAS G12D
	- Binding affinity prediction
	- ADMET filtering
	- Synthesizability checks
5. Evaluation
   - Compare quantum vs classical performance
	- Analyze molecular diversity
	- Rank final candidates

### Installations:
pip install -r requirements.txt

## Usage
Code examples and usage instructions will be added as the project develops.

## License
This project is licensed under the GNU General Public License v3.0 (GPL‑3.0).  
Users may modify and distribute the code only if derivative works remain open‑source under the same license.

## Contributing
Contributions are welcome. Please open an issue or submit a pull request.

## Acknowledgements
This project draws inspiration from advances in:
- Quantum machine learning
- Generative models for drug discovery
- KRAS G12D structural biology

## Author
Maanasa Panchakarla
Dublin City University (Masters' in Artificial Intelligence) 
Interested in Quantum AI research, drug discovery, and space exploration.

This project uses the LICENSE file in the repository. Do not overwrite it without confirmation.
