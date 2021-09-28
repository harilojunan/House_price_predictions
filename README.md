# House_price_predictions
# Intro
Creating a Machine Learning model to predict the house prices in Boston. We are going to use the dataset from Kaggle.com.

Below data science concepts are used in this project

Data loading and cleaning
Outlier detection and removal
Feature engineering
Dimensionality reduction
Gridsearchcv for hyperparameter tunning
K fold cross validation
Technology and tools used in this project

Python
Numpy and Pandas for data cleaning
Matplotlib for data visualization
Sklearn for model building
Jupyter Notebook

#Steps
We will first build a model using sklearn and linear regression using boston house prices dataset from kaggle.com.
Step#One: Import the required libraries
Step#Two: Load the data
Step#Three: Understand the data
        -drop unnecessary columns
Step#Four: Data Cleaning
        - Check for na values
        - Verify unique values of each column
        - Make sure values are correct (eg. 23 BHK home with 2000 Sqrft size is worng)
        - Feature Engineering
        - Dimesionality Reduction
        - Outlier removal using domain knowledge (2bhk price < 3bhk price, size per bhk >= 300 sqft)
        - Outlier removal using standard eviation and mean
        - One Hot encoding
Step#Five: Build Machine Learning Model
Step#six: Testing The model
