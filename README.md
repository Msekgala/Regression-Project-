##### Regression-Project-

Excecutive Summary:
As the PTSD data scientist we have been tasked to analyze and predict the average temperature from the agri-food sector, using the data received from FAO and IPCC. The dataset comprises of about 30 features and +7000 records.
While analyzing the data given, one feature being countries we have chosen to work with the dataset from South Africa. The country as we know it has diverse demographics, a resource-rich country and an attractive tourism industry.

Problem Statement: To analyze and develop a predictive model that accurately forecasts the average temperature for South Africa over 1990 to 2020 based on the manure management, years, urban population, total emission, rice cultivation and IPPU in order to determine the impact of food production.

How we determined the features we will be using was how relevant each dataset to South Africas climate. We created pair plots so our decision on the features  can be determined using the given data and usable for the predictive model. Forest fires was one of our consideration but on the pair plot against average temperature data was not showing any relevance.

While doing some analysis on the chosen features we need to check for multicollinearity. This arises when at least two or more independent variables in a model are highly correlated, indicating a strong linear relationship among the predictor variables. We will use the Ordinary Least Squares summary as it can provide insight on potential errors, model evaluation, coefficient interpretation and potential model improvement. This gives a deeper underlying relationships between variables.

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
  
Based on our models, it seems the decision tree worked better with our data. Using the random forest to improve our model even further.

Conclusion: Our models did not perform as best as we had set out and this could be due to various things. In future we would also take datasets of 2 countries to run parallel to each to see how the models perform. This will help with better training and testing of our model

Trello Board Link: https://trello.com/b/w5UNwLtb/regression-project
Google Slides: https://docs.google.com/presentation/d/1dwN097_VOAcucX2hrlJso0DXM0a-wqJWhXeGergKfkU/edit?usp=sharing



