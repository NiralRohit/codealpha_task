# Car Price Prediction using Machine Learning

## Project Overview

This project aims to predict car prices using Machine Learning techniques based on various car-related features such as present price, kilometers driven, fuel type, seller type, transmission, and car age.

The project demonstrates the complete Machine Learning workflow including data preprocessing, feature engineering, model training, evaluation, and visualization.

## Objective

The objective of this project is to build a regression model that can accurately predict the selling price of a car using historical car data.

## Dataset Features

The dataset contains the following features:

* **Present_Price** – Current ex-showroom price of the car
* **Kms_Driven** – Total kilometers driven by the car
* **Fuel_Type** – Type of fuel used (Petrol/Diesel/CNG)
* **Seller_Type** – Dealer or Individual seller
* **Transmission** – Manual or Automatic
* **Owner** – Number of previous owners
* **Year** – Manufacturing year of the car
* **Selling_Price** – Target variable (Price to predict)

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Data Preprocessing
6. Model Training
7. Model Evaluation
8. Price Prediction

## Model Used

**Random Forest Regressor**

Random Forest Regression was used to train the model because it provides high prediction accuracy and handles non-linear relationships effectively.

## Evaluation Metrics

The model was evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

## Model Performance

* **MAE:** 0.6389
* **MSE:** 0.9383
* **RMSE:** 0.9686
* **R² Score:** 0.9593

The model achieved an **R² score of 95.9%**, indicating excellent prediction accuracy.

## Data Visualization

The project includes visualizations such as:

* Correlation Heatmap
* Actual vs Predicted Price Graph
* Feature Importance Plot

## Installation

Install required libraries:

```bash
pip install -r requirements.txt
```

## Run the Project

1. Open the notebook in Google Colab or Jupyter Notebook
2. Upload the dataset (`car data.csv`)
3. Run all cells sequentially
4. View predictions and evaluation results

## Project Structure

```text
Car-Price-Prediction/
│── car_price_prediction.ipynb
│── car data.csv
│── README.md
│── requirements.txt
```

## Conclusion

This project successfully predicts car prices using Machine Learning. The Random Forest model performed very well with high accuracy and low prediction error, making it suitable for real-world car price estimation.
