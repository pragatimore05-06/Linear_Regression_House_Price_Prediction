# Boston Housing Price Prediction using Linear Regression

## Project Overview
This project uses Machine Learning to predict house prices using the Boston Housing dataset. A Linear Regression model is developed to understand the relationship between house features and median house prices.

## Dataset Information
- **Dataset Name:** Boston Housing Dataset
- **Source:** Kaggle
- **Total Records:** 506 (original dataset)
- **Total Features:** 13 input features and 1 target variable
- **Target Variable:** MEDV (Median House Value)

## Technologies Used
- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Project Workflow
1. Import required libraries.
2. Load and inspect the dataset.
3. Check missing values and duplicate records.
4. Select input features and target variable.
5. Visualise the relationship between features and house prices.
6. Split the dataset into training and testing sets (80:20).
7. Train the Linear Regression model.
8. Generate house price predictions.
9. Evaluate the model using regression metrics.
10. Visualise actual vs predicted prices.
11. Predict the price of a new house.

## Input and Target Variables
- **Input Feature (X):** RM – Average number of rooms per dwelling.
- **Target Variable (y):** MEDV – Median house value (in thousands of US dollars).

## Evaluation Metrics
The model is evaluated using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## Expected Outcome
The project demonstrates how Linear Regression can be used to predict continuous numerical values and evaluate model performance using suitable regression metrics.

## Conclusion
A Linear Regression model is developed to predict house prices based on the average number of rooms. The project demonstrates the complete machine learning workflow, from data preprocessing and visualisation to model training, prediction and evaluation.

## Repository Contents
- `housing.csv` – Boston Housing dataset
- `README.md` – Project documentation

