# PowerPlant Analysis

This project analyzes the [Combined Cycle Power Plant (CCPP)](https://archive.ics.uci.edu/ml/datasets/Combined+Cycle+Power+Plant) dataset to predict the net hourly electrical energy output (EP) of the power plant. The analysis includes simple linear regression, multiple linear regression, polynomial regression, interaction terms, and k-nearest neighbors (KNN) regression methods.

---

## Project Overview

### Data Exploration

- Loading and examining the CCPP dataset.
- Calculation of descriptive statistics (mean, median, quartiles, ranges).
- Visualizing relationships through pairwise scatter plots and correlation analyses.

### Simple Linear Regression

- Performing regression analysis for each predictor individually.
- Evaluating statistical significance and identifying outliers.

### Multiple Linear Regression

- Using all predictors simultaneously.
- Comparing regression coefficients between simple and multiple regressions.
- Exploring nonlinear effects using polynomial and interaction terms.

### KNN Regression

- Implementing KNN regression with optimized selection of k.
- Evaluating model performance using raw and normalized features.

---


- **`data/CCPP`**: Dataset files and documentation.
- **`notebook`**: Jupyter notebook containing complete analysis (`Shree_HW2_DSML.ipynb`).

---

## Getting Started

### Clone the Repository
```bash
git clone https://github.com/yourusername/PowerPlant_Analysis.git
cd PowerPlant_Analysis


