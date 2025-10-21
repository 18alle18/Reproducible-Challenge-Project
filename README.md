# Breast Cancer Prediction with Neural Network and Logistic Regression
**Authors:** Alexander Svensson & Love Sundin

## Dataset
Breast cancer prediction as "Benign" or "Malignant" based on the following variables:

- Sample code number
- Clump Thickness
- Uniformity of Cell Size
- Uniformity of Cell Shape
- Marginal Adhesion
- Single Epithelial Cell Size
- Bare Nuclei
- Bland Chromatin
- Normal Nucleoli
- Mitoses

Variables are discrete values from 1-10.

Data set can be found at:
https://archive.ics.uci.edu/dataset/15/breast+cancer+wisconsin+original

## Prediction Methods

1. Neural Network
2. Logistic regression

## Environment & Packages
The code is written in Python using Jupyter Notebook with the following packages:

- pandas
- seaborn
- matplotlib
- sklearn
- keras
- numpy
- keras-tuner
- shap
- statsmodels

## Files

All code is found in the notebook called Project_Alexander_Love.ipynb.
The notebook is can be run one cell at a time, starting at the top, continuing downwards.

All data files used are in the "Data files" directory. The directory "Hyperparameter tuning" contains data from the process of tuning the hyperparameters of the neural network with Bayesian optimization. The trained neural network with the best hyperparameters found is saved as "optimized_model.keras".

## License
This project is licensed under the MIT License – see the LICENSE file for details.
