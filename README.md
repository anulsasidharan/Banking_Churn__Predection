# 🏦 Banking Customer Churn Prediction
#### This project aims to predict customer churn in the banking sector using Deep Learning techniques(ANN using Tensorflow). By analyzing customer behavior, transaction patterns, and demographic data, the model identifies customers who are likely to leave the bank. The objective is to help financial institutions proactively retain high-value clients and reduce attrition rates.


<p align="center">
  <img src="image.png" alt="alt text" width="35%">
</p>

## 🔍 Key Features

### Dataset: 
- Utilizes the `Churn_Modelling.csv` dataset containing customer demographics and account details.

### Data Preprocessing:

- Encoding categorical variables using `Label Encoding` and `One-Hot Encoding`.

- Feature scaling using a pre-fitted scaler (`scaler.pkl`).

### Modeling:

- Implements an `Artificial Neural Network (ANN)` using `TensorFlow/Keras`.

- Trained model saved as `model.h5` for future predictions.

### Prediction Pipeline:

- `prediction.ipynb`: Notebook demonstrating the prediction process on new data.

- `app.py`: Script for deploying the model as a web application (e.g., using `Flask or Streamlit`).

### Experiments:

- `experiments.ipynb`: Contains `exploratory data analysis (EDA)` and model training experiments.


## 🛠️ Setup Instructions

### 1. Clone the Repository:

`git clone https://github.com/anulsasidharan/Customer_Churn__Predection.git`

`cd Customer_Churn_Predection`

### 2. Create a Conda Environment:

`conda create -p venv python=3.11 -y`

`conda activate ./venv`

### 3. Install Required Packages:

`pip install -r requirements.txt`

`pip install ipykernel`


## 📁 Project Structure

`Churn_Modelling.csv`: Dataset used for training and evaluation.

`experiments.ipynb`: Notebook containing EDA and model training.

`prediction.ipynb`: Notebook for making predictions using the trained model.

`app.py`: Script to deploy the model as a web application.

`model.h5`: Trained ANN model.

`label_encoder_gender.pkl`: Label encoder for the 'Gender' feature.

`one_hot_encoder_geo.pkl`: One-hot encoder for the 'Geography' feature.

`scaler.pkl`: Scaler used for feature scaling.

`requirements.txt`: List of required Python packages.

## 🚀 Usage
- `Training`: Use experiments.ipynb to train the model and evaluate its performance.

- `Prediction`: Use prediction.ipynb to make predictions on new customer data.

- `Deployment`: Run app.py to deploy the model as a web application for real-time predictions.

## 📊 Results
The trained ANN model achieves satisfactory performance in predicting customer churn, enabling banks to identify and retain customers at risk of leaving.