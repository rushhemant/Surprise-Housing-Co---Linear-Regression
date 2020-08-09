# Surprise-Housing-Co---Linear-Regression
Determine:  Which variables are significant in predicting the price of a house, and  How well those variables describe the price of a house.

<font color=blue> **Read Data**	<br>
* Import important libraries	<br>
* Read housing data into dataframe	<br>
* Quick review of dataframe	<br>
	
**Data Preparation**	<br>
* Check missing values in dataframe	<br>
* Drop columns withh more than 80% missing values	<br>
* Impute LotFrontage	<br>
* Impute FireplaceQu	<br>
* Impute Garage related fields	<br>
* Impute Basement related fields	<br>
* Impute missing categorical variables with mode	<br>
* Impute missing quantitative variables with median	<br>
	
**Feature Engineering**	<br>
* Calculate age of house when sold	<br>
	
**Data Analysis**	<br>
* Check distribution of target variable	<br>
* Transform targert variable (log transformation)	<br>
* Create list of numeric and non-numeric columns	<br>
* Analyze outliers from quantitative variables	<br>
* Remove outliers from numerical data	<br>
* Bar plots of quantitative variables vs SalePrice	<br>
* Analyze impact of categorical values on price of house	<br>
* Checking correlation of quantitative variables in housing	<br>
* Pairplots for numerical variables to understand linear relationship	<br>
	
**Data Preparation for Modeling**	<br>
* Dummy variable encoding (one-hot) for other categorical variables	<br>
* Splitting the Data into Training and Testing Sets	<br>
* Create X and y sets	<br>
* Scaling the variables using StandardScaler (Normalizing)	<br>
	
**Ridge Regression**	<br>
* Tune hyperparameter using GridSearchCV	<br>
* Plotting scores to determine optimal alpha	<br>
* Build Ridge regression using best alpha	<br>
* Prediction using ridge regression	<br>
	
**Lasso Regression**	<br>
* Tune hyperparameter using GridSearchCV	<br>
* Plotting scores to determine optimal alpha	<br>
* Build Lasso regression model using best alpha	<br>
* Prediction using lasso regression	<br>
	
**Model Conclusion**	<br>
	
**Subjective Questions**	<br>
* Q1 - Setup to understand behaviour of model if alpha is changed	<br>
* Q3 - New model by removing top 5 predictor variables	<br>
