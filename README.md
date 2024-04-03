# Project-4-UoB Water Potability analysis and prediction using a supervised machine learning algorithm 

# Project Objective:  

To assess and predict water potability based on various water quality parameters, facilitating informed decisions about water treatment and ensuring compliance with water quality standards.

# Overview

## Purpose
The purpose of this project is to analyze water quality measurements to determine if the water is safe for human consumption (potable). Using machine learning techniques, we aim to predict the potability of water based on its chemical attributes.

## Dataset  

The dataset contains water quality measurements such as pH, hardness, solids, chloramines, sulfates, and other significant factors influencing water potability. We obtained our dataset from [Water Quality and Potability Dataset on Kaggle](https://www.kaggle.com/datasets/uom190346a/water-quality-and-potability/data).

## Methodology  

- Data Analysis: Conducted thorough exploratory data analysis (EDA) to understand the distribution and relationships of the variables.  
- Data Cleaning: Initial data cleaning involved handling missing values, normalizing data, and ensuring data integrity.
- Database Creation: Utilized SQLite for database creation, storing cleaned and predicted water quality data for analysis.
- Model Optimization: Used techniques like RandomOverSampler for handling imbalanced datasets and GridSearchCV to identify the best machine learning model and for hyperparameter tuning to improve model performance.
- Machine Learning Modeling: Applied various classification models to predict the potability of water, evaluating models based on accuracy, precision, and recall.

### Resources

- Python Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- Database: SQLite
- Tools: Jupyter Notebook, GitHub for version control and collaboration

## Collaborators

* [Safa Ali](https://github.com/Safa297)  
* [Elcin Kobya Imanci](https://github.com/ELCINKOBYAIMANCI)  
* [Eoghan Alton](https://github.com/ERAA1997)
* [Ahmed Saleem](https://github.com/Asaleem1212)  
