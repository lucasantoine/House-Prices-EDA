# Exploratory Data Analysis of Kaggle's House Prices Dataset

This Jupyter Notebook contains the code for performing Exploratory Data Analysis (EDA) on the Kaggle's House Prices competition's dataset. The objective of this project is to gain insights into the data and prepare it for machine learning models.

## Dataset Description

The Kaggle's House Prices competition's dataset contains 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa. The target variable is the sale price of each house. The dataset can be downloaded from Kaggle's website at this link : [https://www.kaggle.com/competitions/home-data-for-ml-course/data](https://www.kaggle.com/competitions/home-data-for-ml-course/data).

## Tools and Libraries

The EDA has been performed in a Jupyter Notebook using Python programming language. The following libraries have been used:

- **Pandas** : For data manipulation and analysis
- **NumPy** : For numerical computing
- **Matplotlib** and **Seaborn** : For data visualization
- **Scipy** : For statistical analysis
- **Scikit-learn** : For machine learning algorithms and preprocessing

## EDA Overview

The EDA has been divided into the following sections:

1. **Project setup:** This section describes the tools and libraries used for the EDA.
2. **Loading data:** This section loads the data into a pandas DataFrame and gives a brief description of the data.
3. **Missing values:** This section explores the missing values in the dataset and implements methods to handle them.
4. **Descriptive statistics:** This section provides descriptive statistics of the dataset such as mean, median, and standard deviation.
5. **Target value visualization:** This section explores the target variable using histograms and probability density plots.
6. **Numerical values columns:** This section explores the numerical columns in the dataset.
7. **Numerical values distribution:** This section provides a distribution plot of the numerical values.
8. **Numerical values boxplots:** This section provides boxplots of the numerical values to identify outliers.
9. **Numerical values regplots:** This section provides regression plots of the numerical values to identify linear relationships with the target variable.
10. **Numerical values correlation matrix:** This section provides a correlation matrix of the numerical values to identify highly correlated variables.
11. **Categorical values columns:** This section explores the categorical columns in the dataset.
12. **Handling missing categorical values:** This section explores the missing values in the categorical columns and implements methods to handle them.
13. **Categorical values distribution:** This section provides a distribution plot of the categorical values.
14. **Categorical values boxplots:** This section provides boxplots of the categorical values to identify outliers.
15. **Categorical values impact on the target value:** This section explores the impact of categorical variables on the target variable.
16. **Target encoding categorical values:** This section encodes categorical variables using target encoding.
17. **Pairplots of numerical and target encoded categorical variables:** This section provides pairplots of numerical variables and target encoded categorical variables.
18. **Clustering and dimensionality reduction:** This section explores clustering and dimensionality reduction of the dataset.
19. **Feature importance using a Random Forest Regressor:** This section identifies the most important features using a Random Forest Regressor.
20. **Note of the Author:** This section provides a brief note from the author.

The code in this notebook can be used as a starting point for building machine learning models for the Kaggle's House Prices competition.

## How to use the Jupyter Notebook

1. Clone the GitHub repository to your local machine.
2. Install the necessary libraries by running pip install -r requirements.txt command in the terminal.
3. Run the Jupyter Notebook by running the jupyter notebook command in the terminal.
4. Open the house-prices-eda.ipynb file in the Jupyter Notebook and run the code cells sequentially.

## Conclusion

The EDA has provided valuable insights into the data, such as the distribution of the target variable, the relationship between the features and the target variable, the presence of outliers, and missing values. The data has been prepared for machine learning models through feature engineering and correlation analysis. The code in this notebook can be used as a starting point for building machine learning models for the Kaggle's House Prices competition.

Link to the notebook on Kaggle : [https://www.kaggle.com/code/dreygaen/house-prices-exploratory-data-analysis](https://www.kaggle.com/code/dreygaen/house-prices-exploratory-data-analysis)
