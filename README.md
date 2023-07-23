# Mental-Analysis-and-Tracking
Overview
This project aims to develop predictive models to anticipate mental health prevalence and its impact on disease burden using regression trees, decision regression trees, and linear regression. The main code is implemented in the "Mental_Project.ipynb" Jupyter Notebook. The project utilizes two data files, namely "prevalence-by-mental-and-substance-use-disorder_AI.csv" and "mental-and-substance-use-as-share-of-disease-AI.csv."

|- data/
   |- prevalence-by-mental-and-substance-use-disorder_AI.csv
   |- mental-and-substance-use-as-share-of-disease-AI.csv
|- Mental_Project.ipynb
|- README.md

Data
The project uses two data files, which are stored in the "data" directory:

prevalence-by-mental-and-substance-use-disorder_AI.csv: This dataset contains information on the prevalence of mental and substance use disorders across different countries and years.

mental-and-substance-use-as-share-of-disease-AI.csv: This dataset provides data on the share of mental and substance use disorders as a proportion of the overall disease burden.

Jupyter Notebook
The "Mental_Project.ipynb" Jupyter Notebook contains the main code for the project. It includes the following sections:

Data Loading and Exploration: In this section, the data files are loaded, and exploratory data analysis (EDA) is performed to gain insights into the datasets.

Data Preprocessing: The data is cleaned and preprocessed to handle missing values, outliers, and any necessary transformations.

Regression Trees: A regression tree model is implemented to predict mental health prevalence based on various features.

Decision Regression Trees: Another regression tree model with decision splits is employed to anticipate the impact of mental health on disease burden.

Linear Regression: A linear regression model is used to explore the linear relationship between mental health prevalence and other variables.

Model Evaluation: The performance of the models is evaluated using metrics such as mean squared error (MSE) and R-squared.
