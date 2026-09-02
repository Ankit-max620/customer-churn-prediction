# Customer Churn Prediction

## Project Overview

This project uses machine learning to predict whether a telecom customer is likely to churn (cancel their subscription). Predicting customer churn can help telecom companies identify customers at risk and improve customer retention.

## Dataset

This project uses the Telco Customer Churn dataset, which contains information about telecom customers, their services, account information, and churn status.

The raw dataset is stored in:

data/raw/telco_churn.csv

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook
- Flask
- Git
- GitHub

## Project Structure

customer-churn-prediction/
├── data/
│   └── raw/
├── notebooks/
│   └── 01_eda.ipynb
├── src/
│   ├── __init__.py
│   ├── logger.py
│   ├── exception.py
│   ├── components/
│   │   ├── data_ingestion.py
│   │   ├── data_transformation.py
│   │   └── model_trainer.py
│   └── pipeline/
│       ├── train_pipeline.py
│       └── predict_pipeline.py
├── artifacts/
├── requirements.txt
├── README.md
└── .gitignore

## Setup

Install the required libraries:

pip install -r requirements.txt

## Current Status

- Unit 1: Introduction & Environment Setup — Completed
- Git and GitHub setup — Completed
- Unit 2: Logging, Exception Handling & Git Essentials — In Progress