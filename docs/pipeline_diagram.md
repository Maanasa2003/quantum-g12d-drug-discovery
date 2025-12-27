# Pipeline Diagram

```mermaid
flowchart TD

A[Load Data] --> B[Preprocess Data]
B --> C[Train Generative Model]
C --> D[Generate Molecules]
D --> E[Docking Against KRAS G12D]
E --> F[Scoring & Filtering]
F --> G[Save Results]
