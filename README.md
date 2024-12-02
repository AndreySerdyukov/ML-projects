# ML projects
This folder contains my machine learning projects, including classification and regression tasks.

## Folder Structure

- **Selection**: This folder contains Jupyter notebooks for hyperparameter tuning. The files include various methods and approaches for optimizing model hyperparameters.
  
- **Model**: This folder contains the final models obtained after hyperparameter tuning. These models are trained and ready for use in classification or regression tasks.

## Description

Each project consists of two main stages:
1. Hyperparameter tuning using different techniques (GridSearch, ColumnTransformer etc).
2. Training and saving the final model that achieved the best performance on validation data.

The projects cover a variety of tasks, including image classification, text analysis, time series forecasting, and other machine learning problems.

## How to Run
```
git clone https://github.com/AndreySerdyukov/ML-projects
cd ML-projects
python3 -m venv venv
source venv/bin/activate  # macOS/Linux
jupyter lab
```


