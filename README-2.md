# SC1015 Mini Project

## For our mini project in the Introduction to Data Science and Artificial Intelligence module (SC1015), we performed analysis on the Diamonds dataset from Kaggle.

## Problem Definition
## How can we predict the price of diamond based on its characteristics?

### Members(A135_Team 5)
#### 1. Mohamed Muhsin Mohammad Zubair Rahman (U2221521C)
#### 2. Darrell Ma Wei Ze (U2222176G)
#### 3. Lim Weijun (U2222129A)

## Files included
### 1. Diamond.csv - dataset
### 2. SC1015 slides.pdf - presentation slides
### 3. Mini Project.ipynb

- Cleaning and preparation
- Basic visualization
- Exploratory data analysis
- Machine learning: Linear Regression, Decision Tree Regression, Random Forest Regression

### Notebook Details

#### Cleaning and Preparation

a. Check for missing values within the dataset

b. Removed insignificant column: 'Unnamed'

c. Capitalise all our variable names

#### Basic Visualization

a. Used box plots, histograms, and violin plots in visualising numeric variables

b. Used box plots and countplots to visualise categorical variables

#### Exploratory Data Analysis

a. Plot a correlation matrix to identify multicollinearity and any existing patterns within numeric variables

#### Key takeaways from EDA

- We concluded that CARAT has the highest correlation of 0.92 with price

- DEPTH and TABLE has a low correlation of -0.01 and 0.13 respectively with price

- There is high variation in Price boxplots across levels for COLOR and CLARITY

- There is not much variation in Price boxplots across levels for CUT



#### Machine Learning

1. Used Linear Regression model on all numerical variables, with and without outliers.

2. After deciding the best predictor, we compared Decision Tree Regression, Random Forest Regression and Linear Regression models to see which is the best model to predict the price of a diamond using the best predictor.

#### Conclusion

1. As for numerical variables, CARAT is the most suitable predictor for price of a diamond and the most suitable model to use is Decision Tree Regression model.

2. As for categorical variables, COLOR and CLARITY are better predictors for price of a diamond.

### References

1. https://scikit-learn.org/stable/auto_examples/tree/plot_tree_regression.html
2. https://www.kaggle.com/datasets/shivam2503/diamonds
3. https://www.geeksforgeeks.org/random-forest-regression-in-python/
