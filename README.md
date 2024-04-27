# Term Deposit Subscription Prediction Project


## Overview

This repository contains the code and resources for a machine learning project aimed at predicting whether a client will subscribe to a term deposit. The project utilizes various machine learning algorithms and techniques to analyze a dataset containing information about clients and their interactions with a bank's marketing campaigns. The dataset used in the projet contains around 40,000 samples. That means that the bank made calls to around 40,000 people. But very small percentage of the the total actually subscribed to the term deposit, which is very inefficient. We can use different Machine Learning algorithms to make a predictive model based on the features of the people that are to be contacted and predict whether a person will subscribe to the term deposit or not. This way we can narrow down our efforts to the people that has the highest chance of opting to subscribe the term deposit

## Project Structure

The repository is organized as follows:

- **ipynb_checkpoints/**: Directory containing checkpoints of your notebook's state, allowing you to revert back to previous versions if needed.
- **pkl files/**: Directory containing trained machine learning models saved as pickle (.pkl) files.
- **README.md**: Comprehensive documentation about the project, including project overview, setup instructions, usage guide, and acknowledgments.
- **Term Deposit Subscription Prediction.ipynb**: The jupyter notebook file for this project. It contains the all the code for the project 
- **bank-additional-full.csv**: The file that is used as dataset for this project
- **bank-additional-names.txt**: File containing the information about the dataset
- **requirements.txt**: Text file listing all the Python packages required to run the code.

## Setup Instructions

To set up the project environment, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/term-deposit-subscription-prediction.git
   
2. Navigate to the project directory:
   
   ```bash
   cd term-deposit-subscription-prediction
   
3. Create a virtual environment (optional but recommended):
   
   ```bash
   python -m venv venv

4. Activate the virtual environment:
   1. On Windows:
      ```bash
      venv\Scripts\activate
   2. On macOS and Linux:
      ```bash
      source venv/bin/activate
5. Install the required Python packages:
   ```bash
   pip install -r requirements.txt


## Usage Guide

The project can be used for the following purposes:

- Exploring the dataset and performing data analysis.
- Preprocessing the data, including handling missing values, encoding categorical variables, and scaling features.
- Building machine learning models using various algorithms such as logistic regression, random forest, support vector machines, XGBoost, and Naive Bayes.
- Evaluating model performance using metrics like accuracy, precision, recall, and F1-score.
- Saving trained models for future use and deployment.

Refer to the Jupyter notebook for detailed code and explanations.


## Acknowledgments

- The dataset used in this project is sourced from UCI's Machine Learning Dataset Repository.
- [Link the dataset](http://archive.ics.uci.edu/ml/datasets/Bank+Marketing)