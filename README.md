![Image](customer1.png)
# Clustering-Customers-Segmentation
We will work on a customer dataset, our goal is to apply customer segmentation on this historical data. Customer segmentation is the practice of partitioning a customer base into groups of individuals that have similar characteristics. It is a significant strategy as a business can target these specific groups of customers and effectively allocate marketing resources. For example, one group might contain customers who are high-profit and low-risk, that is, more likely to purchase products, or subscribe for a service. 

To identify customer segments hidden in the data, we will apply an unsupervised learning technique. We will first understand, manipulate, and process the dataset. Thereafter, we will focus on Visualizing the data using different plots such as Heatmap, Pairplot, Boxplot, Distributionplot, Countplot and histogram aiming to reveal and analyze the data insights. Then, we will implement a clustering algorithm (K-mean) to segment the customer data. Finally, we will visualize the segmentation found (clusters) and analyze them.
 
 
In  science project, in which we will focus on applying: **Data processing, Exploratory Data Analysis (EDA), Data Visualization, Feature Selection, and Multiple Regression model** aiming to predict a car price.
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
