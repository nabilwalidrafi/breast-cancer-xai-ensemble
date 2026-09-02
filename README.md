# Breast Cancer XAI Ensemble

Code for the manuscript: "A High-Fidelity Soft-Voting Ensemble 
Framework for Breast Cancer Classification with Robust Local 
and Global Explainable AI" — PONE-D-26-11640

## Contents
- `analysis.ipynb` — Full analysis notebook including preprocessing, 
  model training, calibrated ensemble, statistical significance tests 
  (Friedman, McNemar, DeLong, Wilcoxon), and XAI analyses 
  (SHAP, LIME, PFI, PDP, ALE)

## Dataset
Wisconsin Breast Cancer Diagnostic dataset from UCI Machine Learning 
Repository: https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic

## Requirements
- Python 3.x
- scikit-learn
- lightgbm
- catboost
- shap
- lime
- pandas, numpy, matplotlib, seaborn
