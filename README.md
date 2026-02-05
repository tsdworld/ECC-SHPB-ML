# ECC-SHPB-ML

**Engineered Cementitious Composites (ECC)** under impact loading: **SHPB experiments** and **machine-learning-based analysis**.

## Highlights
- SHPB wave-based processing (incident/reflected/transmitted) and stress equilibrium checks
- Numerical assistance (e.g., Abaqus/Explicit) for stress non-uniformity / residual capacity
- ML models (RF/XGBoost/LightGBM) for predicting post-impact properties and interpreting key factors

## Repository Structure
```text
ECC-SHPB-ML/
├─ data/
│  ├─ raw/            # Raw experimental data (do NOT upload sensitive/large files)
│  ├─ processed/      # Cleaned / feature-engineered datasets
│  └─ README.md       # Data dictionary + how to obtain raw data
├─ shpb/
│  ├─ wave_processing/  # Wave separation, filtering, alignment
│  └─ metrics/          # DIF, equilibrium, stress non-uniformity metrics
├─ abaqus/
│  ├─ inp/            # Input decks (if shareable)
│  ├─ odb/            # DO NOT upload large ODBs; store scripts only
│  └─ post/           # ODB extraction scripts, plotting
├─ ml/
│  ├─ notebooks/
│  ├─ src/
│  └─ models/         # saved models (small only)
├─ figures/           # publication-ready figures (exported)
├─ paper/             # manuscript, response to reviewers, supplementary
├─ environment/       # conda/pip environment files
└─ README.md
