# README

## Linear Approximation Analysis

### Overview

The `LinearApproximationAnalysis` directory contains a comprehensive study on linear approximation of the function √1 + x over the interval [0, 1]. This project is a part of the Deep Learning course, focusing on the application and comparison of various linear regression techniques. The main objective is to understand and visualize the performance of different regression models in approximating a non-linear function.

### File Structure

- `LinearRegressionComparisons.ipynb`: A Jupyter notebook that encapsulates the entire analysis, from data generation to model comparison and visualization.

### Project Details

The notebook `LinearRegressionComparisons.ipynb` is structured to guide you through the following steps:

1. **Data Generation**:
    - Generate N = 10,000 random numbers within the interval [0, 1].
    - Compute the labels yi = √1 + xi for each generated number xi.

2. **Model Implementations and Comparisons**:
    - **Closed-Form Linear Regression**: Implement a linear regression model using the closed-form solution.
    - **Linear Regression with Scikit-Learn**: Utilize the `LinearRegression` model from the scikit-learn library.
    - **Gradient Descent**: Implement linear regression using the gradient descent algorithm.
    - **TensorFlow Linear Regression**: Apply TensorFlow's capabilities to perform linear regression.
    - **Stochastic Gradient Descent**: Implement linear regression using the stochastic gradient descent method.
    - **Mini-Batch Gradient Descent**: Implement linear regression using the mini-batch gradient descent approach.

3. **Performance Visualization**:
    - Plot the graphs of all approximations alongside each other for a visual comparison.
    - Compare the results with the first-degree Taylor approximation of the function √1 + x.

