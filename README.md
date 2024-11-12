##### Regression-Project-

Excecutive Summary:
As PTSD Data Scientists, we were tasked with analyzing and predicting average temperature trends in South Africa. We utilized a dataset of approximately 7,000 records and 30 features, sourced from the FAO and IPCC. By 
focusing on South Africa, a country with diverse demographics, significant natural resources, and a thriving tourism industry, we aim to gain valuable insights into the impact of various factors, including agricultural 
practices and environmental conditions, on temperature patterns.

Problem Statement: To analyze and develop a predictive model that accurately forecasts the average temperature for South Africa over the period 1990 to 2020. We will also conduct feature selection to identify the most 
relevant factors influencing temperature, such as manure management, urban population, total emissions, rice cultivation, and IPPU. The goal is to gain insights into the potential impact of food production practices and 
environmental factors on temperature trends.

To ensure the reliability of our model, we will assess the features for multicollinearity. This statistical phenomenon occurs when two or more independent variables are highly correlated, potentially leading to unstable model estimates and difficulties in interpreting the impact of individual features. By examining the Ordinary Least Squares (OLS) regression summary, we can gain insights into potential multicollinearity issues, evaluate model performance, interpret coefficient estimates, and identify areas for improvement. This analysis will provide a deeper understanding of the underlying relationships between the variables and guide our feature selection process.

The below are some of the models that we have used in our project, included advantages and disadvantages
1. Mulitiple Linear Regression - relationship between a dependent variable and multiple independent variables
   Advantages:
   * It is simple and easy to interpret
   * It can be computatioally efficient, for smaller datasets
   Disadvantages:
   * It assumes a linear relatioship between the independent and dependent variables, which might not always be the case for real world scenarios
   * It is sensitivite to multicollinearity
     
2. Ridge Regression - regularization technique used to address the issue of multicollinearity in linear regression models
   Advantages:
   * It can handle multicollinearity
   * Ability to shrink coefficients of less important features to zero
   Disadvantages:
   * It introduces bias to reduce variance, which might leas to less accurate predictions
     
3. Decision Tree Model - represent data by partitioning it into different sections based on questions asked of predictive variables in the data.
   Advantages:
   * It is able to capture comples, non-linear relationships between variables
   * It is easy to interpret
   Disadvantages:
   * Prone to overfitting
   * Can be sensitive to noise in the data
  
Conclusion: While our initial models did not achieve the level of performance we had anticipated, we believe there are several avenues for improvement. One potential direction is to expand our dataset to include data from multiple countries, enabling more robust training and testing.
Our preliminary analysis suggests that Decision Tree models may be particularly well-suited to our dataset. We plan to further explore the potential of ensemble methods, such as Random Forest, to enhance predictive accuracy and model robustness.

Trello Board Link: https://trello.com/b/w5UNwLtb/regression-project
Google Slides: https://docs.google.com/presentation/d/1dwN097_VOAcucX2hrlJso0DXM0a-wqJWhXeGergKfkU/edit?usp=sharing

