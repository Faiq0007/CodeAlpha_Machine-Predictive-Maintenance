# Predictive Maintenance - Feature Engineering

This repository contains the work I did during my internship at **CodeAlpha**, where I applied **feature engineering** techniques to a **Predictive Maintenance** dataset. The goal was to predict machine failures and classify the type of failure based on machine sensor data.

## Dataset Overview

The dataset used is the **Machine Predictive Maintenance Classification Dataset**, which contains critical machine operational data, including:

- Air temperature [K]
- Process temperature [K]
- Rotational speed [rpm]
- Torque [Nm]
- Tool wear [min]
- Target (Failure Prediction: Binary)
- Failure Type (Multi-class classification)

## Task

The task was to create additional features from the dataset that would help improve the performance of machine learning models in predicting:

- Whether a machine will fail (binary classification)
- What type of failure will occur (multi-class classification)

### Feature Engineering Techniques Used:

1. **Rolling Mean Features**: To capture trends over time (e.g., moving averages of air temperature, torque).
2. **Interaction Features**: To create new features that capture relationships between different variables (e.g., air temperature * process temperature).
3. **Rolling Max Features**: To track peak values over a specific window of time (e.g., maximum rotational speed, tool wear).

These features were used to improve model performance, making predictions more accurate.

For more insights or collaborations, feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/faiq-syed-7494b5197/)
