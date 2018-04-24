# Predicting-High-School-Graduation-Rates

The purpose of this project was to use Census data to determine features which best predict high school graduation rates. Data was available from the 2010 Census and the 2008-2012 American Community Survey and contained variables related to income, race, gender, and housing community demographics. 

Notebook 1: Data Cleaning and EDA. In this notebook, I perform some data cleaning, dealing with null values, and do some data exploration and group analysis. Specifically, I start looking at relationships between graduation rates and other variables (e.g., location, race, housing, employment rates). 

Notebook 2: Regression and Classfication. In this notebook, I begin with variables that correlated .10 or higher with the target variable, graduation rates, and run linear regression and decision tree and random forest analyses. I also create a dichotomous variable to reflect high graduation rate (above 80%) and low graduation rate (below 80%) to perform classification analysis. While the overall R-squared and classification accuracy scores are not high, the same features come out again and again as important: Income, Vacant Units in the community, mobile home units, unemployment rates, population below the poverty and line.

Notebook 3: Cluster Analysis. In this notebook, I use KMeans to take the top 15 important features and identify higher-order variables. While not perfectly clean, three clusters emerge: 1) Afluency related to income, 2) Housing Standards, related to living in areas with vacant units or mobile homes, and 3) Head of Household Characteristics, related to whether the HH is married and a relative. 

While there are obviously other variables related to graduation success, recommendations based on this data would involve improving community housing standards and programs to increase employment and income levels in the community. 
