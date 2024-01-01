# Predicting_Fuel_Economy
Automobile characteristics that impact the fuel economy
## Situation
### As a product data scientist for Consumer Reports Magazine, a trusted source for information on consumer products and services. The assignment was that fuel economy is a major factor in the cost of owning a car. So, they were studying that automobile characteristics that impact the fuel economy for an upcoming article. I had to build a regression model to predict fuel economy based on characteristics like car’s weight, model year acceleration and more. The objectives were to prepare and explore the data for modelling split the data and build a multiple regression model, evaluate model, test performance, and interpret the model. In last, I built a ridge regression model and compared the results with my linear regression model. 
### OBJECTIVE 1: Prepare and Explore the Data.
#### The first objective was to prepare the data for modelling, explore the target ('mpg') and other features in the dataset, and fix any issues you encounter.
##### 1. Read in the auto-mpg.csv dataset, and check datatypes and columns for missing or unusual values.
##### 2. Calculate summary statistics for each of the numeric columns in the dataset including min, max and mean, then build a histogram of the target variable (‘mpg’).
##### 3. Explore relationships between the features and the ‘mpg’ column, and use scatterplots and build a correlation heatmap. Which column is most strongly correlated with ‘mpg’?

### OBJECTIVE 2: Split the data and build a multiple regression model.
#### The second objective is to split the data into training and test data, then fit a multiple regression model using the validation scheme of choice. Perform feature engineering and variable selection, and check whether any assumptions are violated.
##### 1. Split the data into train and test, then then set up a validation scheme of your choice and fit a baseline regression model using the feature with the strongest correlation to the target (‘mpg’).
##### 2. Fit a multiple regression model. Perform any feature selection and feature engineering necessary, fixing any violated assumptions along the way.

### OBJECTIVE 3: Evaluate model test performance and interpret the model
#### Score your model on the test data set, use your model to predict a new batch of cars, and interpret your model results. 
###### 1. Score your final model on the test set, calculating both R2 and MAE. If your test R2 is less than 8, revisit the modelling process and interpret your model. What impact does a one-year increase in model year have on the predicted mileage?
