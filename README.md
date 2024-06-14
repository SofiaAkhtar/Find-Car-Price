# Car Price Prediction Model
## Overview
This project aims to predict the selling price of used cars using machine learning techniques. By taking various input features related to the car's details, the model estimates the selling price accurately. Key input features include Present_Price, Kms_Driven, Owner, Year, Fuel_Type, Seller_Type, and Transmission.

## Dataset
The dataset used for training and testing the model is not included in this README due to its size. You can obtain the dataset from the dataset file provided in the dataset/ directory.

## Model Details
The predictive model is trained on a comprehensive dataset of used car prices. Important features that influence the prediction include:

- Present_Price: Current price of the car.
- Kms_Driven: Total kilometers driven by the car.
- Owner: Number of previous owners.
- Year: Age of the car (calculated as the difference between the current year and the year of manufacture).
- Fuel_Type: Type of fuel used by the car (Petrol/Diesel).
- Seller_Type: Whether the seller is an individual or a dealer.
- Transmission: Type of transmission (Manual/Automatic).
## How to Use
1. Install Dependencies:

- Ensure you have Python installed on your system.

- Install the required Python packages by running:

```bash

pip install -r requirements.txt
```
2. Run the Flask Application:

- Start the Flask web application to interact with the prediction model:

```bash

python app.py
```

- Enter the required car details in the web form and submit to get the predicted selling price.

## Project Structure
- dataset/: Contains the dataset used for training and testing. Refer to the dataset/README.md for instructions on obtaining the dataset.
- source/: Source code files for the machine learning model and the prediction script.
- templates/: HTML templates for the Flask web application.
- static/: Static files such as CSS and JavaScript for the web application.
- app.py: Flask application script.
- requirements.txt: List of Python dependencies.
## Contributors
Sofia Akhtar
