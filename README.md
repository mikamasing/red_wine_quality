# Red Wine Quality Prediction

## Project Overview

This project aims to predict the quality of red wine based on 
various physicochemical properties using machine learning 
techniques. The dataset used is from the UCI Machine Learning 
Repository.

## Dataset

The dataset contains the following columns:
1. Fixed acidity
2. Volatile acidity
3. Citric acid
4. Residual sugar
5. Chlorides
6. Free sulfur dioxide
7. Total sulfur dioxide
8. Density
9. pH
10. Sulphates
11. Alcohol
12. Quality (output variable, score between 0 and 10)

## Project Structure

The project is structured as follows:

- `data/`: Contains the dataset.
- `notebooks/`: Jupyter notebooks for data exploration, 
visualization, and model building.
- `scripts/`: Python scripts for data preprocessing, model training, 
and evaluation.
- `README.md`: Project overview and instructions.

## Steps

1. **Data Exploration and Visualization**: Understand the data 
distribution and identify any correlations between features.
2. **Data Preprocessing**: Handle missing values, normalize 
features, and convert the quality score into a binary classification 
(good/bad wine).
3. **Model Building and Evaluation**: Train a decision tree 
classifier and evaluate its performance using metrics like ROC-AUC.
4. **Hyperparameter Tuning**: Optimize the model's hyperparameters 
to improve performance.

## Installation

To run this project, you need to have Python and the following 
libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter (if using notebooks)

