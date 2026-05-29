# House Price Prediction Using Linear Regression

## Project Overview

This project applies Linear Regression to predict house prices using housing-related features from the California Housing Dataset.

The objective is to understand the complete machine learning workflow, including data preprocessing, feature selection, model training, prediction, and evaluation.

## Dataset

The dataset contains information such as:

* Housing Median Age
* Total Rooms
* Total Bedrooms
* Population
* Households
* Median Income
* Median House Value (Target Variable)

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

## Machine Learning Workflow

### 1. Data Loading

The housing dataset was loaded into a Pandas DataFrame.

### 2. Data Exploration

Performed:

* Dataset inspection
* Data type checking
* Missing value analysis
* Statistical summary

### 3. Data Cleaning

Missing values in the `total_bedrooms` column were filled using the median value.

### 4. Feature Selection

Features:

* housing_median_age
* total_rooms
* total_bedrooms
* population
* households
* median_income

Target:

* median_house_value

### 5. Train-Test Split

The dataset was divided into:

* 80% Training Data
* 20% Testing Data

### 6. Model Training

A Linear Regression model was trained using Scikit-learn.

### 7. Prediction

The trained model was used to predict house prices on unseen test data.

### 8. Model Evaluation

Evaluation Metric:

* RMSE (Root Mean Squared Error)

Result:

* RMSE = 77,258.35

## Key Findings

* Median income strongly influences house prices.
* Housing characteristics contribute significantly to price prediction.
* Linear Regression can effectively model relationships between housing features and property values.

## Conclusion

This project demonstrates the implementation of a supervised machine learning regression model for house price prediction. The model achieved an RMSE of 77,258.35 and provided valuable insights into factors affecting housing prices.

## Author

Funbi O. Olowojesiku

Machine Learning Intern – AnalystLab Africa
