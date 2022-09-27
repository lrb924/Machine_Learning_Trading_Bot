# Machine Learning Trading Bot

### Package Requirements

`pip install x` where x is the below listed packages
* pandas
* numpy
* pathlib
* hvPlot
* Matplotlib
* scikit-learn

### Purpose of Use
* Created an algorithmic trading bot that learns and adapts to new data and evolving markets.
* The analysis contains three parts:
  * Implement an algorithmic trading strategy that uses machine learning to automate trade decisions.
  * Adjust the input parameters to optimize the trading algorithm.
  * Train a new machine learning model and compare its performance to that of a baseline model.

### Files Navigation
* Resources: Directory containing necessary csv file and plots
* `machine_learning_trading_bot.ipynb`: Notebook containing all data processing, modeling, and plots

### Solution/Summary Evaluation
* Default Parameters (Baseline):
  * `months = 3`
  * `short_window = 4`
  * `long_window = 100`

* Tuned Parameters:
  * `months = 6`
  * `short_window = 50`
  * `long_window = 275`

Baseline SVM Plot Using Default Parameters
![Baseline SVM Plot](https://github.com/lrb924/Machine_Learning_Trading_Bot/blob/main/Resources/SVM_Baseline.png)

The baseline model produced returns that were slightly greater than the actual returns.

SVM Plot Using Tuned Months
![SVM Plot 6 Months](https://github.com/lrb924/Machine_Learning_Trading_Bot/blob/main/Resources/SVM_6_Months.png)

The tuned model using a longer months offset of 6 months also produced slightly higher returns than the actual returns.

This model returned the best results overall when compared to the other models that were run.

SVM Plot Using Tuned Months and Windows
![SVM Plot 6 Months and Tuned Windows](https://github.com/lrb924/Machine_Learning_Trading_Bot/blob/main/Resources/SVM_6_Months_Updated_Windows.png)

The tuned model using both the longer months offset of 6 months and the updated long- and short-windows significanly decreased the models returns compared to the actual returns.

Alternative Model (Logistic Regression)
![Baseline Logistic Regression Plot](https://github.com/lrb924/Machine_Learning_Trading_Bot/blob/main/Resources/Logistic_Regression_Baseline.png)

The alternative model performed significantly worse than the original model using the default parameters for both. 











