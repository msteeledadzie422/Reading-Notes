# Linear Regressions

1. Can you explain the basic concept of linear regression and its purpose in the context of machine learning and data analysis?
      Regression searches for relationships among variables. For example, you can observe several employees of some company and try to understand how their salaries depend on their features, such as experience, education level, role, city of employment, and so on.
      Generally, in regression analysis, you consider some phenomenon of interest and have a number of observations. Each observation has two or more features. Following the assumption that at least one of the features depends on the others, you try to establish a relation among them.

      In other words, you need to find a function that maps some features or variables to others sufficiently well.

      The dependent features are called the dependent variables, outputs, or responses. The independent features are called the independent variables, inputs, regressors, or predictors.


2. Describe the process of implementing a linear regression model using Python’s Scikit Learn library, including the necessary steps and functions.
      Scikit-learn is a Python package that simplifies the implementation of a wide range of Machine Learning (ML) methods for predictive data analysis, including linear regression.

      Linear regression can be thought of as finding the straight line that best fits a set of scattered data points:

      When creating a linear regressoin model, it is important to consider the following:

      * Best Fit – the straight line in a plot that minimizes the deviation between related scattered data points.
      * Coefficient – also known as a parameter, is the factor a variable is multiplied by. In linear regression, a coefficient represents changes in a Response Variable (see below).
      * Coefficient of Determination – the correlation coefficient denoted as 𝑅². Used to describe the precision or degree of fit in a regression. 
      * Correlation – the relationship between two variables in terms of quantifiable strength and degree, often referred to as the ‘degree of correlation’.  Values range between -1.0 and 1.0. 
      * Dependent Feature – a variable denoted as y in the slope equation y=ax+b. Also known as an Output, or a Response. 
      * Estimated Regression Line – the straight line that best fits a set of scattered data points.
      * Independent Feature – a variable denoted as x in the slope equation y=ax+b. Also known as an Input, or a predictor. 
      * Intercept – the location where the Slope intercepts the Y-axis denoted b in the slope equation y=ax+b. 
      * Least Squares – a method of estimating a Best Fit to data, by minimizing the sum of the squares of the differences between observed and estimated values.
      * Mean – an average of a set of numbers, but in linear regression, Mean is modeled by a linear function.
      * Ordinary Least Squares Regression (OLS) – more commonly known as Linear Regression. 
      * Residual – vertical distance between a data point and the line of regression (see Residual in Figure 1 below).
      * Regression – estimate of predictive change in a variable in relation to changes in other variables (see Predicted Response in Figure 1 below).
      * Regression Model – the ideal formula for approximating a regression.
      * Response Variables – includes both the Predicted Response (the value predicted by the regression) and the Actual Response, which is the actual value of the data point (see Figure 1 below).
      * Slope – the steepness of a line of regression. Slope and Intercept can be used to define the linear relationship between two variables: y=ax+b.
      * Simple Linear Regression – a linear regression that has a single independent variable.


3. What is the purpose of splitting the dataset into train and test sets, and how does this contribute to the evaluation of a machine learning model’s performance?
      In real-world situations, having a complex model and 𝑅² very close to one might also be a sign of overfitting. To check the performance of a model, you should test it with new data—that is, with observations not used to fit, or train, the model.       



