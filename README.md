# AnomaData Capstone Project

## Overview
This project aims to predict machine breakdowns by identifying anomalies in the provided dataset.

## Requirements
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- joblib

## Installation
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`.

## Usage
1. Load the dataset: `data = pd.read_csv('Anoma_data.csv')`.
2. Run the main script: `python main.py`.

## Model Deployment
The trained model can be used for predictions as follows:
```python
import joblib

model = joblib.load('model.joblib')
predictions = model.predict(new_data)
