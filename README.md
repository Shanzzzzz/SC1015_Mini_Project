# SC1015 SC1 - Group 8 - Project 

## About

This is a Mini-Project for CS1015 Introduction to Data Science and Machine Learning.

The dataset used in this project is the 2016, 2018 and 2020 Behavioral Risk Factor Surveillance System (BRFSS) data provided by the Centers for Disease Control and Prevention (CDC), a national public health agency of the United States. 

The chosen dataset contains records of the surveys conducted through landline and cellular telephone. According to CDC, the BRFSS's aims to collect data about chronic diseases and conditions, health risk behaviors, accessibility to health care facilities, and use of health services related to causes of disability and death.

<b> Dataset Source: </b> 

https://www.cdc.gov/brfss/annual_data/annual_data.htm 

https://www.kaggle.com/datasets/sakinak/behavioral-risk-factor-surveillance-survey-201619
  


<h2> Overview of Project </h2> 
  <ol>
    <li> Problem Definition </li> 
    <li> <a href="https://github.com/Shanzzzzz/SC1015_Mini_Project/blob/main/data_preparation_and_cleaning.ipynb"> Data Preparation and Cleaning </a> </li>
    <li> <a href="https://github.com/Shanzzzzz/SC1015_Mini_Project/blob/main/exploratory_data_analysis.ipynb"> Exploratory Data Analysis (EDA) </a> </li> 
    <li> <a href="https://github.com/Shanzzzzz/SC1015_Mini_Project/blob/main/data_splitting_and_resampling.ipynb"> Data Splitting and Resampling </a> </li>
    <li> Machine Learning  </li> 
    <li> Conclusion and Recommendations </li> 
  </ol>


## Problem Definition 

- Can we use machine learning to predict if an individual has Coronary Heart Diease/Myocardial Infarction? (Classification Type)
- Which model would be perform best for the prediction?

## Data Preparation and Cleaning

<ul>
  <li>Remove null values</li>
  <li>Remove redundant values</li>
  <li>Rename variables</li>
  <li>Merge multiple year data</li>
</ul>

## Exploratory Data Analysis (EDA)

<ul>
  <li>Numerical Variable Analysis </li>
  <li>Categorical Variable Analysis </li>
</ul>

## Machine Learning

  <ul>
    <li> <a href="https://github.com/Shanzzzzz/SC1015_Mini_Project/blob/main/ML_logistic_regression.ipynb"> Logistic Regression </a> </li>
    <li> <a href="https://github.com/Shanzzzzz/SC1015_Mini_Project/blob/main/ML_random_forest_classifier.ipynb"> Random Forest Classifier </a> </li>
    <li> <a href="https://github.com/Shanzzzzz/SC1015_Mini_Project/blob/main/ML_deep_learning.ipynb"> Deep Neural Network </a> </li>
  </ul>

## Conclusion and Recommendations

<ul>
  <li>The numerical variables hardly have any correlation with Coronary Heart Disease/Myocardial Infarction</li>
  <li>Based on the stacked bar charts, the ratio of 0's and 1's does seem to vary between category levels for quite a few of the categorical variables, which indicates that different levels might effect the response variable</li>
  <li>The machine learning models are unable to predict very accurately nor precisely even though some of the classification accuracy is moderately high.</li>
  <li>Logistic Regression performed best for the SMOTETOMEK dataset with a 74% accuracy</li>
  <li>Random Forest Classifier did not do well even though with the TomekLinks dataset it achieved 92.4 accuracy because of the insanely high False Negative Rate of 93.4%</li>
  <li>The neural network model did decent as it was able to obtain an accuracy of 0.75 and recall of 0.77 but the precision was low with 0.18</li> 
  <li>What can be done?
    <ul>
      <li>Improve the models by hyperparameter tuning or feature scaling</li>
      <li>Explore other classification models to find better options</li>
      <li>Try other resampling methods to rebalance the dataset</li>
    </ul>
  </li>
</ul>


___

## Learning Outcomes of the Project

<ul>
  <li>Ways to resample imbalanced datasets </li>
  <li>Logistic regression</li>
  <li>Random Forest Classifier</li>
  <li>Deep Neural Network from keras</li>
</ul>


## Group Members

- @Han Zhiguang - Exploratory Data Analysis, Logistic Regression
- @Tan Jin Shan - Data Cleaning, Exploratory Data Analysis, Random Forest
- @NGUYEN GIA KHANH - Deep Neural Network, insights


## References

<ul>
  <li>https://www.cdc.gov/brfss/annual_data/annual_data.htm</li>
  <li>https://towardsdatascience.com/pca-using-python-scikit-learn-e653f8989e60</li>
  <li>https://towardsdatascience.com/</li> <li>logistic-regression-using-python-sklearn-numpy-mnist-handwriting-recognition-matplotlib-a6b31e2b166a</li>
  <li>https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html</li>
  <li>https://seaborn.pydata.org/api.html</li>
</ul>