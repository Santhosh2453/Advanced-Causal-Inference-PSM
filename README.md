# Advanced Causal Inference: Propensity Score Matching (PSM)

This project builds and analyzes a synthetic observational dataset to estimate treatment effects using Propensity Score Matching (PSM).

## Deliverables
- Synthetic dataset
- Propensity score model (logistic regression)
- Nearest neighbor matching with caliper
- ATT estimation with 95% confidence interval
- Balance diagnostics (SMD before/after)
- Love plot
- Final matched dataset
- Full PSM Report

## Files in this Repository
- `Advanced_Causal_Inference_PSM.ipynb` — full analysis notebook
- `synthetic_psm_data.csv` — generated dataset
- `matched_dataset.csv` — output matched sample
- `balance_table.csv` — covariate balance results
- `love_plot.png` — SMD visualization
- `psm_report.txt` — text summary report

## How to Reproduce
1. Install requirements: numpy, pandas, sklearn, matplotlib
2. Open the Jupyter notebook
3. Run all cells

## Author
(Your name)
