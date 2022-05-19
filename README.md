PROJECT
ON
UNITED STATES HOUSE RENT PREDICTION



Introduction:

1.Background:
	The main goal of the research is to create a prediction model using Machine Learning to predict the rental costs of houses across the United States based on numerous variables defining the houses' attributes. This dataset contains several features that characterize the entire nature of the house and its dynamics, as well as ‘Price’ which is to be predicted.
2.Motivation:
	While renting a house we consider different factors such as location, size, number of rooms, etc. that play an important role in making the decision to rent it. This decision can sometimes be difficult to make with the rising number of options. This project will help both the landlords to set an acceptable rent on their properties and the tenants to rent the property on the right price. This prediction technique will also assist investors in making informed investment selections to optimize their profits. 
3.Goal:
	We want to build a model that can inform people what a fair rent for a specific listing (home) in a specific location with amenities would cost at any given time. Using various types of models, we want to reduce the disparity between the real rent and the rent anticipated. Various sorts of machine learning techniques will be used to assess the performance of our model.

Methodology:

	We will analyze the dataset to identify different aspects. To start with, we will perform EDA to get the overall idea of the dataset. We will then perform data cleaning by identifying the missing values, numerical variables, and their distribution. We will use Seaborn library to visualize the data to identify outliers, categorical variables, etc. We will then use Pair plot to get 2D plotting of all the features and then analyze the result which will help in choosing the right machine learning model. The potential algorithms which we can use for our data are:
•	Linear Regression
Linear regression is a widely used algorithm that predicts the output variable using a single input variable. This method also works with multivariable input. We have factors in our dataset that have a direct relationship with the goal variable, such as the location of a property, which can increase the rent price, and so on. This model, we believe, has the potential to work better with our data and should be evaluated as a possible model.
•	K-Nearest Neighbors
KNN can be utilized for both classification and regression issues, as we know. It operates by predicting values based on feature similarity and assigning a value based on similarity in the training set. By analyzing the closeness of a house in a similar region with similar traits or features, it might work with our data.
•	Decision Tree
The decision tree divides data into smaller and smaller subsets until it reaches the lowest leaf node. This model is a possible model because it has elements such as dogs allowed, parking options, etc. that could influence the rent of the house.
•	Random Forest
A decision tree collection known as a Random Forest is a collection of decision trees. It selects K data points at random from the data collection to create a decision tree for these data points. We must select the number of decision trees we require. Thus, we believe this will provide the most efficiency.
•	Gradient Boosting
Gradient boosting is one of the most popular machine learning algorithms for tabular datasets. It is powerful enough to find any nonlinear relationship between your model target and features and has great usability that can deal with missing values, outliers, and high cardinality categorical values on your features without any special treatment.

Description:

	The dataset for housing prices is 380.29 MB in size and has 22 columns with 265192 records. It contains the unique id of every house along with its details like region, type, number of rooms, amenities, pet allowances, description, location, and most important attribute ‘price’.
Data Sources:

This dataset has been taken from Kaggle
https://www.kaggle.com/datasets/rkb0023/houserentpredictiondataset
