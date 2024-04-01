# Flight-Delay-Prediction
The provided code outlines the development of a machine learning model aimed at predicting flight delays, targeting optimization for the airline industry. Here's a summary:
1. Problem Background and Motivation

    The task involves optimizing a classification model to predict flights likely to experience delays.
    Key stakeholders include investors, customers, and national regulatory bodies in the aviation sector.

2. Libraries & Custom Functions

    Libraries such as NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn, Plotly, and Cufflink are imported for data manipulation, visualization, and machine learning tasks.
    Custom functions are defined for evaluating classification model performance.

3. Data Exploration/Preparation

    Initial evaluation of the dataset is performed, including identifying the target variable and splitting the data into training and testing sets.
    Data normalization is conducted using Z-scores.

4. Machine Learning Model
kNN (k-Nearest Neighbors)

    Multiple kNN models with different values for k are fitted.
    The optimal value for k is determined based on accuracy.

Logistic Model

    A logistic regression model is trained and evaluated.
    Performance comparison between kNN and logistic regression models is conducted using AUC-ROC curves and performance metrics.

5. Deployment of Model

    The logistic regression model is chosen due to its higher AUC value.
    The model is serialized using the Pickle library for deployment.
    A basic Streamlit web application is created for users to input flight details and obtain delay predictions.

This summary outlines the development process from problem understanding to model deployment for predicting flight delays in the airline industry.
