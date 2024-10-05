# Medical Insurance Cost Prediction

## Overview

This project aims to predict the medical insurance charges for individuals based on personal and health-related factors such as age, BMI, smoking habits, and the region of residence. By analyzing the dataset, we build predictive models that can help estimate insurance costs, which could be useful for insurance companies and policyholders alike.

## Objective

The objective of this project is to develop a predictive model that accurately estimates medical insurance costs based on features such as age, gender, BMI, smoking status, number of children, region, and other related factors. This will be achieved using both Linear Regression and Polynomial Regression models.

## Dataset

 The dataset contains information on 1,338 individuals and is freely available in public domain repositories like Kaggle.
 Dataset : [insurance.csv](https://www.kaggle.com/datasets/mirichoi0218/insurance)

 ## Algorithms Used

- Linear Regression
- - Polynomial Regression

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit
- Pickle
- Jupyter Notebook

## How It Works

- Data Preprocessing:

  - Categorical variables such as gender, smoker, and region are encoded using LabelEncoder.
  - New features like age_group (child, adult, older) and bmi_category (underweight, normal, overweight, obesity) are created.

- Modeling:

  - Linear Regression: The model is trained on 80% of the data, and its performance is evaluated on the remaining 20%.
  - Polynomial Regression: The same training and testing process is repeated using a polynomial regression model of degree 3.

- Evaluation:

  - Accuracy scores and Mean Absolute Errors (MAE) are computed to evaluate the performance of the models.

- Dynamic Prediction:

  - A module is built for dynamic prediction where users can input feature values to predict insurance costs.

- Model Saving:

  - The polynomial regression model and polynomial features are saved using pickle for future use.

## Results

- Linear Regression: 74.44% training accuracy, 77.95% testing accuracy, Testing error: 6.66%
- Polynomial Regression: 87.72% training accuracy, 87.76% testing accuracy, Testing error: 4.16%

## Conclusion

- Polynomial Regression significantly outperforms Linear Regression in terms of accuracy and lower error rates. It captures the non-linear relationships in the dataset more effectively, making it the preferred model for this project.
- The model can be used to predict insurance costs with reasonably high accuracy, making it a valuable tool for insurance companies to estimate premiums based on individual features.





Bibhash Dash.
