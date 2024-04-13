# Titanic Passenger Dataset Analysis with LightGBM

## Overview
Explore the analysis of the Titanic passenger dataset using the LightGBM model for classification. Evaluate model performance using accuracy_score, roc_auc_score, and f1_score metrics.

## Introduction
This repository contains the analysis of the Titanic passenger dataset, predicting survival outcomes using the LightGBM model. The LightGBM model demonstrates superior performance in terms of accuracy, ROC AUC score, and F1 score compared to Gradient Boosting.

## Contents
- `titanic_lightgbm.ipynb`: Jupyter Notebook containing the Python code for dataset analysis and model implementation.
- `titanic.csv`: CSV file containing the Titanic passenger dataset.

## Approach
1. **Data Exploration**: Analyze the Titanic dataset to understand the features and distribution of data.
2. **Data Preprocessing**: Handle missing values, encode categorical variables, and prepare data for model training.
3. **Model Building**: Implement the LightGBM model for classification.
4. **Model Evaluation**: Assess model performance using accuracy_score, roc_auc_score, and f1_score.
5. **Comparison**: Compare the performance of LightGBM with Gradient Boosting.

## Results
The LightGBM model achieved the following performance metrics:
- Accuracy Score: 87.93%
- ROC AUC Score: 87.93%
- F1 Score: 87.99%

These results demonstrate the effectiveness of LightGBM in predicting survival outcomes for Titanic passengers.

## Requirements
- Python 3
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- LightGBM

## Usage
1. Clone this repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Open and run the `titanic_lightgbm.ipynb` notebook using Jupyter Notebook.

## Contributors
- [Chetan Choudhary](https://github.com/chetan-codes)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
