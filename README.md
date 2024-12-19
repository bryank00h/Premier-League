# Prediction of Football Team Winner

## Overview
This project uses Python and Machine Learning to predict the winner of a football match based on team performance data. By applying multiple machine learning models, we determined the most effective algorithm for predicting match outcomes. The **Decision Tree model** emerged as the most accurate with an **80% prediction success rate**, closely correlated with critical match parameters such as:
- **Goals**
- **Successful Passes**
- **Saves**
- **Shots**


## Key Features
- Applied **6 Machine Learning Models**:
  - Linear Regression
  - Random Forest
  - Decision Tree
  - K-means Clustering
  - K-Nearest Neighbour
  - Naïve Bayes Classifier
- Identified Decision Tree as the ideal model with 80% accuracy.


## Repository Structure
- **`Team1.ipynb`**: The Jupyter Notebook containing Python code for data preprocessing, feature engineering, and machine learning implementation.
- **`stats.csv`**: Dataset containing detailed team statistics used for training and evaluation.
- **`results.csv`**: Match outcome dataset used for training and testing the models.


## Requirements
To run the code, you need the following dependencies:
- Python 3.7 or later
- Libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn
  - jupyter


## Results
- **Decision Tree** achieved the highest accuracy (**80%**) and was deemed the most suitable model for predicting match winners.
- Feature analysis showed significant correlations between match outcomes and parameters such as:
  - **Goals**
  - **Successful Passes**
  - **Saves**
  - **Shots**


## Future Work
- Expand the dataset to include more seasons and leagues for better generalization.
- Experiment with deep learning models for improved prediction accuracy.
- Incorporate additional features such as:
  - **Player statistics**
  - **Weather conditions**

