# Failure Type Prediction Project
## Overview
This project aims to predict the failure type in a given dataset using various machine learning algorithms. The project includes data preprocessing, visualization, balancing the dataset, and applying machine learning models to predict failure types.

## Table of Contents
* Installation
* Data Description
* Exploratory Data Analysis (EDA)
* Data Preprocessing
* Model Training and Evaluation
* Results
* Contributing
* License
### Installation
To run this project, you need to have Python and the following libraries installed:

* pandas
* matplotlib
* seaborn
* scikit-learn
* imbalanced-learn
* xgboost

## Data Description
The dataset used in this project is stored in a CSV file within a zip archive. The dataset contains various features and a target variable indicating the type of failure.

## Exploratory Data Analysis (EDA)
The EDA section includes:

* Checking the shape of the dataset.
* Descriptive statistics of the dataset.
* Missing values analysis.
* Identifying and handling duplicate records.
* Visualizing the distribution of the target variable.
* Plotting histograms and pair plots for numerical features.
## Data Preprocessing
1-Label Encoding: Converting categorical variables into numerical values.

2-Balancing the Dataset: Using SMOTE (Synthetic Minority Over-sampling Technique) to handle class imbalance.

3-Standardization: Scaling the features using StandardScaler.

4-Train-Test Split: Splitting the data into training and testing sets.

## Model Training and Evaluation
The following machine learning models are trained and evaluated:

1-Decision Tree Classifier

2-Random Forest Classifier

3-XGBoost Classifier

The models are evaluated based on their accuracy on both the training and testing datasets.

## Results
The results of the models' performance are compared, and the best model is selected based on the highest accuracy on the testing dataset.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the Apache License 2.0.
