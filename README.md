# E-XGBoost-FairSHAP-MoMo-Ghana
Engineered XGBoost with Focal Loss, SHAP Explainability, and Fairness Auditing for Mobile Money Fraud Detection in Ghana
# E-XGBoost-FairSHAP: Mobile Money Fraud Detection in Ghana

**Engineered XGBoost with Focal Loss, SHAP Explainability, and Fairness Auditing**

Department of Computer Science, KNUST | June 2026

## Overview
This repository contains the code and resources for E-XGBoost-FairSHAP,
a focal-loss-engineered XGBoost model with integrated SHAP explainability
and fairness auditing, applied to mobile money fraud detection in the
Ghanaian MTN MoMo / Telecel ecosystem.

## Repository Structure
- `notebooks/01_baselines_locked.ipynb` — locked baseline experiments
- `notebooks/02_e_xgboost_fairshap.ipynb` — engineered model
- `results/locked_baseline_metrics.csv` — baseline results (never modified)
- `results/shap_plots/` — SHAP visualisations
- `results/fairness_audit.csv` — group-wise FPR results- `survey/instrument_v1.pdf` — Ghanaian MoMo user survey instrument
- `data/README.md` — PaySim dataset instructions and survey protocol

## Dataset
PaySim: https://www.kaggle.com/datasets/ealaxi/paysim1
Primary survey: collected under KNUST CHRPE approval (Ref: pending)

## Reproducibility
All experiments use SEED = 42. Install dependencies: `pip install -r requirements.txt`

## Status
- [x] Repository created
- [ ] CHRPE ethics approval received
- [ ] Baseline experiments complete
- [ ] E-XGBoost-FairSHAP experiments complete
