# Lin_Reg_USA_Housing
This is a comprehensive analysis of USA_housing Dataset.
Main focus is on Linear Regression.
Project is to help real estate agent in predicting housing prices for regions in the USA.  
Created a model so that it allows agent to put in a few features like (Avg area, location, area population and number of bedrooms) of a house and returns back an estimate of what the house would sell for.

For Analysis agent has provide data for USA Housing with 5000 entries.

Exploratory analysis showed positive correlation between price and  other features avg area income is .64, area of property is .34 and area population is .41.
multiple_linear_regression model is created for prediction. data is trained on 70 % of data, and then tested on 30 % of data.
The Co-efficient gave following results.
Comments added in code, explains each step.
Different models are built on a number of parameters, which are explained in code.
Model is checked for multicolinearity and to improve performance is processed through Backward Evaluation.
Models are evaluated using R-score, MSE.

Holding all other features fixed, a 1 unit increase in Avg. Area Income is associated with an *increase of $21.52 *.
Holding all other features fixed, a 1 unit increase in Avg. Area House Age is associated with an *increase of $164883.28 *.
Holding all other features fixed, a 1 unit increase in Avg. Area Number of Rooms is associated with an *increase of $122368.67 *.
Holding all other features fixed, a 1 unit increase in Avg. Area Number of Bedrooms is associated with an *increase of $2233.80 *.
Holding all other features fixed, a 1 unit increase in Area Population is associated with an *increase of $15.15 *.

