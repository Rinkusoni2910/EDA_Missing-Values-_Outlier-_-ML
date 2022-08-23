# EDA_Missing-Values-_Outlier-_-ML
# About Dataset
An individual’s annual income results from various factors. Intuitively, it is influenced by the individual’s education level, age, gender, occupation, and etc.

Fields The dataset contains 15 columns Target filed: Income -- The income is divide into two classes: <=50K and >50K Number of attributes: 15 -- These are the demographics and other features to describe a person

We can explore the possibility in predicting income level based on the individual’s personal information.

# Objective
Objective of this product is to perform EDA, find the missing values if any, find the outliers, and lastly build various Machine Learning models considering ‘income’ as target variable and compare the performance of each of the ML Model.

# steps to be followed:
Step - 1 : Introduction -> Give a detailed data description and objective

Step - 2 : Import the data and perform basic pandas operations

Step - 3 : Univariate Analysis -> PDF, Histograms, Boxplots, Countplots, etc.. Understand the probability and frequency distribution of each numerical column Understand the frequency distribution of each categorical Variable/Column Mention observations after each plot

Step - 4 : Bivariate Analysis Discover the relationships between numerical columns using Scatter plots, hexbin plots, pair plots, etc.. Identify the patterns between categorical and numerical columns using swarmplot, boxplot, barplot, etc.. Mention observations after each plot.

Step - 5 : In the above steps you might have encountered many missing values and outliers Find and treat the outliers and missing values in each column

Step - 6 : Apply appropriate hypothesis tests to verify the below mentioned questions

Is there a relationship between occupation and gender? (i.e. does the preference of occupation depend on the gender)

Is there a relationship between gender and income?

Step - 7 : Split the data into train and test. After which you need to perform feature transformation: For Numerical Features -> Do Column Standardization For Categorical -> if more than 2 categories, use dummy variables. Otherwise convert the feature to Binary. You are free to explore other feature transformations.

Step - 8 : Build various Machine Learning models considering ‘income’ as target variable. Also make sure to perform Hyperparameter tuning to avoid Overfitting of models.

Step - 9 : Create a table to compare the performance of each of the ML Model
