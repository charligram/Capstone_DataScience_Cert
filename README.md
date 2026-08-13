# 🚀 SpaceX Fist Stage Landing Prediction

## Introduction

Within the aerospace industry, SpaceX is able to save a significant amount of resources because some of its launches reuse the first stage of the rocket.

The objective of this project is to identify the characteristics that increase the likelihood of a SpaceX rocket launch successfully recovering its first stage and to create a machine learning model capable of generating such predictions.


## Process

The information will be obtained through the available SpaceX API and launch information from Wikipedia.

The information will then be processed to ensure it is in the appropriate format for analysis. This analysis also includes the development of interactive graphics using Dash and the creation of geospatial maps.

After the analysis, the information will be processed so that it can be fed into various machine learning models.


## ℹ️ Dataset
The launch features used for analysis are as follows:

- Payload Mass

- Flight number

- Launch site

- Orbit type

- Outcome

For working with geospatial data, the latitude and longitude of each launch site were also used.


## 📊 Exploratory Data Analysis (EDA)

In this section, the data were compared to the objective, and the interaction between features was examined. Some examples of these graphs are:

- Payload mass by flight number

- Orbit type by flight number

- Launch site by payload mass


## 👨‍💻 Data preparation
The data were prepared as follows:

- Missing values ​​were handled

- Important features were selected

- Categorical variables were converted to numeric using one-time format

- The information was standardized

- The information was separated into training and test sets


## 🤖 Machine Learning Models

The models used were the following:

- LogisticRegression

- Suport Vector Machine (SVM)

- DecisionTreeClassifier

- K-Nearest Neighbors (KNN)


## 🛠️ Technologies

- Python

- Pandas

- NumPy

- Matplotlib

- Seaborn

- SQL

- Folium

- Plotly/Dash

- Scikit-learn

- Jupyter Notebook


## 👤 Author

Carlos Rojas Villegas

IBM Data Science Professional Certificate - Coursera