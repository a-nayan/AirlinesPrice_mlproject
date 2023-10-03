# AirlinesPrice_mlproject

THIS PROJECT IS TO CREATE A MODEL TO PREDICT THE PRICE OF FLIGHT.

Steps performed
1) Data ingestion
2) Data cleaning 
	- Checks for missing values
	- Drop irrelevant features
	- Drop irrelevant rows
	- Conversion of feature data type to appropriate data type
	- Creation of additional features from existing features
	- Ensure data integrity
3) Exploratory data analysis
	- Plot different graphs to establish relationship between Flight price and Flight duration 
4) Feature Engineering
	- Feature Encoding - use One hot Encoding, Label Encoding and Target guided Encoding
 	- Outlier Detection and handling- use histogram/box plot to detect outlier if any
	- Calculate mutual information score between feature price and other remaining independent features. Drop features with low MI score.

5) Model Building
	- Build model
	- Train and Test
	- Calculate different scores and errors. r2_score, mean_absolute_error, mean_squared_error, mape are calculated to check how model is performing.


