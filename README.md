=================================================================================
# House Price Prediction - Advanced Regression Assignment
=================================================================================
#### Built a Advanced Regression model to purchase houses at a price below their actual values and flip them on at a higher price.
=================================================================================
**A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.** 

=================================================================================
## General Information
=================================================================================

	- The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
	- The company wants to know the following things about the prospective properties:

        Which variables are significant in predicting the price of a house, and
        How well those variables describe the price of a house. Also, determine the optimal value of lambda for ridge and lasso regression.
        
	- Input Data:

        Surprise Housing Data Set: Contains the sale of houses in Australia.
        Surprise Housing Data dictionary: Data dictionary which describes the meaning of all the variables present in Housing data set.
 
	- Language used : Python for Data Science . Tools Used - MS Excel

=================================================================================
## Business objective
=================================================================================

>You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.. 

=================================================================================
## Project Statement
=================================================================================

> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

> The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

> The company wants to know the following things about the prospective properties:

	- Which variables are significant in predicting the price of a house, and
	- How well those variables describe the price of a house.

> Also, determine the optimal value of lambda for ridge and lasso regression.


=================================================================================
## Data Set
=================================================================================

> train.csv have the following fields:

	- MSSubClass: Identifies the type of dwelling involved in the sale.	
	- MSZoning: Identifies the general zoning classification of the sale.
	- LotFrontage: Linear feet of street connected to property
	- LotArea: Lot size in square feet
	- Street: Type of road access to property
	- Alley: Type of alley access to property
	- LotShape: General shape of property
	- LandContour: Flatness of the property
	- Utilities: Type of utilities available
	- LotConfig: Lot configuration
	- LandSlope: Slope of property
	- Neighborhood: Physical locations within Ames city limits
	- Condition1: Proximity to various conditions
	- Condition2: Proximity to various conditions (if more than one is present)
	- BldgType: Type of dwelling
	- HouseStyle: Style of dwelling
	- OverallQual: Rates the overall material and finish of the house
	- OverallCond: Rates the overall condition of the house
	- YearBuilt: Original construction date
	- YearRemodAdd: Remodel date (same as construction date if no remodeling or additions)
	- RoofStyle: Type of roof
	- RoofMatl: Roof material
	- Exterior1st: Exterior covering on house
	- Exterior2nd: Exterior covering on house (if more than one material)
	- MasVnrType: Masonry veneer type
	- MasVnrArea: Masonry veneer area in square feet
	- ExterQual: Evaluates the quality of the material on the exterior 
	- ExterCond: Evaluates the present condition of the material on the exterior
	- Foundation: Type of foundation
	- BsmtQual: Evaluates the height of the basement
	- BsmtCond: Evaluates the general condition of the basement
	- BsmtExposure: Refers to walkout or garden level walls
	- BsmtFinType1: Rating of basement finished area
	- BsmtFinSF1: Type 1 finished square feet
	- BsmtFinType2: Rating of basement finished area (if multiple types)
	- BsmtFinSF2: Type 2 finished square feet
	- BsmtUnfSF: Unfinished square feet of basement area
	- TotalBsmtSF: Total square feet of basement area
	- Heating: Type of heating
	- HeatingQC: Heating quality and condition
	- CentralAir: Central air conditioning
	- Electrical: Electrical system
	- 1stFlrSF: First Floor square feet
	- 2ndFlrSF: Second floor square feet
	- LowQualFinSF: Low quality finished square feet (all floors)
	- GrLivArea: Above grade (ground) living area square feet
	- BsmtFullBath: Basement full bathrooms
	- BsmtHalfBath: Basement half bathrooms
	- FullBath: Full bathrooms above grade
	- HalfBath: Half baths above grade
	- Bedroom: Bedrooms above grade (does NOT include basement bedrooms)
	- Kitchen: Kitchens above grade
	- KitchenQual: Kitchen quality
	- TotRmsAbvGrd: Total rooms above grade (does not include bathrooms)
	- Functional: Home functionality (Assume typical unless deductions are warranted)
	- Fireplaces: Number of fireplaces
	- FireplaceQu: Fireplace quality
	- GarageType: Garage location
	- GarageYrBlt: Year garage was built
	- GarageFinish: Interior finish of the garage
	- GarageCars: Size of garage in car capacity
	- GarageArea: Size of garage in square feet
	- GarageQual: Garage quality
	- GarageCond: Garage condition
	- PavedDrive: Paved driveway
	- WoodDeckSF: Wood deck area in square feet
	- OpenPorchSF: Open porch area in square feet
	- EnclosedPorch: Enclosed porch area in square feet
	- 3SsnPorch: Three season porch area in square feet
	- ScreenPorch: Screen porch area in square feet
	- PoolArea: Pool area in square feet
	- PoolQC: Pool quality
	- Fence: Fence quality
	- MiscFeature: Miscellaneous feature not covered in other categories
	- MiscVal: $Value of miscellaneous feature
	- MoSold: Month Sold (MM)
	- YrSold: Year Sold (YYYY)
	- SaleType: Type of sale
	- SaleCondition: Condition of sale

=================================================================================
## Methods Usedology
=================================================================================

>Step1: Data Understanding and Exploration
>Step2: Data cleaning and Visualization
>Step 3: Data preparation -EDA
>Step 4: Model Building and Evaluation
>Step 5: Residual Analysis
>Step 5: Conclusion

=================================================================================
## Technologies Used
=================================================================================

	- Python -version 3.11.3
	- Pandas - version 1.5.3
	- NumPy - version 1.23.5
	- Seaborn - version 0.14.0
	- MatplotLib - version 3.4.3
	- Plotly - version 5.7.0
	- statsmodels - version 0.12.2
	- sklearn - version 0.24.2
	- scipy - version 1.7.1
	- Jupyter Notebook - Version 6.5.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


=================================================================================
## Problem Statement
=================================================================================

> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

> The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

> The company wants to know the following things about the prospective properties:

	- Which variables are significant in predicting the price of a house, and
	- How well those variables describe the price of a house.

> Also, determine the optimal value of lambda for ridge and lasso regression.


=================================================================================
## Problem Solving Methodology
=================================================================================

Step1: Data Understanding and Exploration

	1.1 Data Sourcing - Import all required Python libaries
	1.2 Importing dataset to csv
	1.3 Check Metadata using info() of DataFrame

Step2: Data cleaning and Visualization

	2.1 checking percentage of null values in each column
	2.2 Drop unnecessary rows and column
	2.3 Analysis variable and see what best we can fit
	2.4 Checking the values count for selected three missing variable
	2.5 Health check of dataframe before Data Preparation
		2.5.1 Derive new columns
		2.5.2 Dropping some variablez as these are of no use anymore.
		2.5.3 Take variables which are highly correlated, First normalize and then find those variable.
		2.5.4 identify outliers -  Let's calculate using Inter-Quartile Range
		2.4.5 plotting distribution of 'SalePrice' without transformation and see behaviour.
		2.4.6 plotting distribution of 'SalePrice' tranform the dependent variable by taking LOG
		2.4.7 check the correlation coefficients using HeatMap.
		2.4.8 plot a graph using scatter plot for all numFeatures data with target variable 'SalePrice'
		2.4.9 Avoid repetation code so creating function for displaying box plot

Step 3: Data preparation -EDA

	3.1 Ordered categorical variables which need to be converted to numerical values.
	3.2 Get dummies for unordered categorical columns.
	3.3 Splitting the Data into Training and Testing Sets
	3.4 Rescaling the features by Creating MinMaxScaler instance
	3.5 Fit and Transform the Train Data & Transform the Test Data Set
	3.6 Heatmap Analysis of Train Data Set to find out which variable is performing well
	3.7 Divide Train and Test Data into X and Y sets

Step 4: Model Building and Evaluation

	==================	
	Linear Regression:
	==================
	4.1 Creating an object of linear Regression.
	4.2 Fitting a model in Linear Regression using RFE
		4.2.1 Display columns selected by RFE and their weights.
	4.3 Fit new Train Data Set and find R2 score for them.
		4.3.1 Display coefficient and intercept
	4.4 Creating a function which will print R2 Score, RSS, MSE and RMSE for both Train and Test Data Set
	4.5 Predict and analysis the R2 Score, RSS, MSE and RMSE for both Train and Test Data Set
	
	==================
	Ridge Regression:
	==================
	4.6 Regularization using Ridge Regression
	4.7 Printing the best hyperparameter alpha using Ridge Regression
	4.8 Plotting mean test and train set with alpha VS R2 scores using Ridge Regression
	4.9 Fitting Ridge model for alpha = 2 and printing coefficients which have been penalised
	4.10 Predict using Ridge Model Evaluation on train and test set with R2, RSS MSE and RMSE Score
	4.11 Analysis Coefficient prediction of Top 10 feature of Ridge Regression

	==================
	Lasso Regression:
	==================
	4.12 Regularization using Lasso Regression
		4.12.1 list of alphas to tune using Lasso Regression
	4.13 Printing the best hyperparameter alpha using Lasso Regression
	4.14 Plotting mean test and train set with alpha VS R2 scores using Lasso Regression
	4.15 Predict the best (Best param, Best Score & Best estimator) hyperparameter alpha using Lasso Regression
	4.16 Plotting mean test and train set with alpha VS R2 scores using Lasso Regression
	4.17 Fitting Lasso model for alpha = 0.0001 and printing coefficients which have been penalised
	4.18 Predict using Lasso Model Evaluation on train and test set with R2, RSS MSE and RMSE Score
	4.19 Analysis Coefficient prediction of Top 10 feature of Lasso Regression
	4.20 Compare all metrics & all Regression together
	4.21 Observe the changes in the coefficients of all the Regression after regularization

Step 5: Residual Analysis:

	5.1 Residual analysis comparision between Error Distribution on Train Data and Test Data
	5.2 Residual analysis comparision between Residual Vs Predictive Values for Train Data and Test Data
	5.3 Residual analysis comparision between Actual Vs Predictive Train Values and Test Values

Step 6: Conclusion

=================================================================================
## Important Points to remember while solving the Assignment :
=================================================================================



=================================================================================
## Conclusions
=================================================================================
>The residual analysis for both test and train data seem to fit the assumptions of the Linear Regression.
>Residuals have mean of zero and closely normally distributed.
>Residuals do not have any pattern hence it has homoscedasticity.

>Below are the TOP 10 variables which are significant in predicting the Sale Price.

	GrLivArea: Above grade (ground) living area square feet.
	OverallQual: Rates the overall material and finish of the house.
	MSZoning_RL: Identifies residential with Low Density zone.
	MSZoning_RH: Identifies residential with High Density zone.
	OverallCond: Rates the overall condition of the house.
	GarageCars: Size of garage in car capacity.
	LotArea: Lot size in square feet
	BedroomAbvGr: Bedrooms above grade (does NOT include basement bedrooms)
	MSZoning_RM: Identifies residential with Medium Density zone.
	MSZoning_FV: Identifies residential with Floating Village Residential

>Ridge Regression
	R2 score(Train): 90.05%
	R2 score(Test): 87.86%

>Lasso Regression
	R2 score(Train): 89.88%
	R2 score(Test): 88.20%

>Optimal value of alpha for Ridge and Lasso Regression is below:
	Alpha value for Ridge Regression: 1
	Alpha value for Lasso Regression: 0.0001

=======================================

	Though the model performance by Ridge Regression was better in terms of R2 values of Train and Test, it is better to use Lasso, since  it brings and assigns a zero value to insignificant features, enabling us to choose the predictive variables.
	It is always advisable to use simple yet robust model.
	Equation can be formulated using the features and coefficients obtained by Lasso.

=================================================================================
## Acknowledgements
=================================================================================
>This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course.


=================================================================================
## Contributors
=================================================================================
* [Debasish Deaty] 
Email: ddeaty@gmail.com 
(https://github.com/ddeaty/)

=================================================================================