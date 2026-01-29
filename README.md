# EOLIA Trial Heterogeneous Treatment Effect Analysis

This repository contains the results of a heterogeneous treatment effect (HTE) analysis for the EOLIA trial using Bayesian Additive Regression Trees (BART).

## Contents

- `EOLIA_BART_RD_RR.html`: Primary analysis results including:
  - Conditional average treatment effect (CATE) estimation using BART
  - CART-derived subgroup identification
  - Variable importance and interaction heatmaps

## Methods

Treatment effect heterogeneity was assessed using a two-step approach:
1. Individual-level CATEs were estimated using BART with hyperparameters selected via cross-validation
2. A CART model was fit to the estimated CATEs to identify patient subgroups with differential treatment effects

## Reference

For methodological details on the variable importance and interaction visualization, see:
- Inglis A, Parnell A, Hurley C. bartMan: Visualizing and Diagnosing Bayesian Additive Regression Trees. *Journal of Data Science, Statistics, and Visualisation*. 2024.
