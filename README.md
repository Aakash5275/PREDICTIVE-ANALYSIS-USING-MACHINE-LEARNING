# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING
A web app that predicts Bengaluru house prices using machine learning. Enter property details like location, size, and BHK to get instant price estimates. Built with Python and Streamlit for buyers, sellers, and agents to make informed decisions.




# Bangalore House Price Prediction

## Overview

This project aims to predict house prices in Bangalore using a machine learning model. The model takes into account various features such as location, total square footage, number of bathrooms, and number of bedrooms (BHK). The project includes a web application built using Streamlit to provide an interactive user interface for making predictions.



## Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model](#model)
- [Results](#results)

## Project Structure

The project consists of the following files and directories:

- `app.py`: The main script for the Streamlit web application.
- `Bengaluru_House_prediction.ipynb`: Jupyter notebook containing the data analysis and model training process.
- `random_forest_house_price_model.pkl`: Serialized machine learning model. `NOT AVAILABLE ON GITHUB DUE TO THE LARGE FILE SIZE.`
- `dataset.pkl`: Serialized dataset used for training the model.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/BangaloreHousePricePrediction.git
    cd BangaloreHousePricePrediction
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Ensure you have Streamlit installed:
    ```bash
    pip install streamlit
    ```

## Usage

To run the web application, execute the following command:
```bash
streamlit run app.py
```

This will start the Streamlit server, and you can access the web application in your browser at `http://localhost:8501`.

## Dataset

The dataset used for this project is a comprehensive collection of housing data from Bangalore. It includes features such as location, total square footage, number of bathrooms, and number of bedrooms (BHK). The dataset is serialized and stored in `dataset.pkl`.

## Model

The machine learning model used in this project is a Random Forest Regressor. The model is trained on the dataset to predict house prices based on the input features. The trained model is serialized and stored in `random_forest_house_price_model.pkl`.



## Results

The web application allows users to input the location, total square footage, number of bathrooms, and number of bedrooms to get a predicted house price in Bangalore. The predicted price is displayed in lakhs.

[OUTPUT] ![Image](https://github.com/user-attachments/assets/a164932e-7290-4d16-8b79-613d355f2b30)
