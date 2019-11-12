# Network-Intrusion-Detection-System
Network Intrusion Detection Binary Classification and Multi-class Classification
## BUSINESS PROBLEM: 
Your task to build network intrusion detection system to detect anamolies and attacks in the network. There are two problems. 
* 1. Binomial Classification: Activity is normal or attack 
* 2. Multinomial classification: Activity is normal or DOS or PROBE or R2L or U2R 

Please note that, currently the dependent variable (target variable) is not definied explicitly. However, you can use attack variable to define the target variable as required. 
DATA AVAILABILITY: 
This data is KDDCUP’99 data set, which is widely used as one of the few publicly available data sets for network-based anomaly detection systems. 
For more about data: http://www.unb.ca/cic/datasets/nsl.html 

## Data Prepration
* Exploring Dataset.
* Dealing with Duplicate values, Null Values, Missing values, Outliers.
* Seperating data into Numeric features and Categorical Features.
* Generating New Features from Existing
* Generating Data Audit Report for both Numerical and Categorical 

### EDA
* Box Plot
* Anova test for Variable reduction

### Converting Categorical features to numeric for machine learning
* Generating Dummies
* Merging both numeric & categorical variable

## Machine learning Models
*  Scaling Dataset(0-1)
*  Seperating Data set into Train and Test Dataset
*  Creating class for Attack Type for Multi-class Classification
*  Random Forest for variable reduction
*  Decision Tree
*  Random Forest
*  KNN(KNeighbors)
*  Logistic Regression
