# AI Realization Gap: Empirical Analysis of EU-27 Countries

## Overview

This repository contains the Python notebooks, analytical outputs, tables, figures, and econometric results for a research project examining the **AI Realization Gap** across the 27 member states of the European Union (EU-27).

The project investigates how differences in AI-related conditions and observed outcomes can be assessed across countries and over time. It is organized as a step-by-step research workflow to make the analysis transparent and reproducible.

> **Research status:** Working research repository. Variable definitions, the exact gap construction, sample coverage, model specifications, and findings should be verified against the notebooks and accompanying manuscript before citation.

## Repository structure

```text
ai_realization_gap/
├── codes/                           # Python/Jupyter notebooks for each analytical step
├── Step_01_outputs/                 # Outputs from Step 01
├── Step_02_outputs/                 # Outputs from Step 02
├── Step_03_outputs/                 # Outputs from Step 03
├── Step_04_outputs/                 # Outputs from Step 04
├── Step_05_outputs/                 # Outputs from Step 05
├── Step_06_Figures/                 # Descriptive and diagnostic figures
├── Step_06_Tables/                  # Descriptive and diagnostic tables
├── Step_07_All_Econometric_Results/ # Econometric estimation outputs
└── README.md
```

Notebook filenames currently include:

- `codes/Step_06_Descriptive_Analysis_and_Gap_Diagnostics.ipynb`
- `codes/Step_07_All_Econometric_Results.ipynb`

Consult the `codes/` directory for the full sequence of scripts and notebooks.

## Research workflow

1. **Steps 01–05 — Data preparation and intermediate analysis.** Inspect the corresponding notebooks and output folders for the data sources, cleaning procedures, transformations, and intermediate datasets used in this study.
2. **Step 06 — Descriptive analysis and AI Realization Gap diagnostics.** Generate summary tables and figures, including visualizations of how the mean AI Realization Gap changes over time in EU-27 countries.
3. **Step 07 — Econometric analysis.** Estimate the specifications implemented in the notebooks and save the associated model outputs for review and robustness assessment.

The steps above describe the repository organization; the notebooks are the authoritative source for exact variable formulas and model specifications.

## Reproducing the analysis

### Requirements

- Python 3.10 or later (recommended; check the notebooks for version-specific dependencies)
- Jupyter Notebook, JupyterLab, or Google Colab
- Python packages imported by the notebooks

To run locally:

```bash
git clone https://github.com/sureyyatemelli/AI_Realization_Gap.git
cd AI_Realization_Gap
jupyter lab
```

Open the notebooks in `codes/` and run them in step order. Update any local or Google Drive paths to match your environment. Verify that input datasets are present at the paths expected by the notebooks.

For complete computational reproducibility, the project should also provide a pinned `requirements.txt` (or an environment file), the source-data download instructions, and the precise commands or notebook order needed to regenerate all outputs.

## Data sources and availability

Data provenance and access conditions should be checked in the individual notebooks. Before releasing a final archival version, document for each input dataset:

- Original provider and dataset title
- Source URL, version, and date accessed
- Geographic and temporal coverage
- License or redistribution restrictions
- Any transformations or harmonization steps

Only redistribute source data when the applicable terms permit it.

## Outputs

The output directories organize intermediate files, descriptive tables, figures, and econometric results. These materials support inspection of the analytical process; interpretation of the findings should follow the final manuscript and the corresponding model diagnostics.

## Citation

If you use the code or outputs, cite the accompanying article when available. A permanent archived release (for example, via Zenodo) can additionally provide a version-specific DOI.

**Repository:** https://github.com/sureyyatemelli/AI_Realization_Gap

## License

No license is specified in this repository at present. Unless a license is added, standard copyright restrictions apply. Code and third-party datasets may have different reuse terms.

## Contact

For questions or issues, please use the GitHub repository's Issues section.
