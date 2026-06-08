# EOLIA Trial Heterogeneous Treatment Effect Analysis

This repository contains the code and results for the heterogeneous treatment effect analysis of the EOLIA trial, reported in the manuscript "Limited Heterogeneity of Treatment Effect of Venovenous ECMO in Severe ARDS: A Secondary Analysis of the EOLIA Trial".

- Primary analysis results (`EOLIA_BART_RD_RR.html`):
  - Conditional average treatment effect (CATE) estimation using BART
  - CART-derived subgroup identification
  - Variable importance and interaction heatmaps

- Supplementary analyses (`EOLIA_supplementary_analyses.html`):
  - Sensitivity analysis for BART hyperparameters 
  - Cross-method comparison (BCF, causal forest, XGBoost meta-learners).
  - Risk-stratified treatment effect analysis
 
- Subgroup analyses by EOLIA enrollment criterion:
  - `HTE_BART_Analysis_EOLIA_V2_sub.html`: analysis restricted to patients enrolled with PaO2/FiO2 < 80 mmHg with FiO2 ≥ 80% for > 6 hours. 
  - `HTE_BART_Analysis_EOLIA_V2_sub_pH.html`: analysis restricted to patients enrolled with pH < 7.25 with PaCO2 ≥ 60 mm Hg for > 6 hours.  
    
