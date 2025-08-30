# House_price_prediction
California House Price Prediction  This project demonstrates an XGBoost Regressor model, built with Python and Scikit-learn, to predict California house prices. It achieved an R-squared score of 0.83 on the test data. The project showcases a full machine learning pipeline from data processing with Pandas to model evaluation.


Project Title: California House Price Prediction
Description

This project demonstrates the development and evaluation of a machine learning model for predicting the median house values in California districts. The goal is to build a regression model that can accurately estimate a house's price based on key features like median income, house age, average number of rooms, and geographical location.

Dataset

The model is built using the California Housing dataset, a classic dataset for regression tasks. It contains 20,640 instances with 8 numerical features and the target variable, which is the median house value.

Technologies & Libraries

Python: The core programming language used for the project.

Jupyter Notebook / Google Colab: The environment used for development and data analysis.

Pandas: Used for data manipulation and loading the dataset into a DataFrame.

NumPy: Essential for numerical operations and handling arrays.

Matplotlib & Seaborn: Used for data visualization, including creating a heatmap to understand the correlation between different features.

Scikit-learn: A crucial library for machine learning tasks, used for splitting the data into training and testing sets and for evaluating the model's performance.

XGBoost (XGBRegressor): The primary machine learning algorithm used for building the regression model.

Methodology

Data Loading and Exploration: The California Housing dataset was loaded into a Pandas DataFrame. Initial checks were performed to understand the dataset's structure, identify missing values (none were found), and view statistical measures.

Data Preprocessing and Analysis: A correlation heatmap was generated using Seaborn and Matplotlib to visualize the relationships between the features and the target variable.

Model Training: The dataset was split into training and testing sets. An XGBoost Regressor model was initialized and trained on the training data.

Model Evaluation: The trained model was evaluated on both the training and test datasets. Performance was measured using:

R-squared Error: A score of 0.94 was achieved on the training data, and a score of 0.83 on the test data.

Mean Absolute Error (MAE): The MAE was calculated to be 0.19 on the training data and 0.31 on the test data, providing a clear measure of the average prediction error.

Visualization: A scatter plot was created to visually compare the actual house prices against the model's predicted prices, providing a clear representation of the model's performance.

Conclusion

The project successfully demonstrates the entire machine learning pipeline for a regression problem, from data analysis and model training to evaluation. The XGBoost Regressor proved to be an effective algorithm for this task, with an R-squared score of 0.83 on the test set, indicating a strong predictive capability.
