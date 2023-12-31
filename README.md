# Project-ml-regression-crop_production
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRxOLQtDnSSpRrnewi7wygkaF1TYSNuxreRRQ&usqp=CAU" width = "1000">

## Overview
* **Motivation:**
Crop yield prediction is an essential task for the decision-makers at national and regional levels 
for rapid decision-making. An accurate crop yield prediction model can help farmers to decide on what to grow and when to grow.
Crop yield prediction is one of the challenging problems in precision agriculture.

* **Problem Statement:**
Predict the crop production in India

## Working Methodology
* Primary Task is to Understand Data and finding anomalies in data.
* Visualizing data to understand it better
* Exploratory data analysis.
* Feature Engineering.
* Machine Learning Preprocessing.
* Building Machine Learning model.
* Model Evaluation.
* Cross validation.
* Tuning Model.

## Data Collection
The dataset I took from kaggle.link for the dataset is [here](https://data.world/thatzprem/agriculture-india)

## Technical Aspect :
* Python -- Programming Langauge for this Notebook.
* Pandas -- Python Data Analysis Library.
* Sklearn -- Machine Learning handling in Python.
* Scipy -- Scintific Calculation in python
* Matplotlib -- creating static, animated, and interactive visualizations in Python.
* Seaborn -- Python data Visulization based on matplotlib.

## Model Evaluation criteria
* MSE
* RMSE
* R2_score

## Results 
|Algorithm|r2_score|
|:--:|:--:|
LinearRegression|0.226581
DecisionTreeRegressor|0.923590
RandomForestRegressor	|0.941825
AdaBoostRegressor RandomForest as base model|0.593816
AdaBoostRegressor DecisionTree as base model|0.576665
GradientBoostingRegressor	|0.938196
XGboost Regressor|0.941793

## Conclusion 
1. Decision Tree Regressor has given the best r2_score but the predictions seems to be grouped
2. Hence Random Forest is the best model for this problem 
3. Random Forest has given an r2_score of 94.18 i.e approx 94% 
4. All the boosting models have given almost equal score 
5. Random Forest can be improved further by correct hyper parameter tuning 
6. Reducing the levels in crop and state has reduced the model performance 
