# SCT_ML_1(House Price Prediction Using Linear Regression)

## Overview
This project predicts house prices using a Linear Regression model.
The prediction is based on three main features:
- Square Footage
- Number of Bedrooms
- Number of Bathrooms

The project was completed in Google Colab for an internship task at SkillCraft Technology.

## Project Structure
- datasets/
  - train.csv
  - test.csv
- SCT_ML_1.ipynb
- README.md


## Dataset
The dataset contains housing-related numerical features.
The target column for prediction is: SalePrice.

Files inside the datasets folder:
- train.csv
- test.csv

## Data Cleaning
The following preprocessing steps were performed:
- Filled missing numeric values using the median
- Removed unnecessary non-numeric columns
- Retained only important features required for the model

## Visualizations
The notebook contains scatter plots for:
- Square Feet vs Sale Price
- Bedrooms vs Sale Price
- Bathrooms vs Sale Price

(All output graphs are already included inside the notebook.)

## Model Used
Linear Regression

Steps:
1. Load dataset
2. Clean and preprocess data
3. Select features
4. Train-test split
5. Train Linear Regression model
6. Predict house prices  

## How to Run
1. Open Google Colab.
2. Upload the `SCT_ML_1.ipynb` file.
3. Upload the `datasets/` folder.
4. Run all cells to see outputs.

## Author
Sri Gowri
