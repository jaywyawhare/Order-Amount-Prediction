# Order Amount Prediction

## Objective 
Build a Machine Learning model to predict the order amount that customers can place in the upcoming days. 

## Data Description 
The [dataset](https://drive.google.com/uc?id=1n8uvqL9lkwVUgzvXWrTXzp2WKtVxAQWr&export=download) contains the past orders information and behavior of various buyers. Based on the previous orders patterns, the ML model needs to predict what will be the amount of orders the customer is going to place in the upcoming days.

## Requirements
The project requires the following packages to be installed:

- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

To install these packages, you can run the following command:


- Clone the repository to your local machine:
```bash
> git clone https://github.com/jaywyawhare/Order-Amount-Prediction.git
```

- Navigate to the project directory:
```bash
> cd Order-Amount-Prediction
```

- Install the required packages:

```bash
> pip install -r requirements.txt
```

## Problem Statement

The objective of the first half of the summer internship project is:
- To build a Machine Learning Model to predict the order amount, customers might make in the upcoming days.



## [Milestone 1 - Data Sanity ( by using Numpy and Pandas)](./notebook/Milestone%201%20-%20Data%20Sanity.ipynb)

1. Use the PRS dataset to create a dataframe
1. Check the description of the dataframe
1. Check the shape of the dataframe
1. Check the data frame informations
1. Check for the Null values in the dataframe
1. Replace all the null values with "NaN"
1. Change the format of date columns - "ORDER_CREATION_DATE" to datetime[64] with the format as "%Y%m%d"
1. Do the same activity for the other date field i.e. "REQUESTED_DELIVERY_DATE" to datetime[64] with the format as "%Y%m%d"
1. Sanity check - Check how many records are having order date greater than the delivery date
1. Remove those records where order date is greater than the delivery date 
1. Check the number of records where the “ORDER_AMOUNT” field is having “-” in it.
1. Replace “-” with “” from the “ORDER_AMOUNT” field. 
1. Check the number of records where the “ORDER_AMOUNT” field is having “,” in it..
1. Replace “,” with “.” from the “ORDER_AMOUNT” field. 
1. Count the number of records where the order date and the delivery date are same
1. Count the number of records for each currency type by using the field “'ORDER_CURRENCY'”
1. Create a new column in the existing dataframe as “'amount_in_usd'” and convert all the non-USD currencies in USD and store them in the same column. 
1. Check for values “0” in the “'amount_in_usd” column. 
1. Create a new column in the existing dataframe “unique_cust_id” by adding 'CUSTOMER_NUMBER' and 'COMPANY_CODE'

## [Milestone 2 - EDA](./notebook/Milestone%202%20-%20EDA.ipynb)

1. Create a Histogram on DISTRIBUTION_CHANNEL
1. Create a Pie Chart on ORDER_CURRENCY
1. Create a line chart PURCHASE_ORDER_TYPE and DISTRIBUTION_CHANNEL
1. Create a line plot on ORDER_CREATION_DATE and amount_in_usd
1. Create a boxplot on ORDER_AMOUNT	to find out the outliers
1. Create a barchart on COMPANY_CODE and ORDER_AMOUNT

## [Milestone 3 - Feature Engineering and Selection](./notebook/Milestone%203%20-%20Feature%20Engineering%20and%20Selection.ipynb)

1. Check for the outliers in the “amount_in_usd” column and replace the outliers with appropriate values, discussed in the sessions.
1. Label encoding or One hot Encoding on all the categorical columns 
1. Log Transformations on continuous columns 
1. Try to extract new features by grouping existing columns 
1. Create a heatmap to find correlation between the columns
1. Try to identify important or relevant columns for feature extraction


## [Milestone 4 - ML Models and Evaluations](./notebook/Milestone%204%20-%20ML%20Models%20and%20Evaluations.ipynb)

1. Modify the dataset to pass into any type of machine learning models. 
1. Try different machine learning models like - 
    - Linear Regression
    - Support Vector Machine 
    - Decision Tree
    - Random Forest 
    - AdaBoost
    - Xgboost etc. 
1. Perform Regression model evaluations like MSE, RMSE, R-Square etc.
1. Compare the accuracies of all the models 
1. Select the best possible model
1. Perform Hyperparameter tuning, select best hyperparameters by using appropriate algorithms, come up with the best possible model accuracy.
