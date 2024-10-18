This README.txt file was generated on 11282023 by Rishitha Madipelli

-------------------
GENERAL INFORMATION
-------------------


1. Title of Dataset: Newspapers Churn dataset

---------------------
DATA & FILE OVERVIEW
---------------------

# dataset source: https://www.openml.org/search?type=data&status=active&id=44226&sort=runs

# Data Description: This dataset includes 15856 records of individuals who are or were subscribers to this newspaper. Datasets contain demographic information like HH Income which stands for household income, and home ownership, dummy for Children, Ethnicity, Year Of Residence, Age range, and Language; Geographic information like Address, State, City, County, Longitude, Latitude, and Zip Code. Also, the delivery period is chosen by the particular subscriber, as well as the weekly charge associated with it. The dataset also included the number of rewards subscribers used and the source channel he/she was recruited in the first place. Finally, the dataset included information on whether the customer is still our subscriber or not.

-----------------------------------------
DATA DESCRIPTION FOR: newspaper.csv
-----------------------------------------

1. Number of variables: 20


2. Number of rows: 14848

--------------------------
METHODOLOGICAL INFORMATION
--------------------------

# Software: Databricks platform
The language used is pyspark. 

1. Apache Spark installation: Apache Spark can be downloaded from the official website. 

2. Python and PySpark must be installed: Install Python on your computer. Install the pyspark library with a package manager such as pip. Mlib is already included in the spark.

For cluster deployment, a Spark cluster is necessary. A Spark cluster can be manually configured using technologies like Apache Hadoop or Apache Mesos, or you can use a cloud-based service like Databricks.

DBFS for Databricks: Sign up for an account on the Databricks website is needed.
-----
AIM
-----

The aim of this project is to predict if the user is a subscriber or not. Based on the dataset we have done exploratory analysis and trained the dataset using logistic, Random forest and Decision tree to predict which model gives the accuracy result.

-------------
MODELS USED:
-------------
1. Logistic Regression: The method of modeling the probability of a discrete result given an input variable is called logistic regression. The binary result, which might have two values like true or false, yes or no, and so forth, is what most logistic regression models represent. It is used to build a predictive model for subscribers. Pipelines are used to train and fit the model and evaluation was done using accuracy and ROC

2. Random Forest: A popular ensemble learning technique for classification, regression, and other problems is called random forests or random decision forests. It works by building a large number of decision trees during the training phase. The class that the majority of the trees choose is the random forest's output for classification problems. It is used to build a more complex model for predicting subscribers. The evaluation was done using the same metrics as decision trees. Multiple methods were used to compare their performance and identify the most effective approach for predicting subscribers in this dataset.

3. Decision Tree: Objects can be categorized based on their learning characteristics by using decision trees to solve classification problems. As a way to forecast continuous outcomes from unexpected data, they can also be applied to regression problems. Decision trees were used to build a model for predicting subscribers. 