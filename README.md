# Credit-Card-Customer-Prediction

**DOMAIN:** Banking

**CONTEXT:** Dataset 2 is a list of bank customers who have a credit card with the bank. It suggests whether a credit
card customer is performing good or bad for a bank. It contains 20 features including demographic,
socio-economic, and transactional variables for 5050 customers who have an active credit card with
the bank.

**DATA DESCRIPTION:** The data contains a 'class' variable where bad=Customers who are not profitable
credit card holders for the bank and Good=Customers who are profitable credit card holders for the
bank. Customer_id is a unique serial number/identifier of each customer. 

**PROJECT OBJECTIVE:**  Develop a machine learning model to predict the customer who are more profitable for the bank.


**DATA EXPLORATION AND DATA CLEANING:**

Combined the two files to create a single file with all the relevant variables and perform the necessary data quality checks and cleaning. In data cleaning, checked for the missing values/unexpected values in the dataset. Also, checked for the outliers in the dataset (if any). Also, make sure that the data types of the variables are appropriate as required for our analysis (Here, converted all the categorical variable data types to category and continuous variable data types to int or float).

**DATA ANALYSIS:**

Checked the distribution of data for the continuous (histogram charts) and categorical (pie charts) variables along with the target variable (pie charts). Performed uni-variate, bivariate, and multivariate analysis of the dataset, for example, 5-point summary of the continuous variable, pair plot, correlation matrix plot, and boxplot to detect outliers.

**DATA PREPROCESSING:**

Here, removed the unwanted/irrelevant independent variable/feature based on the above analysis from the dataset. Also, encoded the categorical variable using one-hot encoding and label encoding based on the categories, and scaled the independent variable using standard scaler.

**MODEL BUILDING, EVALUATION AND IMPROVEMENT:**

Used k nearest neighbour, logistic regression, and support vector machine (SVM) algorithm to predict the customer who are more profitable and evaluate the model using confusion metrix, accuracy score, recall score, precision score and f1 score. Further tunned the models using GridsearchCV and compared all the models to find the best model.

**After comparing we can see that, accuracy for all the models is very low for both training and testing set. The highest accuracy achieved is 66.98%. So we can conclude that the models did not learn properly from the dataset, there is less number of datapoints. The models are underfitiing.**

**Recommendations: Need to increase the data points with quality.**


