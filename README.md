# ANN Classification Project

This project is a Streamlit web application for predicting customer churn using an Artificial Neural Network (ANN). It takes customer information such as age, balance, credit score, geography, gender, and account activity, then predicts the probability that a customer will churn.

## Live Demo

https://ann-classification-cxgvhkoa9ff9qsyv2u9ylo.streamlit.app

## Project Overview

- Predicts customer churn using a trained neural network model
- Provides a simple and interactive web interface with Streamlit
- Uses preprocessing steps such as encoding and scaling for model input

## Files Included

- app.py - Streamlit app interface and prediction logic
- model.h5 - Trained ANN model
- Churn_Modelling.csv - Dataset used for training
- requirements.txt - Required Python packages
- experiments.ipynb / prediction.ipynb - Notebook files for experimentation and prediction

## Requirements

Install the required packages using:

```bash
pip install -r requirements.txt
```

## Run the App Locally

```bash
streamlit run app.py
```

Then open the local Streamlit URL shown in the terminal.

## How It Works

1. The app loads the trained ANN model.
2. User enters customer details through the Streamlit form.
3. The input is encoded and scaled.
4. The model predicts churn probability.
5. The app displays whether the customer is likely to churn.

## Author

Devraj Maji

This project was built as an ANN-based classification demo for customer churn prediction.
