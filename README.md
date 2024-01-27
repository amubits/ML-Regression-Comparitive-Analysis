# HW3 Dataset Predictive Modeling

## Overview
This repository is dedicated to building and evaluating predictive models for the `HW3.xlsx` dataset, which contains consumer responses to a test mailing of a catalog, including purchase decisions and spending amounts. The project involves two main tasks: predicting the spending amount based on customer information, excluding the Purchase attribute, and a focused analysis on a restricted dataset of confirmed purchases.

## Task A: Predicting Spending on Full Dataset
- **Models Used**: Linear Regression, k-NN, Regression Tree, SVM Regression, Neural Network, and Ensembling Models.
- **Exploration**: The process involved hyper-parameter tuning, normalization of data, and model evaluation to identify the best predictive model for each technique.
- **Best Results**: The repository documents the top-performing model configurations and their predictive performances for each technique.

## Task B: Predicting Spending on Restricted Dataset
- **Restricted Dataset**: Only includes records where a purchase was made (`Purchase = 1`).
- **Modeling Approach**: The same set of models was applied to this subset, with the aim of comparing the predictive performance to that of the full dataset.

## Task C: Comparative Analysis
- **Performance Discussion**: An analysis of why models might perform differently on the full dataset versus the restricted dataset, with insights into the effects of data volume, variability, and potential biases.

## Key Findings
- **General Trend**: Except for Linear Regression, all models showed better performance on the full dataset than on the restricted dataset, as indicated by lower RMSE values.
- **Linear Regression**: The RMSE remained constant across both tasks, suggesting insensitivity to the dataset restriction.
- **Neural Network Performance**: Notably excelled in Task A, potentially due to its capacity to capture non-linear relationships in the data.
- **Data and Variability**: The full dataset's broader data scope and variability likely contributed to the generally better performance of models in Task A.

## Usage
Instructions for data preprocessing, model training, and evaluation are provided, enabling replication of the analysis or application to similar datasets.

## Contribution
Contributions for model optimization, additional analyses, or documentation enhancements are welcome. Please fork the repository and submit pull requests.

## License
The project is released under the MIT License.
