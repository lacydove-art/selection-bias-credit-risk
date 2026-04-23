# Who Did We Leave Out?  
## Selection Bias in Credit Risk Modeling

## Overview

This project explores a critical issue in credit risk modeling: **selection bias from approved applicants only**.

Using the Home Credit dataset, we:

* Quantify the impact of selection bias
* Apply correction methods (reject inference + survival analysis)
* Evaluate calibration and fairness impacts

## Read the Blog Report

👉 https://lacydove-art.github.io/selection-bias-credit-risk/

## Notebook (Technical Work)

👉 https://nbviewer.org/github/lacydove-art/selection-bias-credit-risk/blob/main/notebook.ipynb

## Key Insight

Models trained only on approved applicants are **well-ranked but poorly calibrated**, especially in underrepresented regions of the feature space.

## Methods

* Logistic Regression
* Survival Analysis
* Reject Inference Techniques
* Calibration Evaluation

## Data
* Home Credit Default Risk - Kaggle  
  👉https://www.kaggle.com/competitions/home-credit-default-risk/data
  
## Author

Michael Beyer, Lacy Dove, Harelle Keli, Aryan Sanan
