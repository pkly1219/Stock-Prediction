# Predict Stock Prices

This project demonstrates the prediction of stock prices using three different machine learning models: Support Vector Regression (SVR), Support Vector Classification (SVC), and Random Forest Classifier (RFC). The models were trained on historical stock data and evaluated based on their accuracy.

## Project Overview

The goal of the project is to predict stock price movements using machine learning techniques. Three methods were implemented and evaluated in separate Jupyter notebooks:

Support Vector Regression (SVR)

Support Vector Classification (SVC)

Random Forest Classifier (RFC)

The models were built and evaluated using a dataset that includes historical stock price data, such as the adjusted closing price over time.

## Methods

### 1. Support Vector Regression (SVR)
SVR is a type of Support Vector Machine (SVM) used for regression tasks. It attempts to find a function that deviates from the actual data points by a value no greater than a specified threshold. SVR can be applied with different kernels to model the data in various ways.
- Linear SVR: Fits a straight line to the data. This model assumes that the relationship between the input features and the target variable is linear
- Polynomial SVR: Models the relationship between the features and target variable using a polynomial function, allowing for more complex relationships.
- RBF SVR (Radial Basis Function): Uses a non-linear kernel that transforms the feature space, allowing it to capture more complex patterns in the data.


### 2. Support Vector Classification (SVC)

 SVC is a classification technique that constructs a hyperplane or set of hyperplanes in a high-dimensional space to separate data into different classes. For this project, SVC was used to classify the direction of stock price movement (up or down)

### 3. Random Forest Classifier (RFC)

 RFC is an ensemble learning method used for classification. It operates by constructing multiple decision trees during training and outputs the class that is the mode of the classes (for classification) of the individual trees

## Results

### 1. SVR (Support Vector Regression):

Linear SVR, Polynomial SVR, and RBF SVR were applied, but the RBF SVR achieved the highest accuracy of **50%**.

### 2. SVC (Support Vector Classification):

The SVC model performed slightly better than the SVR, with an accuracy of **52%**.

### 3. Random Forest Classifier:

This model significantly outperformed both SVR and SVC, with an accuracy of **79%**.

## Installation and Setup

Clone this repository.

git clone [https://github.com/yourusername/PredictStock.git](https://github.com/pkly1219/StockProject.git)

Run the Jupyter notebooks in the following order:

PredictStock_ver1.ipynb (SVR Models)
PredictStock_ver2.ipynb (SVC Model)
PredictStock_ver3.ipynb (RFC Model)

## Usage

Each notebook can be executed to run the corresponding model. The notebooks contain the complete code for data preprocessing, model training, evaluation, and visualization of results.

## Dependencies

The project requires the following Python packages:

numpy

pandas

scikit-learn

matplotlib

seaborn

## Conclusion
The Random Forest Classifier (RFC) significantly outperforms the other models, making it the best approach for predicting stock price movements in this project.

