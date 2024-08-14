# Rainfall Prediction Project

This project involves building a classifier to predict whether there will be rain the following day. Using a dataset provided by the Australian Government's Bureau of Meteorology, the project focuses on cleaning the data and applying different machine learning algorithms to build predictive models. The models are evaluated using various metrics to determine their accuracy and effectiveness.

## Project Objectives

- **Data Cleaning:** Preprocess and clean the rainfall dataset to make it suitable for machine learning.
- **Model Building:** Apply multiple classification algorithms to predict rainfall, including:
  1. Linear Regression
  2. K-Nearest Neighbors (KNN)
  3. Decision Trees
  4. Logistic Regression
  5. Support Vector Machines (SVM)
- **Model Evaluation:** Evaluate the performance of each model using the following metrics:
  1. Accuracy Score
  2. Jaccard Index
  3. F1-Score
  4. Logarithmic Loss (LogLoss)
  5. Mean Absolute Error (MAE)
  6. Mean Squared Error (MSE)
  7. R-squared Score (R2)

## Dataset

The dataset used in this project is sourced from the Australian Government's Bureau of Meteorology. It contains various weather-related features that are used to predict whether it will rain the following day.

- **Source:** [Bureau of Meteorology Rainfall Dataset](https://example.com) (or download it from the given link)
- **Features:** The dataset includes attributes such as temperature, humidity, wind speed, and others relevant to predicting rainfall.

## Project Structure

- **Data Preparation Notebook:**
  - `data_cleaning.ipynb`: Contains the steps to clean and preprocess the dataset.
  
- **Modeling Notebooks:**
  - `linear_regression.ipynb`: Building and evaluating the Linear Regression model.
  - `knn.ipynb`: Building and evaluating the KNN model.
  - `decision_trees.ipynb`: Building and evaluating the Decision Trees model.
  - `logistic_regression.ipynb`: Building and evaluating the Logistic Regression model.
  - `svm.ipynb`: Building and evaluating the SVM model.

- **Evaluation Notebook:**
  - `model_evaluation.ipynb`: A comprehensive analysis of the model performance using various metrics.

## Results

Each model was evaluated using the listed metrics, and the accuracy was compared across all models. The final results and findings are documented in the evaluation notebook.

### Key Findings

- **Best Performing Model:** [Logistic Regression]

## Conclusion
This project demonstrates the application of various machine learning algorithms to predict rainfall, providing insights into the strengths and weaknesses of different models. The comprehensive evaluation metrics help in selecting the most appropriate model for the task.
