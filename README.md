# PowerPlant_Analysis
This project analyzes the Combined Cycle Power Plant dataset, using linear and KNN regression (with polynomial and interaction terms) to predict hourly energy output and identify optimal prediction models.
PowerPlant Analysis

This project performs an analysis on the Combined Cycle Power Plant (CCPP) dataset to predict the net hourly electrical energy output of a power plant using regression techniques. The analysis involves simple linear regression, multiple linear regression, polynomial and interaction term regressions, as well as k-nearest neighbors (KNN) regression.

Project Overview

Data Exploration

Dataset loading and initial exploration.

Descriptive statistics including mean, median, quartiles, and ranges.

Pairwise scatter plots to understand relationships and correlations among features.

Simple Linear Regression

Individual regressions of each predictor to the response.

Evaluation of statistical significance and identification of potential outliers.

Multiple Linear Regression

Joint regression involving all predictors.

Comparison of coefficients from simple and multiple regression models.

Inclusion of polynomial and interaction terms to capture nonlinear associations.

KNN Regression

Regression analysis using k-nearest neighbors.

Optimization of k-values using raw and normalized features.

Comparative evaluation of regression performance using mean squared error (MSE).

Repository Structure

.
├── data/
│   └── CCPP/
│       ├── Folds5x2_pp.ods
│       ├── Folds5x2_pp.xlsx
│       ├── Readme.txt
│       └── Readme.txt~
├── notebook/
│   └── Shree_HW2_DSML.ipynb
└── README.md

data/CCPP: Contains dataset files and documentation.

notebook: Includes Jupyter Notebook (Shree_HW2_DSML.ipynb) containing detailed analysis and code implementation.

Getting Started

Step 1: Clone the Repository

git clone https://github.com/yourusername/PowerPlant_Analysis.git
cd PowerPlant_Analysis

Step 2: Install Dependencies

(Optional) Set up a virtual environment and install required libraries:

pip install -r requirements.txt

Step 3: Launch the Notebook

jupyter lab

Open Shree_HW2_DSML.ipynb and execute cells sequentially to reproduce analysis.

Results

Linear Regression

Identifies significant predictors affecting the power plant’s energy output.

Compares performance between simple and multiple regression approaches.

Nonlinear and Interaction Terms

Tests for nonlinear and interaction effects to enhance predictive accuracy.

KNN Regression

Finds optimal k-values through systematic evaluation.

Compares KNN regression performance against linear models based on train and test errors.

Contributing

Contributions such as suggestions, issues, or pull requests are encouraged.

License

Select an appropriate license (e.g., MIT License) for your project and include details here if applicable.

References

Combined Cycle Power Plant Dataset - UCI Machine Learning Repository

