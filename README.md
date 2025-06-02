## Brief analysis of a kidney disease file and model fitting
### This project reads in a small file containing features and outcomes related to kidney disease, performs cleansing, provides visual analyses, then builds and evaluates models.

The project was created to meet the criteria for a data science class. <br>
+ Reads in a small file <br>
	The csv file included in this repository was read into a Jupyter notebook. Descriptive statistics and other such outputs were performed to understand the data. <br>
+ Performs cleansing <br>
	Data was reviewed for duplicates, zero values in columns which are invalid which required imputation, unique categorical values for later one-hot encoding, and other such cleansing activities.  <br>
+ Provides visual analyses <br>
	Visual representations of various comparisons were performed using the Seaborn library, to understand the relationship between the outcome variable and the features, as well as among the features. <br>
+ Builds and evaluates models <br>
	Three models were fit to the data for comparison, the goal being which model performed the best. Those models were Logistic Regression, SVM, and a recurrent neural-network (RNN). <br>

#### Installation
This is basic Python code so you can use whatever tool you want that executes Python. I choose Anaconda running JupyterLab Version 4.0.9 <br>
#### Known issues
At the time of this Readme creation, there were no known issues. However as libraries are updated and functions deprecated, you may encounter errors and warnings.
#### Disclaimer
As this project was created for a specific class, it is not my intention to keep this up-to-date. If you choose to do pull requests and updates, feel free as long as you don't leave it in a broken state when you perform your final commit, or at least restore it back to its pre-pulled state. <br>
I expect users and contributors to realize better ways to implement the functions I put forth. I'm all for improving what I started with, but I'm a neophyte when it comes to Python so no trolling please.
  
