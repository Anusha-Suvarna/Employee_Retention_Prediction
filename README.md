# Employee Retention Prediction

This project focuses on predicting employee retention within an organization using machine learning models and deep learning techniques. The primary goal is to analyze historical employee data, identify influential factors contributing to retention, and build predictive models to forecast potential cases of employee retention.

## Table of Contents

- [Introduction](#introduction)
- [Dataset Overview](#dataset-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Models and Techniques](#models-and-techniques)
- [Results](#results)
- [Contributing](#contributing)

## Introduction

Employee retention, the ability to retain valuable staff within a company, is crucial for organizational success. This project delves into exploratory data analysis (EDA), feature engineering, and the application of various machine learning and deep learning models to predict and understand factors influencing employee retention.

## Dataset Overview

The dataset used in this project encompasses employee-related features such as:

- **Demographics**: Age, Gender, Marital Status
- **Job-related Factors**: Job Role, Department, Job Level, Job Satisfaction
- **Work Environment**: Work Accident History, Working Hours, Performance Ratings
- **Employee Performance Indicators**: Years at Company, Promotions, Salary, Satisfaction Level


## Installation

To set up the environment and run this project locally, follow these steps:

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/your-username/employee-retention-prediction.git
    ```

2. Navigate to the project directory.

3. Install the required dependencies listed in the `requirements.txt` file:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Exploratory Data Analysis (EDA)**:
    - Explore the `Employee_Retention_Analysis.ipynb` notebook to understand the dataset's characteristics, distributions, and relationships between features.

2. **Model Building**:
    - Use the `Employee_Retention_Prediction.ipynb` notebook to create and evaluate predictive models for employee retention.

    - Experiment with various algorithms, including:
        - Random Forest Classifier
        - Gradient Boosting Classifier
        - Artificial Neural Networks (Deep Learning)

3. **Evaluation**:
    - Assess model performance using metrics such as accuracy, precision, recall, and F1-score.

## Models and Techniques

This project involves several techniques and libraries, including:

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

## Contributing

Contributions to enhance this project are welcome! If you have suggestions, feature requests, or want to report issues, please open an issue or submit a pull request.

