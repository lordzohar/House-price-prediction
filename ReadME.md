# House Price Prediction Project

## Objective
The objective of this project is to predict house prices by applying various machine learning algorithms to explore different housing datasets and comparing their performance. This includes regression models such as K-Nearest Neighbors, Random Forest, Kernelized Ridge Regression, and Neural Networks, implemented using Python. The algorithms were selected for assessment with the intent to compare their relative performance at this task. These models are applied to the Boston Housing Dataset, the California Housing Dataset, Ames Housing, and the United Kingdom Dataset. The performance of each model is visualized and compared.

## Datasets
- **Boston Housing Dataset**
- **California Housing Dataset**
- **Ames Housing Dataset**
- **United Kingdom Housing Dataset**

## Algorithms Used
- **K-Nearest Neighbors (kNN)**
- **Random Forest**
- **Kernelized Ridge Regression**
- **Neural Networks**


## Preprocessing Steps
The preprocessing steps for each dataset include:
- Handling missing values
- Encoding categorical variables
- Feature scaling
- Splitting the dataset into training and testing sets using five-fold cross-validation

## Hyperparameter Tuning
Hyperparameters for the algorithms were optimally selected using the grid search algorithm. The cleaned dataset was split using five-fold cross-validation to reduce the risk of bias. An optimal subset of hyperparameters for the algorithms was selected for the best prediction.

## Results
The Random Forest algorithm was found to consistently perform better than the kNN algorithm in terms of smaller errors and was better suited as a prediction model for the house price problem.

## Visualization
The performance of each model is visualized using various plots, including:
- Scatter plots of predicted vs. actual prices
- Box plots of errors
- Learning curves

## Report
The report details the background knowledge required to implement these models, the preprocessing steps for each dataset, and an analysis of the results.

## Requirements
To run this project, you need to have the following Python libraries installed:
- numpy
- pandas
- scikit-learn
- matplotlib
- seaborn
- tensorflow or pytorch (for neural networks)

