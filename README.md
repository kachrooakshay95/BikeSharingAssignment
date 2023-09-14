# BikeSharingAssignment
Bike sharing service for customers to rent the bike temporarily.

## Business Understanding

A bike-sharing system is a service that provides bikes for shared use to individuals on a short-term basis, either for a fee or sometimes even for free. These systems typically feature computer-controlled docks where users can input their payment information to unlock a bike. Once unlocked, the bike can be used and later returned to another dock within the same system. In this case study, our primary objective is to investigate the key factors influencing the demand for shared bikes, particularly in the American market. The company's specific inquiries include:

Identifying Significant Variables: We aim to determine which variables play a crucial role in predicting the demand for shared bikes. By analyzing the data, we can pinpoint the factors that have a meaningful impact on bike rental demand.

Understanding Demand Drivers: We will assess how well these identified variables describe the variations in bike rental demands. This analysis will provide insights into the strength and direction of the relationships between these factors and the demand for shared bikes.

The ultimate goal of this study is to provide the bike-sharing company with actionable insights into the American market, helping them adapt their strategies and operations to meet customer expectations and optimize their business for success in this unique market context.

## Objective

Boom Bikes aims to gain insights into the key factors influencing the demand for shared bikes in the American market by addressing the following questions:

Identify Significant Predictors: We intend to determine which independent variables play a significant role in predicting the demand for shared bikes. In other words, we want to recognize the variables that have a substantial impact on bike rental demand.

Evaluate Predictive Power: Once we identify these significant variables, we will assess how effectively they describe or predict the variations in bike rental demand. This step involves quantifying the predictive power of these variables in explaining the fluctuations in demand.

By addressing these questions, we can gain a comprehensive understanding of the drivers behind bike rental demand and construct a robust predictive model that helps Boom Bikes tailor their business strategy to meet customer expectations effectively.

## ML Requirements

- numpy - Version 1.23.5
- pandas - Version 1.5.3
- seaborn - Version 0.12.2
- matplotlib - Version 3.7.0
- sklearn - Version 1.2.1
- statsmodels - Version 0.13.5
  
## Dataset

Bike Sharing dataset (data.csv) and Data dictionary was provided to student.

## Conclusion

Significant Predictors for Bike Demand:

After rigorous analysis and model selection, it was found that several variables have a significant impact on predicting the demand for shared bikes. These crucial predictors include:
- Year 2019
- Temperature
- Windspeed
- Season (Spring and Winter)
- Months (July and September)
- Day of the Week (Sunday)
- Weather Situation (Light Rain/Snow and Misty Conditions)
- Description of Predictor Variables:

The process of selecting predictor variables was thorough and systematic. It involved two key steps:

- Recursive Feature Elimination (RFE): This technique helped identify the most relevant predictors by iteratively eliminating less important variables.
- Manual Feature Selection: Additional variables were considered based on their multicollinearity and statistical significance within the model.
- Model Evaluation: The model's performance was assessed against the assumptions of Linear Regression, which include checking for Error Normal distribution and Homoscedasticity.
- Model Fit: The adjusted R-squared value, a measure of how well the model fits the data, was found to be 0.829. This suggests that the selected predictor variables collectively explain a substantial portion of the variance in bike demand, indicating a good fit for the model.
- These findings demonstrate a well-thought-out and data-driven approach to identify and describe the significant predictors for bike demand, ensuring the model's effectiveness in making predictions.
