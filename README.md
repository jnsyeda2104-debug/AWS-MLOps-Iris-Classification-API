# AWS MLOps – Iris Classification API

## Project Overview

This project demonstrates the deployment of a Machine Learning model as a REST API using Amazon Web Services (AWS).

A Random Forest Classifier was used to classify Iris flowers into three species: Setosa, Versicolor, and Virginica. The trained model was integrated with a FastAPI application and deployed on an AWS EC2 instance.

## Project Objectives

- Train and save a Machine Learning model.
- Build a REST API using FastAPI.
- Deploy the application on an AWS EC2 instance.
- Perform predictions through an API endpoint.
- Understand the practical implementation of ML model deployment on the cloud.

## Technologies & Tools

- Python
- Scikit-learn
- FastAPI
- Uvicorn
- Joblib
- Amazon Web Services (AWS)
- Amazon EC2
- Linux

## Model Information

- **Algorithm:** Random Forest Classifier
- **Dataset:** Iris Dataset
- **Task:** Multi-class Classification
- **Target Classes:** Setosa, Versicolor, Virginica

## Application Features

### 1. Home Endpoint

`/Home`

Checks the application status and confirms that the API is running.

### 2. Prediction Endpoint

`/predict`

Accepts four Iris flower measurements and returns the predicted flower class.

Example input:

- Sepal Length: 5.1
- Sepal Width: 3.5
- Petal Length: 1.4
- Petal Width: 0.2

Expected prediction: Setosa.

## AWS Deployment

The FastAPI application was deployed on an Amazon EC2 instance running Amazon Linux.

The application was run using Uvicorn, and API functionality was tested through the prediction endpoint.

## Project Files

- `app.py` – FastAPI application and prediction endpoint.
- `train.py` – Model training script.
- `rf_model.pkl` – Saved Random Forest model.

## Key Learning Outcomes

- Machine Learning model deployment
- REST API development
- AWS EC2 instance management
- Model serialization using Joblib
- Cloud-based application testing
- Understanding practical MLOps concepts

## Author

Syeda Jovaria Nisar
