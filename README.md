# Diabetes-prediction-api-model# Diabetes Prediction API Model

This repository contains a machine learning model to predict diabetes in individuals. The model is built using Python and deployed on Heroku.

## Introduction

This project aims to provide a API model for predicting diabetes based on various health metrics. The model is trained using a dataset of medical records and leverages machine learning techniques to make predictions.

## Features

- Predicts the likelihood of diabetes based on input features.
- RESTful API endpoints for easy integration.
- Deployed on Heroku for accessibility.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Diabetes-prediction-api-model.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Diabetes-prediction-api-model
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the application locally:
   ```bash
   python main.py
   ```
2. Access the API at `http://localhost:5000`.

## API Endpoints

- `POST /predict`: Predicts diabetes based on input data.
  - **Request Body**:
    ```json
    {
        input values ...
    }
    ```
  - **Response**:
    ```json
    {
        "prediction": "Positive" or "Negative"
    }
    ```
