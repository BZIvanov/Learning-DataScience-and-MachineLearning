# Linear Regression (LR)

## Valid data

Linear Regression is sometimes not appropriate depending on the dataset. We can usually visually tell that. Check the 4 examples below for more info.

Anscombe's Quartet: https://en.wikipedia.org/wiki/Anscombe%27s_quartet

Only the top-left dataframe is appropriate for linear regression. The downside with the below example is that it is only when we are working with 1 feature. When we are working with more than feature what we could do is to plot the residual error.

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/Anscombe%27s_quartet_3.svg/850px-Anscombe%27s_quartet_3.svg.png">

## Simple Linear Regressin

### Equation

$${\hat{y} = {b_0} + {b_1}{x_1}}$$

where:

- $\hat{y}$ - dependent variable
- ${b_0}$ - y-intercept (constants)
- ${b_1}$ - slope coefficient
- ${x_1}$ - independent variable

## Multiple Linear Regression

### Equation

$${\hat{y} = {b_0} + {b_1}{x_1} + {b_2}{x_2} + ... + {b_n}{x_n}}$$

where:

- $\hat{y}$ - dependent variable
- ${b_0}$ - y-intercept (constants)
- ${b_1}$ - slope coefficient 1
- ${x_1}$ - independent variable 1
- ${b_n}$ - slope coefficient n
- ${x_n}$ - independent variable n

## Polynomial Linear Regression

### Equation

$${\hat{y} = {b_0} + {b_1}{x_1} + {b_2}{x^2_1} + ... + {b_n}{x^n_1}}$$

## Evaluation metrics

Below are the three most common evaluation metrics for regression problems:

**Mean Absolute Error** (MAE) is the mean of the absolute value of the errors:

$$\frac 1n\sum_{i=1}^n|y_i-\hat{y}_i|$$

**Mean Squared Error** (MSE) is the mean of the squared errors:

$$\frac 1n\sum_{i=1}^n(y_i-\hat{y}_i)^2$$

**Root Mean Squared Error** (RMSE) is the square root of the mean of the squared errors:

$$\sqrt{\frac 1n\sum_{i=1}^n(y_i-\hat{y}_i)^2}$$

Comparing these metrics:

- **MAE** is the easiest to understand, because it's the average error.
- **MSE** is more popular than MAE, because MSE "punishes" larger errors, which tends to be useful in the real world. Larger error is for example error when 1 point on the scatter plot is really off, but the opposite values of the other points can cover that fact.
- **RMSE** is even more popular than MSE, because RMSE is interpretable in the "y" units.

All of these are **loss functions**, because we want to minimize them. They all measure the differences between the predicted values and the actual (ground truth) values of the target variable. Lower values of these metrics indicate better model performance.

## Regularization

Regularization is to solve a few common model issues by:

- minimizing model complexity
- reducing model overfitting
- penalizing the loss function

Types of regularization:

- L1
- L2
- Combining L1 and L2
