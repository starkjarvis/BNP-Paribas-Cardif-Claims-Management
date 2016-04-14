# BNP-Paribas-Cardif-Claims-Management
In this challenge, BNP Paribas Cardif is providing an anonymized database with two categories of claims:  1. Claims for which approval could be accelerated leading to faster payments.  2. Claims for which additional information is required before approval.

SOFTWARE INSTALLATION:

Anaconda(Open Source IDE) download weblink:
https://www.continuum.io/downloads

STATISTICAL ANALYSIS: 
After receiving data from kaggle.com, my first approach was to understand how the data is to be interpreted. Since, there exists no meta-data regrading the features(columns), I wanted to find the importance of each column. 

I applied a Logistic Regression model to obtain the accuracy of the same using the given training and testing data. The output was about 75%. Furthermore, I calculated the importance of each feature based on this model. 

My next step was to apply Random Forest Classifier Ensemble. Using this feature in scikit learn, I was able to get an accuracy of 90.20%. 


INTERPRETING THE CODE:

Step 1: Impoting 'pandas', 'sklearn' [for Logistic Regression and Random Forest Classifier]. 

Step 2: Loaded the data in the separate segments of trainData, targetData and testData. 

Step 3: We cannot apply the models if other than numeric values are present. So, we first convert the String values to numeric values and then replace empty values with mean values for the feature in the dataset.

Step 4: Then Logistic Regression model was performed to check the mean accuracy. 

Step 5: Random Forest Classifier ensemble was applied to the data which achieved a mean accuracy of 90.20%.


