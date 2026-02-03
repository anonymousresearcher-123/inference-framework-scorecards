# inference-framework-scorecards

This repository contains code examples for credit scorecard creation supporting our research on inferential capability in data-driven models.

## Overview

Two approaches to credit scorecard development:
- **Automated approach**: Data-driven binning and feature selection
- **Manual approach**: Manual binning and feature selection

## Getting Started

### Prerequisites
- Python 3.8+
- Required packages: `numpy`, `pandas`, `scikit-learn`, `matplotlib`, `statsmodels`

Install dependencies:
```bash
pip install -r requirements.txt
```

### Running Examples
Both examples can be run as separate Jupyter notebooks:

```bash
# Run automated example
jupyter notebook notebooks/scorecard_example1_automated.ipynb

# Run manual example
jupyter notebook notebooks/scorecard_example2_manual.ipynb
```

### Repository Structure
```
├── README.md
├── requirements.txt
├── feature_monotonicity_table.pdf
├── notebooks/
│   ├── scorecard_example1_automated.ipynb
│   └── scorecard_example2_manual.ipynb
└── data/
    └── GiveMeSomeCredit/
        └── cs-training.csv
        └── Data Dictionary.csv
```
