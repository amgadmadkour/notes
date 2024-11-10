# Linear Regression

A statistical modeling technique that is used for understanding the relationship between a dependent variable and a one or more independent variables.

For example, a house price is considered a dependent variable because its what we want to predict while the independent variables would be the house size, number of rooms, and so forth. A linear regression model helps us **predict the value of dependent variable** based on the independent variables. The objective of linear regression is to determine the best-fit line that minimizes the difference between the dependent variable and independent variables. Univariate linear regression involves only one independent variable, e.g. house size being the independent variable for predicting the price. The equation of a linear regression model is a straight-line equation represented as follows:

$$f_{w,b}(x^{(i)}) = wx^{(i)} + b$$

where

- $f$ is a function that takes the input x
- $x$ is the input feature or independent variable
- $x^{(i)}$ is the ith instance of input $x$
- $w$, $b$ are called the parameters

$w$ and $b$ are the parameters of the model. In machine learning, parameters of a model are the variable used during training in order to improve the model. Parameters are also called *coefficients* or *weights*.
