# Survival Analysis
These are specific codes and data for the course of Survival Analysis.

## Contents

The notebooks are numbered in the order of the course. The data sets are in the folder `data`.

**Survivor function and comparison of groups**

| # | Notebook |
|---|---|
| 00 | Kaplan-Meier and Nelson-Aalen estimators, with inference for quantiles |
| 01 | Kaplan-Meier and Nelson-Aalen estimators with `lifelines` |
| 02 | Kaplan-Meier and Nelson-Aalen estimators with `scikit-survival` |
| 03 | Comparison of two groups |
| 04 | Comparison of two groups using Cox regression |
| 05 | Comparison of two groups with three strata |

**Cox regression**

| # | Notebook |
|---|---|
| 06 | Comparison of Cox models with two factors |
| 07 | Building models to compare two treatments for prostatic cancer |
| 08 | Building models with several variables |
| 09 | Variable selection using lasso |
| 10 | Testing non-linearity |
| 11 | Survivor functions from a Cox model with two factors, and the risk-adjusted survivor function |
| 12 | Risk-adjusted survivor functions for two treatments |

**Model checking**

| # | Notebook |
|---|---|
| 13 | Concordance, predictive ability, and explained variance |
| 14 | Time-dependent ROC |
| 15 | Residuals for Cox regression model: infection in patients on dialysis |
| 16 | Residuals for Cox regression model: multiple myeloma |

**Bayesian models**

| # | Notebook |
|---|---|
| 17 | Bayesian Weibull model without covariates |
| 18 | Bayesian Weibull model to compare two groups |
| 19 | Bayesian Weibull model with gamma frailty to compare two groups |
| 20 | Bayesian Weibull model with gamma frailty to compare two groups (extended) |

The file `CheatsheetSurvivalAnalysis.pdf` is the cheatsheet of the course.

## Requirements

Python 3.11 with `numpy`, `scipy`, `pandas`, `matplotlib`, `scikit-learn`, `statsmodels`, `ipywidgets`, `lifelines`, `scikit-survival`, `pymc` and `arviz`.
