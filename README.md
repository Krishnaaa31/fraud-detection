# fraud-detection
# Credit Card Fraud Detection

This repository contains a Python script for detecting credit card fraud using machine learning techniques. The dataset used is the `creditcard.csv` dataset, containing transactions made by European cardholders in September 2013.

## Overview

The dataset consists of 284,807 transactions, of which 492 are fraudulent. This imbalance necessitates careful handling of the data and choice of algorithms to effectively detect fraud. The script explores various models and preprocessing steps to build a robust fraud detection system.

## Features

- **Data Loading and Exploration**: Initial loading and basic exploration of the dataset.
- **Data Visualization**: Visual representations of class distribution and key features.
- **Feature Engineering**: Creation and transformation of features to improve model performance.
- **Model Training and Evaluation**: Training various models and evaluating their performance using appropriate metrics.

## Libraries Used

- **NumPy**: For numerical operations.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For creating static, animated, and interactive visualizations.
- **Seaborn**: For making statistical graphics.
- **scikit-learn**: For machine learning, including model training, evaluation, and preprocessing.

## Usage

1. **Data Loading and Exploration**
    - Load the dataset using Pandas.
    - Print the shape, first 5 rows, statistical description, and data types of the dataset.

2. **Data Visualization**
    - Visualize the class distribution using a pie chart.
    - Analyze the `Time` variable to detect any trends by converting it into hours and plotting histograms.
    - Analyze the `Amount` variable by plotting histograms with a logarithmic scale.

3. **Feature Engineering**
    - Standardize the `Amount` feature using `StandardScaler`.
    - Drop unnecessary features such as `Time` after extracting useful information.

4. **Model Training and Evaluation**
    - Split the data into training and test sets.
    - Train models using `GaussianNB` and `LogisticRegression`.
    - Evaluate model performance using confusion matrix, recall, precision, F1 score, accuracy, and ROC AUC.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
