# Sales Prediction

# Introduction
This project aims to predict product sales based on advertising expenditures across different channels. Using a dataset containing TV, radio, and newspaper advertisement investments, we developed a linear regression model to understand their impact on sales.  

# Data and Methodology
The dataset includes three independent variables: TV, radio, and newspaper, while sales is the target variable. The data was split into 80% training and 20% testing. A linear regression model was trained to learn the relationship between advertising spend and sales.  

# Model Performance
The model was evaluated using key metrics:  
- **Mean Absolute Error (MAE):** Measures the average prediction error.  
- **Root Mean Squared Error (RMSE):** Indicates the typical deviation from actual sales.  
- **R-squared (R²) Score:** Measures how well the model explains sales variations.  

TV and radio advertisements showed a strong impact on sales, while newspaper ads had minimal influence.  

# Visualizations and Insights

# 1. Actual vs. Predicted Sales
This scatter plot shows how well the model predicts sales. The red line represents perfect predictions, and points close to this line indicate accurate predictions.  

![image alt](https://github.com/Engr-Usman-Ali/codealpha_tasks_Sales_Prediction/blob/80f8a6d8dc86db674f4f30b009240053fe0c5fb1/Actual%20vs%20predicted.png)

# 2. Residual Distribution
The histogram of residuals (errors) helps assess model accuracy. A normal distribution suggests a well-fitted model.  

![image alt](https://github.com/Engr-Usman-Ali/codealpha_tasks_Sales_Prediction/blob/80f8a6d8dc86db674f4f30b009240053fe0c5fb1/Distribution.png)

# 3. Feature Importance
This bar chart shows the impact of each advertisement type on sales. TV has the highest effect, followed by radio, while newspapers contribute the least.  

![image alt](https://github.com/Engr-Usman-Ali/codealpha_tasks_Sales_Prediction/blob/80f8a6d8dc86db674f4f30b009240053fe0c5fb1/importance.png)

# Conclusion
The model effectively predicts sales, highlighting that TV and radio ads are the most effective for increasing sales. Future improvements could include testing more complex models or adding online advertising data for better predictions.


