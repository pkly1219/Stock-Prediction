# Predict Stock Prices
This project demonstrates the prediction of stock prices using three different machine learning models: Support Vector Regression (SVR), Support Vector Classification (SVC), and Random Forest Classifier (RFC). The models were trained on historical stock data and evaluated based on their accuracy.

## Project Overview
The goal of the project is to predict stock price movements using machine learning techniques. Three methods were implemented and evaluated in separate Jupyter notebooks:

Support Vector Regression (SVR): Achieved a 50% accuracy.
Support Vector Classification (SVC): Achieved a 52% accuracy.
Random Forest Classifier (RFC): Achieved the highest accuracy of 79%.
The models were built and evaluated using a dataset that includes historical stock price data, such as the adjusted closing price over time.

## Methods
1. Support Vector Regression (SVR)

- Linear SVR
- Polynomial SVR
- RBF SVR
SVR models were used to predict stock prices based on a set of features derived from historical stock data. Linear, polynomial, and RBF kernels were applied. The best accuracy achieved was 50%.

2. Support Vector Classification (SVC)

SVC was used to classify stock movement as either up or down. The accuracy was slightly better than SVR, reaching 52%.

3. Random Forest Classifier (RFC)

RFC performed the best in this project, with an accuracy of 79%. This model is based on an ensemble of decision trees, making it robust to overfitting and capable of capturing more complex patterns in the data.
## Results
1. SVR (Support Vector Regression):

Linear SVR, Polynomial SVR, and RBF SVR were applied, but the RBF SVR achieved the highest accuracy (50%).
2. SVC (Support Vector Classification):

The SVC model performed slightly better than the SVR, with an accuracy of 52%.
3. Random Forest Classifier:

This model significantly outperformed both SVR and SVC, with an accuracy of 79%.
## Installation and Setup
Clone this repository.

git clone https://github.com/yourusername/PredictStock.git

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
matplotlib
seaborn

## Conclusion
The Random Forest Classifier (RFC) significantly outperforms the other models, making it the best approach for predicting stock price movements in this project.

