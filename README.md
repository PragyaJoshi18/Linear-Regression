# Linear-Regression
Linear regression is a predictive modeling method used to forecast a numerical dependent variable based on one or more independent variables. In predictive modeling, "regression" typically refers to tasks that involve predicting a real number, as opposed to "classification," which involves predicting a category or class. The term "linear" in linear regression denotes that the technique models data using a linear combination of the independent variables. A linear combination is an expression where one or more variables are multiplied by a constant factor and then summed. For linear regression with a single independent variable, the linear combination can be expressed as:

response = intercept + constant * explanatory

The right side of the equation defines a line with a specific y-intercept and a slope multiplied by the explanatory variable. In its simplest form, linear regression fits a straight line to the dependent variable. The model is designed to fit a line that minimizes the squared differences (also called errors or residuals). While we won't delve into the math behind how the model minimizes these squared errors, the outcome is a line intended to provide the "best fit" for the data. Since linear regression fits data with a line, it is most effective when there is a linear relationship between the dependent and independent variables.

Let's use the mtcars dataset and linear regression to predict vehicle gas mileage based on vehicle weight. 
