
# California Housing Price Prediction

## Overview

This project uses machine learning regression techniques to predict median house values using the California Housing dataset from scikit-learn.

## Objectives

- Build a Linear Regression baseline.
- Apply Ridge Regression with feature scaling.
- Tune the regularization parameter using GridSearchCV.
- Evaluate the model using Mean Absolute Error (MAE).
- Analyze prediction errors and residual plots.

## Dataset

The dataset contains housing information derived from the 1990 U.S. Census.

The target variable is `MedHouseVal`, measured in units of $100,000. Target values are capped at approximately 5.0, so this dataset should not be used to estimate current housing prices.

## Methods

- Train-test split
- Linear Regression
- Ridge Regression
- StandardScaler
- 5-fold cross-validation
- GridSearchCV
- MAE evaluation
- Error analysis

## Results

- Best Ridge alpha: `10`
- Best cross-validation MAE: `0.5354`
- Final test MAE: `0.5255`

The test MAE corresponds to approximately $52,551 in the dataset's target units.

## Technologies

- Python
- NumPy
- pandas
- Matplotlib
- scikit-learn
- Jupyter Notebook

## How to Run

Install the required libraries:

```bash
pip install -r requirements.txt
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook and run the cells in order.

## Limitations

- The data is based on historical census information.
- Target values are capped at approximately 5.0.
- Model performance on this dataset does not establish accuracy for current housing prices.

## Learning Outcomes

This project demonstrates practical use of regression, regularization, cross-validation, model evaluation, and error analysis.
