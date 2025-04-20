# Facebook Comment Volume

## Dataset
This project uses the Facebook Comment Volume Dataset from the UCI Machine Learning Repository. The dataset contains features from Facebook posts including page metrics (popularity, check-ins, category), derived statistical features, comment history patterns, and temporal information (posting day, time between posting and measurement).

## Problem Statement
The goal is to predict how many comments a Facebook post will receive in the next H hours, given its current attributes and comment history. This regression task requires handling a highly skewed distribution of comment volumes and extracting meaningful patterns from complex social media engagement data.

The main files of our repository are:
1. DataPreprocessing.ipynb
2. FeatureEngineering.ipynb
3. DecisionTree.ipynb
4. LinearRegression.ipynb
5. NeuralNetwork.ipynb
6. KNN.ipynb

### DataPreprocessing and FeatureEngineering
The first two notebooks explain the data preprocessing and feature engineering done for our project. These notebooks contain functions that were taken into consideration when training the models. They include baseline models and various processes applied to improve these baseline models. The purpose of these notebooks was not to train a model, but to try different processes seen in class and determine which ones yielded better results. When actually training and tuning the models, only the best methods in preprocessing and feature engineering were taken into consideration.

### DecisionTree, LinearRegression, NeuralNetwork, KNN, and FeatureEngineering
The next four notebooks (Decision Tree, Linear Regression, Neural Network, and KNN) contain the principal models that we developed, with the Decision Tree being the best. The main organization of these notebooks was to first have a baseline model and test it directly with all the features. After that, many techniques were applied throughout the notebooks to improve the model. These include the data preprocessing done previously, the feature engineering, and also other specific techniques that are relevant to those types of models.

## Independent work
We also include a PDF with the statement of the group’s independent work by the name 'Statement of Independent Work.pdf'.

## References
Singh, K. (2015). Facebook Comment Volume [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5Q886.
A. Elsakran, A. Al Amin and A. Alzaatreh, "Machine Learning Approach to Predict Facebook Comment Volume," 2019 International Conference on Digitization (ICD), Sharjah, United Arab Emirates, 2019, pp. 64-67, doi: 10.1109/ICD47981.2019.9105863.
Singh, K. (2015). Facebook Comment Volume [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5Q886
Sekar, E. (2023, July 26). Feature Engineering for Machine Learning: A Step-by-Step Guide (Part 1). kgxperience. Retrieved from https://medium.com/kgxperience/feature-engineering-for-machine-learning-a-step-by-step-guide-part-1-33b520c67137
Malamahadevan. (2025, January 7). Step-by-step exploratory data analysis (EDA) using Python. Analytics Vidhya. https://www.analyticsvidhya.com/blog/2022/07/step-by-step-exploratory-data-analysis-eda-using-python/ 

##### CS3244_Final_Project
