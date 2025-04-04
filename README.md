1.	Load data file using pandas
2.	Check for null values in the data. Get the number of null values for each column
3.	Drop records with nulls in any of the columns
4.	Variables seem to have incorrect type and inconsistent formatting. You need to fix them
5.	Sanity checks
a.	Reviews should not be more than installs as only those who installed can review the app. If there are any such records, drop them.
b.	For free apps (type = “Free”), the price should not be >0. Drop any such rows.
6.	Performing univariate analysis
7.	Outlier treatment
8.	Bivariate analysis: Let’s look at how the available predictors relate to the variable of interest, i.e., our target variable rating. Make scatter plots (for numeric features) and box plots (for character features) to assess the relations between rating and the other features.
9.	Data preprocessing
10.	Train test split and apply 70-30 split. Name the new data frames df_train and df_test.
11.	Separate the data frames into X_Train, y_train, X_test, and y_test
12.	 Model building
