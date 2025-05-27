# Crime-Cast Forecasting

Crime-Cast Forecasting is a machine learning project that aims to predict crime categories using a dataset obtained from Kaggle. The project involves performing Exploratory Data Analysis (EDA), preprocessing the data, and training several machine learning models to forecast crimes.

## Table of Contents

* Project Overview
* Dataset
* EDA and Preprocessing
* Modeling
* Results
* Dependencies

---

## Project Overview

The goal of this project is to forecast the categories of crimes occurring in various locations based on historical data. The models used include:

* Random Forest
* XGBoost Classifier
* Bagging Classifier with Decision Tree
* Gradient Boosting Classifier

We compare these models based on accuracy, precision, recall, and other relevant metrics.

---

## Dataset

The dataset used in this project is sourced from Kaggle. It contains the following features:

* **Location**: The place where the crime occurred.
* **Cross\_Street**: The cross street near the crime location.
* **Latitude and Longitude**: Geographical coordinates of the crime location.
* **Date\_Reported and Date\_Occurred**: The reported and actual dates of the crime.
* **Time\_Occurred**: The time when the crime occurred.
* **Area\_ID**: An identifier for the area where the crime occurred.
* **Area\_Name**: The name of the area where the crime occurred.
* **Reporting\_District\_no**: The number of the reporting district.
* **Part 1-2**: Classification of the crime as Part 1 or Part 2.
* **Modus\_Operandi**: The method or technique used to commit the crime.
* **Victim\_Age, Victim\_Sex, Victim\_Descent**: Information about the victim.
* **Premise\_Code and Premise\_Description**: The location or building type where the crime occurred.
* **Weapon\_Used\_Code and Weapon\_Description**: Information about any weapons used in the crime.
* **Status and Status\_Description**: The status of the crime case (open, closed, etc.).
* **Crime\_Category**: The type of crime committed.

**Link to dataset**: Kaggle Dataset

---

## EDA and Preprocessing

Exploratory Data Analysis (EDA) was performed to understand the distribution and relationships between various features. Key steps in EDA included:

* Visualizing crime trends over time.
* Analyzing correlations between features like victim demographics, crime types, and locations.
* Identifying missing data and handling them.

In preprocessing, we performed:

* Data cleaning (handling missing values, outliers).
* Encoding categorical variables.
* Scaling numerical features.
* Splitting the data into training and test sets.

---

## Modeling

Several machine learning models were implemented to forecast crime occurrences:

* **Random Forest** - A robust ensemble method.
* **XGBoost Classifier** - Known for its high performance in structured/tabular data.
* **Bagging Classifier with Decision Tree** - Combines multiple decision trees for better predictions.
* **Gradient Boosting Classifier** - An ensemble method that builds models sequentially.

Each model was evaluated based on various performance metrics such as accuracy, F1-score, and ROC-AUC.

---

## Results

The models were compared on several metrics, with the following highlights:

* **Random Forest**: Achieved accuracy of 90%.
* **XGBoost Classifier**: Excelled in accuracy.
* **Bagging Classifier**: Performed well on recall.
* **Gradient Boosting Classifier**: Offered the best trade-off between precision and recall.

---

## Dependencies

To run this project, you will need the following dependencies:

* Python
* pandas
* numpy
* scikit-learn
* xgboost
* matplotlib
* seaborn
