## Sure Tomorrow Insurance Project
# Project Overview
This project involves developing machine learning models to assist Sure Tomorrow Insurance Company with various tasks, including customer similarity identification, predicting insurance benefit probabilities, and ensuring data privacy using data obfuscation techniques.

# Features
- Customer Similarity Model: Identifies customers similar to a given customer to aid marketing strategies.
- Insurance Benefit Prediction: Predicts whether a new customer is likely to receive an insurance benefit using a model that outperforms a random dummy model.
- Benefit Amount Prediction: Uses linear regression to predict the number of insurance benefits a new customer might receive.
- Data Obfuscation: Implements data transformation algorithms to protect personal data while maintaining model quality.

## Prerequisites
- Python 3.x
- Required Python libraries: pandas, numpy, scikit-learn

## Installation
- Clone this repository.
- Install the required libraries using:
- pip install -r requirements.txt

## Usage
- Load and Preprocess Data: Prepare the dataset and handle any missing or extreme values.
- Run Models for Each Task:
- For customer similarity: Execute the code to scale the data and find similar customers.
- For insurance benefit prediction: Train and test the prediction model against a dummy baseline.
- For benefits amount: Implement and evaluate the linear regression model.
- For data obfuscation: Apply the data transformation and validate the model's performance.

## Conclusions
- Successfully identified customer behavior patterns.
- Improved prediction model accuracy over a dummy baseline.
- Maintained model performance while protecting customer data.
- Designed a model to identify potential customers that are close in behavior and demographic to current customers.
- Designed a model to determine the probability of customers to make a purchase of insurance and increased the accuracy of our model by using scaled data. Our results were tested against a random dummy model to determine if we could significantly outperform it which our model was able to achieve.
- Used a linear regression model to check RMSE and R2 scores of scaled and unscaled data and displayed our results.
- Obfuscated out data by multipying our data by an inverse of P and then recovered our dataset to make sure customer data is protected without breaking our prediction model.
