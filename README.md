# Ford Car Price Prediction Using Generative AI and Machine Learning
This project explores how Generative AI can help write Python code to prepare and analyze data and build machine learning models for predicting Ford car resale prices. It involves cleaning the dataset, exploring car sales data, identifying price outliers, and comparing different regression models, including linear, polynomial, and Ridge regression. Finally, GridSearchCV is used to find the best hyperparameter for the Ridge regression model and improve its prediction accuracy.

## Project Scenario

You have been hired as a Data Scientist by a consultancy firm that serves a resale car dealer. The dealer specializes in Ford cars and wants your firm to develop a model that can predict the optimal quotation price for the cars in its inventory.

The client provides sales data collected over the past few years. The dataset contains various car features, along with the prices at which the cars were sold.

Your assigned tasks are as follows:

1. **Data Cleaning:** Identify and handle duplicate entries and missing values in the dataset.
2. **Exploratory Data Analysis (EDA):** Analyze the dataset to gain insights into the data and understand how different features affect car prices. The client specifically requests that you:
   - Identify the number of sales for each fuel type.
   - Determine which transmission type has more price outliers.
3. **Regression Modeling:** Compare linear, polynomial, and Ridge regression models using single and multiple variables to identify the best-performing model.
4. **Hyperparameter Tuning:** Perform a grid search on the Ridge regression model to identify the optimal hyperparameter for the best performance.

## About the Dataset

This dataset contains resale prices for Ford cars. It is publicly available on Kaggle under the [Ford Car Pricing Dataset](https://www.kaggle.com/datasets/adhurimquku/ford-car-price-prediction) and is licensed under [CC0: Public Domain](https://creativecommons.org/publicdomain/zero/1.0/).

The dataset has been slightly modified for this project.

The dataset attributes are described below.

| Variable | Description |
|---|---|
| `model` | Car model name |
| `year` | Year the car was manufactured |
| `transmission` | Type of transmission: Automatic, Manual, or Semi-Auto |
| `mileage` | Number of miles the car has traveled |
| `fuelType` | Type of fuel used: Petrol, Diesel, Hybrid, Electric, or Other |
| `tax` | Annual tax payable in USD |
| `mpg` | Miles per gallon |
| `engineSize` | Engine size of the car |
| `price` | Selling price of the car in USD |

## Project Tasks

The project focuses on three main areas: data preparation, data analysis, and model development. Using the provided dataset, you will write prompts for a Generative AI tool to generate Python code for each task.

