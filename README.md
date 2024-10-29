# Heart_Disease_Prediction
This project uses a Logistic Regression model to predict whether a person has heart disease based on medical data.
The model is trained on a dataset with 14 features such as age, sex, cholesterol levels, and resting blood pressure.

# Features
- Data Processing: Loads and preprocesses medical data for heart disease prediction.
- Model Training: Trains a Logistic Regression model on the dataset.
- Model Evaluation: Measures accuracy on both training and test data.
- Predictive System: Allows users to input new data and receive a prediction on heart disease status.
  
# Dataset
The dataset consists of 303 samples with 13 features and a target variable indicating heart disease presence (1 for disease, 0 for no disease).

# Requirements
- Python 3.x
- Numpy
- Pandas
- Scikit-learn

# Code Overview
- Data Loading and Processing: Loads the dataset, checks for null values, and splits it into training and testing sets.
- Model Training: Trains a Logistic Regression model using the training data.
- Evaluation: Computes accuracy on both training and test data.
- Predictive System: Allows predictions based on user-provided data.
  
# Model Performance
- Training Accuracy: ~85%
- Test Accuracy: ~82%

# Example Prediction
- To make a prediction, input data such as:
input_data = (62,0,0,140,268,0,0,160,0,3.6,0,2,2)
- The output will indicate if the person has heart disease or not.

# License
- This project is licensed under the MIT License.


