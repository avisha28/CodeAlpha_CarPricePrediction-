# CodeAlpha_CarPricePrediction-
# Car Price Prediction using Machine Learning

## Project Overview

This project aims to predict the selling price of used cars using machine learning techniques. Various factors such as car age, fuel type, transmission type, ownership history, kilometers driven, and present market price are used to estimate the resale value of a vehicle.

The project demonstrates the application of regression algorithms for solving real-world price prediction problems.

## Dataset Information

The dataset contains information about different cars and their characteristics.

### Features

* Car_Name
* Year
* Selling_Price (Target Variable)
* Present_Price
* Driven_kms
* Fuel_Type
* Selling_type
* Transmission
* Owner

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Project Workflow

### 1. Data Loading

* Imported the car dataset using Pandas.
* Explored the dataset structure and feature information.

### 2. Data Preprocessing

* Checked for missing values.
* Created a new feature called Car Age from the manufacturing year.
* Removed unnecessary columns.
* Converted categorical variables into numerical format using one-hot encoding.

### 3. Exploratory Data Analysis

* Generated descriptive statistics.
* Analyzed relationships between different variables.
* Visualized feature correlations using a heatmap.

### 4. Model Building

* Split the dataset into training and testing sets.
* Trained a Random Forest Regressor model to predict car prices.

### 5. Model Evaluation

The model was evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

### 6. Prediction Analysis

* Compared actual and predicted car prices.
* Visualized model performance using scatter plots.

## Key Findings

* Present Price has a strong influence on the selling price.
* Car Age affects resale value significantly.
* Fuel type and transmission also contribute to price prediction.
* Machine learning can effectively estimate vehicle prices using historical data.

## Results

The Random Forest Regression model successfully predicted car selling prices with high accuracy. The model demonstrated strong predictive performance and effectively captured the relationship between vehicle features and market value.

**R² Score:** 0.9595 (95.95%) 

The high R² score indicates that the model can accurately estimate car prices based on factors such as present price, age, fuel type, transmission type, ownership history, and kilometers driven.

## Conclusion

This project demonstrates how machine learning can be used to predict car prices based on multiple vehicle attributes. The Random Forest Regression algorithm provided accurate predictions and showcased the practical application of data science in the automobile industry.

## Future Improvements

* Use larger and more diverse datasets.
* Experiment with advanced regression algorithms.
* Perform hyperparameter tuning for better accuracy.
* Deploy the model as a web application.

## Author

Developed as part of the CodeAlpha Data Science Internship Program.
