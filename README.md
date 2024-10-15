## Lending-Club-Interest-Rate-Prediction

## Project Overview

This project aims to predict interest rates for loans issued by Lending Club using machine learning models. By analyzing historical loan data and macroeconomic factors, the project seeks to build a model that can accurately estimate interest rates for new loan applications.

## Data Source

The project utilizes two main data sources:

1. **Lending Club Loan Data:** Historical data on loans issued by Lending Club, including loan details, borrower information, and loan performance. This data is obtained from Lending Club's website or publicly available datasets.

2. **Macroeconomic Data:** Data on macroeconomic indicators like interest rates, inflation rates, and CPI obtained from the Federal Reserve Economic Data (FRED) API. This data provides context about the broader economic environment during the loan issuance period.

## Methodology

1. **Data Cleaning and Feature Engineering:** Raw loan data and macroeconomic data are cleaned and processed to handle missing values, inconsistencies, and outliers. New features are engineered to create more informative variables for the model.

2. **Exploratory Data Analysis:** Data visualization techniques are used to explore the relationships between variables, identify trends, and gain insights into factors that influence interest rates.

3. **Model Development:** Machine learning models, such as XGBoost and ARIMA, are employed to predict interest rates. The dataset is split into training and testing sets for model evaluation.

4. **Model Evaluation:** The performance of the models is assessed using metrics like Root Mean Squared Error (RMSE) to measure the accuracy of predictions. 

5. **Inflation Adjustment:** The predicted interest rates are adjusted for inflation to provide a more realistic estimate of the cost of borrowing.


## Key Findings

- The project identifies key factors that significantly influence interest rates, including borrower creditworthiness, loan amount, loan term, and macroeconomic conditions.
- The developed models demonstrate reasonable accuracy in predicting interest rates, allowing for more informed loan pricing decisions.
- The inflation adjustment provides a valuable perspective for lenders and borrowers to understand the real cost of borrowing.

## Future Enhancements

- Incorporate more advanced feature engineering techniques.
- Experiment with different machine learning models and ensemble methods.
- Develop a web application to provide interactive predictions and insights.

