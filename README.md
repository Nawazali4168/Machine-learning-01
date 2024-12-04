# Impact of Number of Trees and Feature Selection on Overfitting in Random Forest Classifiers

## Overview

This project explores how the **number of trees** and **feature selection** impact overfitting in **Random Forest classifiers**. We use the **Breast Cancer Wisconsin dataset** to evaluate the model's performance and demonstrate how these factors affect accuracy and generalization.

## Objectives

- Understand how **Random Forest** helps prevent overfitting.
- Explore the effect of **number of trees** and **feature selection** on model performance.
- Implement and evaluate Random Forest classifiers using `sklearn` in Python.

## Key Concepts

- **Overfitting**: When a model fits the noise in the data, leading to poor generalization.
- **Feature Selection**: Choosing the most relevant features to improve model accuracy and reduce complexity.
- **Random Forest**: An ensemble method using multiple decision trees to improve accuracy and robustness.

## Steps

1. **Load and preprocess the data** (handle missing values, normalize features).
2. **Train and evaluate Random Forest classifiers** with different numbers of trees.
3. **Select important features** using feature importance and evaluate performance.
4. **Plot performance** with different tree counts and feature selections.

## Results

- Increasing the number of trees generally improves accuracy but with diminishing returns.
- Feature selection reduces complexity without sacrificing performance.

## Requirements

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
