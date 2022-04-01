# Deep Learning Homework: Charity Funding Predictor

## Background

The non-profit foundation Alphabet Soup wants to create an algorithm to predict whether or not applicants for funding will be successful. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

* **EIN** and **NAME**—Identification columns
* **APPLICATION_TYPE**—Alphabet Soup application type
* **AFFILIATION**—Affiliated sector of industry
* **CLASSIFICATION**—Government organization classification
* **USE_CASE**—Use case for funding
* **ORGANIZATION**—Organization type
* **STATUS**—Active status
* **INCOME_AMT**—Income classification
* **SPECIAL_CONSIDERATIONS**—Special consideration for application
* **ASK_AMT**—Funding amount requested
* **IS_SUCCESSFUL**—Was the money used effectively


### Step 1: Preprocess the data

Preprocessed the dataset in order to compile, train, and evaluate the neural network model later 


1. Read in the charity_data.csv to a Pandas DataFrame, and be sure to identify the following in your dataset:
2. Dropped the `EIN` and `NAME` columns.
3. Determined the number of unique values for each column.
4. Used the number of data points for each unique value to pick a cutoff point to bin "rare" categorical variables together in a new value, `Other`, and then checked if the binning was successful.
5. Used `pd.get_dummies()` to encode categorical variables

### Step 2: Compile, Train, and Evaluate the Model

Designed a neural network, amd deep learning model, to create a binary classification model that can predict if an Alphabet Soup–funded organization will be successful based on the features in the dataset. Later, compiled, trained, and evaluated my binary classification model to calculate the model’s loss and accuracy.

