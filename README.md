# Loan Eligibility Prediction

Welcome to the Loan Eligibility Prediction project! This repository contains code and resources for predicting loan eligibility using various machine learning algorithms.

## Project Overview

This project aims to predict loan eligibility based on applicant information such as income, credit history, and employment status. By comparing the performance of different machine learning models, we can identify the most accurate method for predicting loan eligibility, helping financial institutions streamline their approval processes.

## Key Features

- Algorithms Implemented:
  - Decision Tree
  - Random Forest
  - Naive Bayes

- Data Manipulation and Visualization:
  - Pandas
  - NumPy
  - Matplotlib

## Results

- Decision Tree: 61.7% accuracy
- Random Forest: 77.2% accuracy
- Naive Bayes: 83.7% accuracy (best performance)

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Sanika2511/Loan_Eligibility_Prediction.git

Project Workflow
1. Importing Libraries
The project begins with importing necessary libraries like Pandas, NumPy, and Matplotlib.

2. Loading the Dataset
The dataset loan-train.csv is loaded and basic exploratory data analysis (EDA) is performed.

3. Data Visualization
Several plots and visualizations are created to understand the distribution of the data.

4. Data Preprocessing
Normalizing data
Handling missing values
Encoding categorical variables
Scaling the dataset
5. Model Training and Evaluation
Three different machine learning models are trained and evaluated:
Decision Tree Classifier
Random Forest Classifier
Naive Bayes Classifier
6. Predicting Test Data
The best-performing model (Naive Bayes) is used to predict the loan eligibility on a separate test dataset loan-test.csv.

Usage :
The Jupyter Notebook Loan_Eligibility_Prediction.ipynb contains all the steps to preprocess the data, train the models, evaluate their performance, and visualize the results. Follow the comments and markdown cells in the notebook for detailed explanations.

Contributing :
Contributions are welcome! If you have any suggestions or improvements, feel free to fork the repository and submit a pull request. You can also open an issue for any bug reports or feature requests.

Feedback :
I'd love to hear your thoughts and feedback on this project. Feel free to connect with me on LinkedIn or open an issue in this repository.

License :
This project is licensed under the MIT License.

