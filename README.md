Student Performance Analysis with Linear Regression
This repository contains a Python project for analyzing and predicting student performance in various subjects (Physics, Math, and Chemistry) using Linear Regression. It explores data visualization, data preprocessing, and machine learning modeling.

Overview

Data Exploration: We start by loading a dataset containing student information and their performance metrics. We examine the data's shape, missing values, and duplicate entries.

Data Visualization: We visualize the distribution of scores in Math, Physics, and Chemistry using histograms. Additionally, we create a correlation matrix heatmap to explore relationships between variables.

Data Preprocessing: Categorical variables like 'Gender' and 'Has_Part_Time_Job' are encoded for model compatibility. We prepare the data for machine learning.

Linear Regression Modeling: We use scikit-learn to build separate linear regression models for Physics, Math, and Chemistry scores. The models are trained and evaluated using mean squared error (MSE).
