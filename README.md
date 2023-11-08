# Machine Learning Trading Bot

## Overview 

The goal of this assignment was to act as a financial advisor at a top-five global financial advisory firm and enhance existing algorithmic trading strategies to maintain and surpass the firm's competitive edge in the market. This involved establishing a performance baseline with the current trading algorithm, refining it, introducing a new machine learning classifier, and assessing its impact on performance improvement.

## Table of Contents 

* Establish a Baseline Performance
* Tune the Baseline Trading Algorithm
* Evaluate a New Machine Learning Classifier
* Create an Evaluation Report

## Establish a Baseline Performance 

### Baseline Performance 

![SVM Model Classification Report](Starter_Code/Images/svm_model_report.png)

![SVM Model Cumalative Returns Plot](Starter_Code/Images/svm_model_returns_plot.png)

Explain that this section focuses on setting up a baseline for the trading algorithm and includes the following steps:

* Open the Jupyter notebook and run the provided starter code.
* Import the OHLCV dataset into a Pandas DataFrame.
* Generate trading signals using short- and long-window SMA values.
* Split the data into training and testing datasets.
* Use the SVC classifier model from SKLearn's support vector machine (SVM) learning method to fit the training data and make predictions.
* Review the classification report associated with the SVC model predictions.
* Create a predictions DataFrame with columns for "Predicted" values, "Actual Returns," and "Strategy Returns."
* Create a cumulative return plot that compares actual returns with strategy returns. Save a PNG image of this plot.
* Write conclusions about the baseline trading algorithm's performance in the README.md file, supported by the saved PNG image.

## Tune the Baseline Trading Alogrithm 

![SVM Model Classification Report SMA Adjusted Values](Starter_Code/Images/svm_model_report_sma_adjusted_values.png)

![SVM Model Cumalative Returns Plot SMA Adjusted Values](Starter_Code/Images/svm_model_returns_plot_sma_adjusted_values.png)


Explain that this section focuses on setting up a baseline for the trading algorithm and includes the following steps:

* Open the Jupyter notebook and run the provided starter code.
* Import the OHLCV dataset into a Pandas DataFrame.
* Generate trading signals using short- and long-window SMA values.
* Split the data into training and testing datasets.
* Use the SVC classifier model from SKLearn's support vector machine (SVM) learning method to fit the training data and make predictions.
* Review the classification report associated with the SVC model predictions.
* Create a predictions DataFrame with columns for "Predicted" values, "Actual Returns," and "Strategy Returns."
* Create a cumulative return plot that compares actual returns with strategy returns. Save a PNG image of this plot.
* Write conclusions about the baseline trading algorithm's performance in the README.md file, supported by the saved PNG image.

## Evaluate a New Machine Learning Classifier 

Explain that this section involves applying a different machine learning classifier to the provided parameters and includes the following steps:

Import a new classifier (e.g., AdaBoost, DecisionTreeClassifier, or LogisticRegression).
Fit another model with the new classifier using the original training data.
Backtest the new model and save a PNG image of the cumulative product of the actual returns vs. the strategy returns.
Write conclusions about the performance of the new model in the README.md file, comparing it to the provided baseline model and the tuned trading algorithm.

## Create an Evaluation Report

Explain that this section requires you to add a summary evaluation report at the end of the README.md file. The report should contain your final conclusions and analysis, supported by the PNG images you created throughout the assignment.

Feel free to expand upon this outline, adding details or formatting as needed, to create a comprehensive README that guides users through the assignment and your findings.
