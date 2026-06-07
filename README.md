# Mining Reviewer Rings: A Forensic Pipeline for Coordinated Fraud

**Data Mining Course Project** | University of Trento | MSc Data Science

## Overview

A five-stage unsupervised fraud detection pipeline that identifies coordinated fake review campaigns in the Amazon Appliances dataset using classical data mining techniques.



## Repository Structure

```
├── analysis.ipynb              # Main pipeline implementation
├── eda.ipynb                   # Exploratory data analysis
├── Data Mining Report.pdf      # Full technical report
├── output/                     # Generated figures
├── campaign_risk_scores.csv    # Risk scores for all users
├── cluster_assignments.csv     # DBSCAN cluster labels
├── near_duplicate_pairs.csv    # LSH-detected duplicates
├── cache/                      # Cached computations (LSH, FP-Growth)
├── Appliances/                 # Amazon appliances dataset
└── requirements.txt            # Python dependencies

```

## Dependencies

```bash
pip install -r requirements.txt
```

Main libraries: `polars`, `pandas`, `scikit-learn`, `datasketch`, `mlxtend`

## Usage

```bash
# Run full pipeline
jupyter notebook analysis.ipynb

# Exploratory analysis
jupyter notebook eda.ipynb
```

