# house-price-prediction-api
Machine Learning-based House Price Prediction API built using Flask, Scikit-Learn, and RESTful APIs. Supports real-time price prediction through Postman and web requests.
# House Price Prediction API

This project is a Machine Learning-based House Price Prediction System developed using Python, Scikit-Learn, and Flask. The model is trained on housing data to predict property prices based on various features such as overall quality, living area, garage capacity, basement size, and year built.

The trained model is deployed as a REST API using Flask and can be tested through Postman or integrated into web and mobile applications.

## Features
- Data preprocessing and feature engineering
- Machine Learning model training and evaluation
- Model serialization using Pickle
- REST API development using Flask
- API testing with Postman
- Ready for cloud deployment

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-Learn
- Flask
- Joblib
- Postman

## API Endpoints

### GET /
Returns API status.

### GET /features
Returns the list of model features.

### POST /predict
Predicts house prices based on input features.

## Sample Response

{
    "predicted_price": 285432.75
}

## Project Workflow

Data Collection → Data Preprocessing → Model Training → Model Serialization → Flask API Development → Postman Testing → Deployment
