# Shipment Price Prediction

### Project Overview

This project focuses on predicting shipment prices using machine learning techniques. The goal is to develop a model that accurately estimates shipping costs based on various input features.

###  Dataset Information

The dataset used for this project is stored in raw.csv. It contains information such as shipment weight, distance, package dimensions, and other relevant features that influence shipping costs.

### Installation & Setup

To run this project, install the necessary dependencies:

pip install pandas numpy scikit-learn matplotlib seaborn xgboost

Ensure you have Python 3.13 installed, preferably in an Anaconda environment.

### Model Architecture

The model is built using machine learning algorithms such as:

Linear Regression

Random Forest

XGBoost

Feature selection and engineering are performed to improve predictive performance.

### Training Process

Data preprocessing (handling missing values, feature encoding, normalization)

Splitting the dataset into training and testing sets

Training models and evaluating performance using cross-validation

### Evaluation Metrics

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R-squared (R²)

### Usage

Run the training script to build and evaluate the model:

python train.py

### Future Improvements

Hyperparameter tuning

Incorporating real-time data

Deployment using streamlit

Feel free to contribute and enhance the project!
