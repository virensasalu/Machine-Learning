Readme. 

The objective of the final project will be to build a fully reproducible project that uses ML to address a question of my choice. On the German bank dataset which is facing issues with defaulters. The Project contain technique and methods with reason on how to predict defaulters.


Structure of my Final report named: Final Project- The German Bank
Submitted as PDF
Submitted on 29th November, 2023

1. Introduction

* Data Description
* Some of the Questions I have answered throughout the program

2. Methods and Materials

* Exploratory Data Analysis (EDA)
* Data Understanding, Cleaning and Pre-Paring/Pre-Processing
* Data Visualization: �Datavis�
* My Observations
* Data Pre-Processing
* Models Training: �ProcessedBankData�
* Model fitting and Evaluations
* Model Comparison and Final Selection

3. Result

* Logistic Regression
* K-Nearest Neighbours
* Quadratic Discriminant Analysis
* Random Forest
* Gradient Boosting
* AdaBoost
* Linear Discriminant Analysis

4. Discussion

* General Thoughts
* Least performing models and its observation
* Best Performing model and its observation
* Limitations 
* Citations

5. Conclusion





Structure of my Code file Named: Final Project- The German Bank
Submitted as IPYNB (notebook) and an HTML page
Submitted on 29th November, 2023
My apologies, my code file is a little different from the structure of my final report. But rest assured all the results are from the code file 



1. General Introduction to the problem statement

* Objectives
* Context
* Data Description
* Some Questions I have answered throughout the program
* Importing all the libraries that might be need pre-emotively
* Reading the data set to being with understanding it and then processing it

2. Pre-Processing

* Checking the data in depth to make sure there no anomalies (some insights shared)
* Cleaning up the dataset, getting rid of all the anomalies
* Making different copies of the dataset. One for data visualization (Datavis) and one for models (ProcessedBankData)
* Mapping the dataset to fit the models (Insights)

3. Exploratory Data Analysis for Bank data

* Making more sense of the data by drafting graphs and learning the relationship between each attributes
* PairPlot (numerical features only)
* plotly.express
* Heat map � of selected features only (Numerical and some categorical)
* Correlation matrix
* Box plot, density and histogram with hue= default 
* Count plot of all the features without default

4. Exploring Machine Learning Models

* Splitting the data to 80 - 20 with stratification
* Initialize StandardScaler and fit-transform on the training and test data
* Model 1 random forest
* Understanding the feature importance
* Checking how well the model fits
* Models 2,3,4,5,6,7
* Last leg 
* Plotting all confusion matrix
 
5. Comparing The Model Performance

* Adapted Precision Recall curve, Area Under Curve, Receiver Operating Characteristic curve
* Created a dummy dataset to fit to my model.(Deployment proof)


