# 🚗 Car Sales Prediction
This project utilizes machine learning to predict the car purchase amount based on customer demographic and financial information.

## 📊 Dataset Description
The dataset contains the following features:

```markdown
Column Name         | Description
Customer Name       | Full name of the customer
Customer e-mail     | Customer's email address
Country             | Country of residence
Gender              | Gender of the customer
Age                 | Age of the customer
Annual Salary       | Annual income in USD
Credit Card Debt    | Credit card debt in USD
Net Worth           | Customer's net worth in USD
Car Purchase Amount | Amount spent on car purchase (target)
```

## 🛠️ Libraries Used
The project is built using the following libraries:

```python
import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
import tensorflow as tf
import pickle
import warnings

warnings.filterwarnings("ignore")
%matplotlib inline
```

## 📌 Objective
The main goal is to train a regression model to accurately predict how much a customer is likely to spend on a car based on their personal and financial data.

## 📈 Workflow Overview
1. Data Loading & Preprocessing

2. Exploratory Data Analysis (EDA)

3. Feature Engineering

4. Model Building with TensorFlow/Keras

5. Model Evaluation

6. Saving the Model with Pickle

7. Deployment-Ready Predictions

## 🧠 Model
This project uses a neural network built with TensorFlow/Keras for regression. The model learns the relationship between customer attributes and their car purchase spending.

## 📦 Output
- Trained machine learning model saved as .pkl file

- Visualizations of feature distributions and correlations

- Performance metrics such as Mean Absolute Error (MAE)









