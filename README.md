# Air Quality Index (AQI) Prediction Model

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

## Project Overview
This repository contains a predictive model for forecasting the Air Quality Index (AQI). Leveraging historical data and various environmental factors, the model aims to provide accurate predictions of air quality. This tool is especially useful for environmental analysis and public health forecasting.

## Data Sources
The model uses several datasets that include historical records of AQI, Ozone concentration, PM2.5 levels, and comprehensive weather features. The data is structured to highlight the temporal relationship with AQI values over a span of multiple years.

## Key Variables
The model incorporates a wide range of variables to predict AQI:

Date: To capture temporal trends.

Previous AQI: To understand the continuity in air quality trends.

Ozone Concentration & PM2.5: Critical pollutants affecting air quality.

Weather Features: Including temperature (Max/Min/Mean), dew point, humidity, sea level pressure, visibility, wind speed, precipitation, and cloud cover.

## Modeling Approach
The project employs a linear regression model trained on data from the 1980s and tested on data from the 1990s.
It includes an exploratory data analysis (EDA) to understand trends and relationships in the data.
The model is evaluated based on Mean Absolute Error (MAE) and Mean Squared Error (MSE) metrics to assess prediction accuracy.

## Model Validation
The model's predictions are compared against actual AQI values from past events to gauge its accuracy.
This approach enables an understanding of the model's effectiveness in real-world scenarios and its potential applicability for future predictions.

## Repository Structure
predictor.ipynb: The main Jupyter notebook containing the model development, EDA, and evaluation.
aqi_data.csv, ozone_data.csv, pm2.5_data.csv: Datasets used for model training and testing.
Additional supporting files and documentation.

## Links: 
SF weather features: https://raw.githubusercontent.com/zonination/weather-us/master/sanfrancisco.csv

AQI data: https://aqs.epa.gov/aqsweb/airdata/download_files.html#AQI

PM2.5 data: https://www.epa.gov/outdoor-air-quality-data/download-daily-data


## Usage
Users can clone the repository and run the Jupyter notebook to explore the model and datasets.
The notebook is well-documented, making it easy for users to follow the analysis and understand the model's workings.
Future Work
Extend the model to include more recent data and test its predictive capabilities over a longer time span.
Explore more complex models and machine learning techniques to improve prediction accuracy.


## Authors
[@imeltsner](https://github.com/imeltsner)

[@aleonlopez](https://github.com/aleonlopez)

[@ignaciojuarez](https://github.com/ignaciojuarez)


