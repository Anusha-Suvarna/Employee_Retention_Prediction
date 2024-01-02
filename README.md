# Employee Attrition Prediction

This project focuses on predicting employee attrition within an organization using machine learning models and deep learning techniques. The objective is to analyze historical employee data, identify significant factors contributing to attrition, and create predictive models to forecast potential attrition cases.

## Table of Contents

- [Introduction](#introduction)
- [Dataset Overview](#dataset-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Models and Techniques](#models-and-techniques)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Employee attrition, the departure of staff from a company, poses significant challenges for organizations. Understanding and predicting attrition can help companies take proactive measures to retain valuable employees. This project delves into exploratory data analysis (EDA), feature engineering, and the application of various machine learning and deep learning models to predict employee attrition.

## Dataset Overview

The dataset used in this project comprises employee-related features such as:

- Demographics: Age, Gender, Marital Status
- Job-related Factors: Job Role, Department, Job Level, Job Satisfaction
- Work Environment: Work Accident History, Working Hours, Performance Ratings
- **Employee Performance Indicators**: Years at Company, Promotions, Salary, Satisfaction Level

Dataset Source: [Provide Source/Reference if Applicable]

## Installation

To set up the environment and run this project locally, follow these steps:

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/your-username/employee-attrition-prediction.git
    ```

2. Navigate to the project directory.

3. Install the required dependencies listed in the `requirements.txt` file:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Exploratory Data Analysis (EDA)**:
    - Access and explore the `Employee_Attrition_Analysis.ipynb` notebook to understand the dataset's characteristics, distributions, and relationships between features.

2. **Model Building**:
    - Utilize the `Employee_Attrition_Prediction.ipynb` notebook to build and evaluate predictive models for employee attrition.
    
    - Experiment with various algorithms such as:
        - Random Forest Classifier
        - Gradient Boosting Classifier
        - Artificial Neural Networks (Deep Learning)

3. **Evaluation**:
    - Assess the performance of the models using metrics like accuracy, precision, recall, and F1-score.

## Models and Techniques

This project employs several techniques and libraries, including:

- **Machine Learning Libraries**:
    - `scikit-learn`: for data preprocessing, model building, and evaluation.
    - `pandas` and `numpy`: for data manipulation and analysis.
    - `matplotlib` and `seaborn`: for data visualization.

- **Models Explored**:
    - Random Forest Classifier
    - Gradient Boosting Classifier
    - Artificial Neural Networks using TensorFlow/Keras

## Results

The project achieved the following results on the test set:

- **Random Forest Classifier**:
    - Accuracy: 88%
    - Precision and Recall for Class 0: High
    - Precision and Recall for Class 1: Moderate

- **Gradient Boosting Classifier** (if applicable):
    - Accuracy: XX%
    - Precision and Recall for Class 0: XX
    - Precision and Recall for Class 1: XX

- **Deep Learning Model**:
    - Accuracy: 87%
    - Precision and Recall for Class 0: High
    - Precision and Recall for Class 1: Moderate

