Churning Customers Prediction
This project aims to develop a deep learning model that can predict customer churn for a telecom company. Customer churn is the loss of customers who stop using the company’s services. It is a major problem that affects the revenues and profitability of the company. Therefore, finding factors that increase customer churn and identifying customers who are likely to churn are important tasks for the company.

Data
The data used for this project is from this link, which contains information about 7043 customers of a telecom company. The data includes 20 features, such as gender, tenure, monthly charges, contract type, etc. The target variable is Churn, which indicates whether the customer left the company within the last month.

Methodology
The steps involved in this project are:

Data preprocessing: Cleaning, encoding, scaling, and splitting the data into train and test sets.
Feature extraction: Selecting the relevant features that can define customer churn using correlation analysis and feature importance methods.
Exploratory data analysis: Exploring the distribution and relationship of the features and the target variable using descriptive statistics and visualization techniques.
Model building: Defining and training a multi-layer perceptron (MLP) model using the functional API of TensorFlow and Keras. The model has three hidden layers with ReLU activation and a sigmoid output layer. The model is optimized using Adam optimizer and binary cross-entropy loss function.
Model evaluation: Evaluating the model’s performance on the test set using accuracy and AUC score metrics. The AUC score measures the ability of the model to distinguish between positive and negative classes.
Model deployment: Creating a web-based platform to host the model using Flask and HTML. The platform allows users to enter new data and get the prediction of customer churn and the confidence factor of the model.
Demo
A short video demonstrating how the web-based platform works can be found here.
