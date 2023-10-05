# AirlinesPrice_mlproject

Project Overview:

This project aims to leverage my Data Science capabilities to build a ML model that predicts the price of a flight, helping us to stay competitive while attracting customers and not loosing too much profit.


The project consists of below parts.

1) Data ingestion
2) Data cleaning 
	- Checks for missing values
	- Drop irrelevant features
	- Drop irrelevant rows
	- Conversion of feature data type to appropriate data type
	- Creation of additional features from existing features
	- Ensure data integrity
3) Exploratory data analysis
	- Determine if Total flight duration impacts flight price. Plot different graphs to establish relationship between Flight price and Flight duration
	- Determine When will most of the flights take off? 
	- On Which Route Jet Airways is mostly used ?
	- Airline Vs Price Analysis. Create box plot for Airline and Price to establish their relation
4) Feature Engineering
	- Feature Encoding - use One hot Encoding, Label Encoding and Target guided Encoding
	- Creating new features
 	- Outlier Detection and handling- use histogram/box plot to detect outlier if any
	- Calculate mutual information score between feature price and other remaining independent features. Drop features with low MI score.

5) Model Building
	- Build model
	- Train and Test
	- Calculate different scores and errors. r2_score, mean_absolute_error, mean_squared_error, mape are calculated to check how model is performing.


Tools Used: Jupyter Notebook, Python
Skills Used: 
	Python Library -  pandas, numpy, matplotlib.pyplot, seaborn, plotly, cufflinks, statsmodels.api, sklearn.feature_selection, sklearn.model_selection, sklearn.ensemble, RandomForestRegressor, metrics, pickle, sklearn.tree, DecisionTreeRegressor
	