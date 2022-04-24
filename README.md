# SC1015-Personal-key-indicators-of-heart-disease-dataset
## Introduction
Heart disease is the leading cause of death globally, taking an estimated 17.9 million lives each year, representing 32% of global deaths. With the power of data, we get to investigate and determine what lifestyle habits or conditions that mostly contribute to one’s likelihood to suffer from heart disease.

This repository is part of a mini-project submission for SC1015 - Introduction to Data Scicence and Artificial Intelligence.

## Problem Statement
How can different variables predict whether one has heart disease?

## Libraries used
pandas for dataframes, seaborn, numpy, scipy and matplotlib for plotting graphs, scikit-learn and graphviz for machine learning

## Contents
The contents of this repository include:
* README.md - this file
* heart_2020_cleaned.csv - the dataset used for this particular problem, which includes the variables which were used as predictors for the risk of heart disease.
* DSAI Project - EDA v3.ipynb - the python notebook containing our main source code base, which includes the visualization of the data, the setting of the variables into our classification problem, as well as the generation of our linear regression model.
* SC2 Group 5 Presentation.pptx - presentation slides used for our project.
Because the original dataset was heavily skewed towards non-heart disease sufferers, a large number of random samples had to be dropped to make the dataset more balanced.

## Conclusion
We learnt that for our problem statement, the decision tree model alone is not enough to get a reliable prediction. So we require both linear regression and decision tree to have a model that can predict if someone is more likely to get heart disease. We also have found that although our model is not perfect, we get to know the group of people that are more likely to have or develop heart disease, such as people ages 50 and above. For these groups of people, we can advise them to take healthier life choices to reduce the chances of them getting heart disease, which, to reiterate, is the biggest cause of death currently.

## Contributors
* Fabian Tay (@fabbiotaye) - Exploratory Data Analysis
* Thaddeus Chong - Multi-Variate Analysis of Classification Problem
* Muhammad Akmal bin Johari (@mistaakjo) - Compilation of Presentation

## References
1. Personal Key Indicators of Heart Disease. (2022, February 16). [Dataset]. https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease
