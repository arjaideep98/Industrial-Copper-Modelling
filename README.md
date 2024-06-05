# Industrial-Copper-Modelling

**Copper Industry Data Analysis and Prediction Project**

This project addresses challenges in the copper industry related to sales and lead classification using machine learning techniques. It includes building regression and classification models to predict selling prices and lead statuses, respectively. Additionally, a Streamlit web application is developed for interactive prediction.

**Problem Statement**

The copper industry faces issues with skewed and noisy data affecting manual predictions of sales prices and lead classifications. Machine learning regression and classification models are proposed to mitigate these challenges and optimize pricing decisions and lead evaluation.

**Objectives**

1.	Explore skewness and outliers in the dataset.
2.	Transform the data and perform necessary cleaning and preprocessing steps.
3.	Develop a machine learning regression model to predict selling prices.
4.	Build a machine learning classification model to predict lead statuses.
5.	Create a Streamlit web page for interactive prediction of selling prices and lead statuses.

**Approach**

1.	Data Understanding: Identify variable types and distributions, handle rubbish values, and treat reference columns as categorical.
2.	Data Preprocessing: Handle missing values, treat outliers, identify and treat skewness, and encode categorical variables.
3.	Exploratory Data Analysis (EDA): Visualize outliers and skewness before and after treatment using Seaborn's plotting functions.
4.	Feature Engineering: Engineer new features if applicable and drop highly correlated columns.
5.	Model Building and Evaluation: Split data, train and evaluate regression and classification models, optimize hyperparameters, and interpret model results.
6.	Model GUI: Create an interactive Streamlit page for prediction with input fields for each column value except for the target variable.

**Usage**

1.	Install required Python libraries.
2.	Run data preprocessing scripts.
3.	Train regression and classification models using scripts.
4.	Run the Streamlit web application using the code in the web_app/ directory.
5.	Input data into the web application for predictions.
