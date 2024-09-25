# titanic-survival-prediction

In this project, we explore the Titanic dataset to predict whether a passenger survived or not. Various machine learning algorithms such as Logistic Regression, Decision Tree Classifier, Random Forest Classifier, and Gradient Boosting Classifier are implemented to evaluate their performance on the dataset.

Dataset:

The dataset used is the Titanic dataset, which contains the following key features:

Survived: Outcome of survival (0 = No; 1 = Yes)

Pclass: Socio-economic class (1 = Upper class; 2 = Middle class; 3 = Lower class)

Name: Name of the passenger

Sex: Sex of the passenger

Age: Age of the passenger (Some entries contain NaN)

SibSp: Number of siblings and spouses aboard

Parch: Number of parents and children aboard

Ticket: Ticket number

Fare: Fare paid by the passenger

Cabin: Cabin number (Some entries contain NaN)

Embarked: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

Exploratory Data Analysis (EDA):
We use the following techniques to explore and visualize the dataset:

Histogram for Parch (number of parents/children aboard)

Distribution plots for Age and Parch

Line plots, scatter plots, and bar plots for relationships between features

Heatmaps for correlation analysis and missing data visualization

Data Preprocessing:

Handling missing data for the Age and Cabin columns

Dropping unnecessary columns (Name, Ticket, PassengerId)

Converting categorical data (Sex, Embarked) to numerical using one-hot encoding

Feature scaling using StandardScaler

Models:

The following machine learning models are used for survival prediction:

Logistic Regression:

A simple linear model for binary classification.

Decision Tree Classifier:

A tree-based model that splits data into branches to make decisions.

Random Forest Classifier:

An ensemble learning method using multiple decision trees for more accurate predictions.

Gradient Boosting Classifier:

An ensemble method that builds models sequentially to minimize prediction errors.

Results:

Logistic Regression:

Accuracy 0.82 %

Decision Tree Classifier:

Accuracy  78.65 %

Random Forest Classifier:

Accuracy  82.58 %

Gradient Boosting Classifier:

Accuracy  84.27 %

Installation:

To run this project, ensure you have the following dependencies installed:
pip install -r requirements.txt
