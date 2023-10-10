# Udacity Data Scientist Nanodegree Capstone Project

This repository has all the code and report for my Udacity Data Scientist Nanodegree Capstone project.

## Starbucks Capstone Project: Using Starbucks app user data to predict effective offers

### 1. Installations
This project was written in Python, using Jupyter Notebook on Anaconda. The relevant Python packages for this project are as follows:

- pandas
- numpy
- math
- json
- sklearn.model_selection (train_test_split module)
- sklearn.preprocessing (StandardScaler, PolynomialFeatures)
- from sklearn.tree (DecisionTreeClassifier,DecisionTreeRegressor)
- sklearn.ensemble (RandomForestClassifier)
- sklearn.metrics (mean_squared_error,classification_report)
- sklearn.linear_model (Ridge)
- time
- sklearn.model_selection (GridSearchCV)
- matplotlib

### 2. Project Motivation
This project is the Capstone project of my Data Scientist nanodegree with Udacity. As students in the nanodegree, we have the option to take part in the Starbucks Capstone Challenge.
For the challenge, Udacity provided simulated data that mimics customer behavior on the Starbucks rewards mobile app.

In this project, I use the data to answer 2 business questions:

  - a. What are the main drivers of an effective offer on the Starbucks app?
  - b. Could the data provided, namely offer characteristics and user demographics, predict whether a user would take up an offer?

To answer the above 2 questions, I created 3 models for the data on the 3 offer types provided. The three offers are: Buy One Get One Free (BOGO), Discount (discount with purchase), and Informational (provides information about products).

As a brief summary of my findings:
- For Question 1, Across all three offer types, membership tenure emerged as the most significant predictor of offer effectiveness.

- For Question 2, these values of accuracy for different types of abovementioned offers are acceptable and reasonable. However, the accuracy of the model for the "informational offer" is below 80% which is also fine since this offer is just for the customers' information. This shows that our model is working well.

### 3. File Descriptions
This project contains 4 files. The report of my project is called 'Starbucks_Capstone_Project.ipynb'. 
The datasets are listed is in the files called portfolio.json, profile.json and transcript.json. 

### 4. Results <a name="results"></a>
The main findings of the code can be found at the post on Medium available [here](https://medium.com/@farhadabbasiamiri/using-starbucks-app-user-data-to-predict-effective-offers-e9d17e3abc1d)

### 5. Licensing, Authors, Acknowledgements, etc.

Data for coding project was provided by Udacity.
