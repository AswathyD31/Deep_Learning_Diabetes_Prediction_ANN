# Deep Learning - Predicting Diabetes Progression Using Artificial Neural Networks

# Project Overview
This project focuses on building an Artificial Neural Network (ANN) to predict the progression of diabetes based on a dataset of medical features. The goal is to create a predictive model that aids healthcare professionals in understanding the factors influencing diabetes progression and helps design better treatment plans and preventive measures.

## Dataset
The dataset used is the Diabetes Dataset from the sklearn library. It includes 10 baseline variables (age, sex, BMI, blood pressure, and six blood serum measurements) and a quantitative measure of diabetes progression one year after baseline.

# Features:

+ Age
+ Sex
+ BMI
+ Blood Pressure
+ Six blood serum measurements: S1 to S6

+ Target:

A continuous measure of diabetes progression after one year.

# Steps Involved

## Loading and Preprocessing the Dataset:

* Load the dataset using sklearn.datasets.load_diabetes.
  
* Normalize the features using Min-Max Scaling for better compatibility with ANN models.
  
* Handle outliers and transform skewed features to improve data quality.

## Exploratory Data Analysis (EDA):

* Visualize the distribution of features and the target variable.
* Understand relationships between features and the target using scatterplots and correlation matrices.

## Model Building:

* Design and implement a simple ANN architecture using TensorFlow/Keras.
  
* Incorporate at least one hidden layer with appropriate activation functions (e.g., ReLU for hidden layers and linear for the output layer).
  
## Model Training and Evaluation:

* Split the data into training and testing sets.
  
* Train the ANN using a suitable loss function (e.g., Mean Squared Error) and optimizer (e.g., Adam).
  
* Evaluate model performance using metrics such as Mean Squared Error (MSE) and R² Score.

## Improving the Model:

* Experiment with hyperparameters (e.g., learning rate, batch size) and architectures (e.g., number of layers and neurons) to enhance performance.
  
* Compare the performance of the improved model with the baseline ANN.

## Insights and Analysis:

* Provide a detailed interpretation of the model results.
  
* Highlight the most significant features influencing diabetes progression.

## Technical Requirements

* Programming Language: Python
  
### Libraries Used:

* sklearn for loading the dataset and preprocessing
  
* numpy and pandas for data manipulation
  
* matplotlib and seaborn for visualization
 
* tensorflow/keras for building and training the ANN

## Key Results
The project delivers:

* A trained ANN model capable of predicting diabetes progression with reasonable accuracy.
  
* Insights into the most influential features affecting diabetes progression.
  
* Visualizations and metrics to evaluate model performance.

# Conclusion
_______
This project demonstrates the application of Deep Learning in healthcare for predicting disease progression. By leveraging an ANN, we provide a tool for understanding diabetes dynamics and aiding in effective clinical decision-making.
