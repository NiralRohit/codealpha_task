# Sales Prediction using Python

## Project Overview

This project predicts future sales based on advertising spend across different marketing platforms such as **TV, Radio, and Newspaper** using **Machine Learning (Linear Regression)**.

The goal is to analyze how advertising investments affect product sales and generate useful business insights for marketing strategies.

## Objectives

* Predict future sales using advertising data.
* Perform data cleaning and preprocessing.
* Analyze relationships between advertising platforms and sales.
* Train a regression model for sales forecasting.
* Evaluate model performance using regression metrics.
* Deliver actionable business insights.

## Dataset

The dataset used in this project is **Advertising.csv**, which contains:

### Features

* **TV** → Advertising budget spent on TV
* **Radio** → Advertising budget spent on Radio
* **Newspaper** → Advertising budget spent on Newspaper

### Target Variable

* **Sales** → Product sales

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Project Workflow

### 1. Data Collection

Load the advertising dataset.

### 2. Data Preprocessing

* Handle missing values
* Remove unnecessary columns
* Perform feature selection

### 3. Exploratory Data Analysis (EDA)

* Correlation heatmap
* Scatter plots
* Advertising impact analysis

### 4. Model Building

Use **Linear Regression** to train the sales prediction model.

### 5. Model Evaluation

Evaluate the model using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

### 6. Sales Prediction

Predict future sales using new advertising spending values.

## Results

The model predicts sales based on advertising expenditure and helps understand which marketing platform contributes most to business growth.

## Business Insights

* TV advertising has the highest impact on sales.
* Radio advertising moderately affects sales.
* Newspaper advertising has less impact on sales.
* Businesses can optimize marketing budgets for better ROI.

## How to Run the Project

1. Upload the dataset (`Advertising.csv`) in Google Colab.
2. Install required libraries.
3. Run all notebook cells step by step.
4. Train the model and evaluate performance.
5. Predict future sales.

## Future Improvements

* Use advanced regression models.
* Add more marketing features.
* Improve prediction accuracy using hyperparameter tuning.

## Author

Developed as part of a Machine Learning project using Python.
