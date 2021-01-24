# Titanic Data Analysis Using Python

![Python](https://img.shields.io/badge/Python-3.8.2-blueviolet)
![Numpy](https://img.shields.io/badge/Numpy-1.16.4-red)
![Pandas](https://img.shields.io/badge/Pandas-0.24.2-green)
![Seaborn](https://img.shields.io/badge/Seaborn-0.9.0-fcba03)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.1.0-blue)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-darkorange)

## Introduction
* This is the legendary Titanic ML competition – the best, first challenge for you to dive into ML competitions and familiarize yourself with how the Kaggle platform works.
* This dataset is from Kaggle site [[Download Dataset](https://www.kaggle.com/c/titanic/download)].
* This dataset provides an opportunity to ask question which features are useful to predict the survival of people. 
* Did **Exploratory Data Analysis (EDA)** and **Feature Selection** To get better results.
* Did **Data Analysis**.


## Resources Used
* **Jupyter**
* **Python-3.8.2**
* **Numpy-1.16.4**
* **Pandas-0.24.2**
* **Matplotlib-3.1.0**
* **Seaborn-0.9.0**

## Data
* survival - Survival (0 = No, 1 = Yes)
* pclass   - Ticket class(1 = 1st, 2 = 2nd, 3 = 3rd)
* sex	     - Sex	
* Age	     - Age in years	
* sibsp	   - no. of siblings / spouses aboard the Titanic	
* parch	   - no. of parents / children aboard the Titanic	
* ticket	 - Ticket number	
* fare	   - Passenger fare	
* cabin	   - Cabin number	
* embarked - Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Objective
To find out the important features to predict the survival of people onboard.

## Overview of data
* Data columns (total 11 columns):
* Column name    values     dtype
* Survived    891 non-null  int64
* Pclass      891 non-null  int64
* Name        891 non-null  object
* Sex         891 non-null  object
* Age         714 non-null  float64
* SibSp       891 non-null  int64
* Parch       891 non-null  int64
* Ticket      891 non-null  object
* Fare        891 non-null  float64
* Cabin       204 non-null  object

**object** means **string** type.
* Embarked    889 non-null object
