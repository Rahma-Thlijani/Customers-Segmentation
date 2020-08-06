![Image](customer1.png)
# Customers-Segmentation


Data science project, in which we will focus on applying: **Data processing, Exploratory Data Analysis (EDA), Data Visualization, Feature Selection, and Multiple Regression model** aiming to predict a car price.
## Data Description
We have the Automobile dataset "auto.csv". It was obtained through the following link: https://archive.ics.uci.edu/ml/machine-learning-databases/autos/imports-85.data.

The datasets has 205 rows and 27 columns containing the cars' characteristics such as 'symboling', 'normalized-losses', 'maker', 'fuel-type', 'aspiration',
'num-of-doors', 'body-style', etc.
## Project Overview
In this data science project, we will first understand, manipulate, process, visualize and analyze the data. In addition, we will train a multiple regression model aiming to predict the price of the car regarding its different properties. Finally, we will evaluate the model based on the MAE
the RMSE and the R2_Score.
## Project Steps
All the project steps are organized and listed below:

### 1. Data Import
### 2. Data Understanding and Manipulation
* Show data header
* Show columns names
* Drop the first irrelevant column
* Fix columns names
* Data information
* Check to number of rows and columns
### 3. Data Processing
* Dealing with missing data
* Drop the duplicate rows
* Correct data format
* Dealing with outliers
* Data standardization
* Data normalization
* Binning
* Converting categorical values
### 4. Exploratory Data Analysis
* Descriptive Statical Analysis 
* Analyzing Individual Features 
* Combinaison and Groupping 
* Output Analysis \
![Image](c1.png)  ![Image](c2.png)
### 5. Feature Selection
### 6. Model Development
* Select the dataframe
* Split data set into training and testing parts (80/20)
* Scale both training and testing input data
* Train the regression model
### 7. Model Evaluation
We tested the multiple regression model on the testset to provide predictions, and then we evaluated its performance using the three metrics:
* Mean Absolute Error (MAE): 2921.78
* Root mean squared error (RMSE): 4150.64
* R-squared Score (R2_Score): 0.7503
