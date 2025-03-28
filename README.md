# Project Title

A Kaggle-based Data Analysis and Machine Learning Notebook

## Description

This project explores data analysis and machine learning using Python. It includes data preprocessing, feature engineering, model training, and evaluation. The notebook is designed for experimentation with datasets hosted on Kaggle.

## Dataset

### About the Dataset

The dataset contains various features related to airline passenger satisfaction.&#x20;

Exploratory Data Analysis (EDA)

- Performed statistical analysis to understand the dataset's structure and numerical characteristics.
- Visualized categorical and numerical features for better insights.
- Created a heatmap to analyze correlations between various attributes.
- Identified and handled missing values: The dataset had **310 missing values** in the **Arrival Delay** column. Based on visualization, we found a linear relationship between **Arrival Delay** and **Departure Delay**, so missing values were replaced with **Departure Delay** values.

## Model Building

We applied multiple machine learning algorithms to build a classification model:

- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM)**
- **Decision Tree**
- **Random Forest**
- **AdaBoost Classifier**
- **Gradient Boosting**
- **XGBoost**

Among these models, **XGBoost achieved the highest accuracy of 96%**, outperforming other algorithms.

## Requirements

- Python 3
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib & Seaborn (for visualization)

## Usage

1. Clone the repository.
2. Open the notebook in Jupyter.
3. Run the cells to load and process data.
4. Train and evaluate models based on the dataset.

## Author

Developed as part of a data science learning project.


