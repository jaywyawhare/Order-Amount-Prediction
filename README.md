# Order Amount Prediction

This project aims to build a Machine Learning model to predict the order amount that customers can place in the upcoming days based on their past order information and behavior.

<i>(This project is an assignment for the HighRadius unpaid internship for the 2024 passing out batch.) </i>

## Project Structure
The project is structured as follows:

- <b>data/</b> : This directory contains the [dataset](https://drive.google.com/uc?id=1n8uvqL9lkwVUgzvXWrTXzp2WKtVxAQWr&export=download) used for training and evaluation.
- <b>notebooks/</b> : This directory contains Jupyter notebooks for each milestone of the project.
- <b>requirements.txt</b> : This file lists the required packages and dependencies for running the project.
- <b>README.md</b> : This file provides an overview of the project and its objectives.

## Requirements
The project requires the following packages to be installed:

- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

To install these packages, you can run the following command:

```bash
pip install -r requirements.txt
```

## Milestones
The project consists of several milestones, each focusing on a specific task. Here is a summary of the milestones:

1. <b>[Data Sanity](./notebook/Milestone%201%20-%20Data%20Sanity.ipynb) </b>: In this milestone, we perform data cleaning and preprocessing tasks such as handling missing values, formatting date columns, removing inconsistent records, and converting currency values to USD.

1. <b>[EDA (Exploratory Data Analysis)](./notebook/Milestone%202%20-%20EDA.ipynb) </b>: This milestone involves analyzing the dataset to gain insights and understand the relationships between variables. We create visualizations such as histograms, pie charts, line plots, and box plots to explore different aspects of the data.

1. <b>[Feature Engineering and Selection](./notebook/Milestone%203%20-%20Feature%20Engineering%20and%20Selection.ipynb) </b>: In this milestone, we perform feature engineering techniques such as encoding categorical variables, applying log transformations to continuous columns, and creating new features through grouping. We also analyze the correlation between variables using a heatmap and select relevant features for prediction.

1. <b>[ML Models and Evaluations](./notebook/Milestone%204%20-%20ML%20Models%20and%20Evaluations.ipynb) </b>: This milestone focuses on building and evaluating different machine learning models for order amount prediction. We try various models such as Linear Regression, Support Vector Machine, Decision Tree, Random Forest, AdaBoost, and XGBoost. We perform model evaluations using metrics like Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-Squared. We compare the accuracies of the models and select the best-performing one. We also perform hyperparameter tuning to further improve the model's accuracy.

Please refer to the individual Jupyter notebooks in the <b>notebooks/</b> directory for detailed explanations and code implementation for each milestone.

## Usage
To use this project, follow these steps:

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/jaywyawhare/Order-Amount-Prediction.git
    ```

1. Navigate to the project directory:

    ```bash
    cd Order-Amount-Prediction
    ```

1. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

1. Open the Jupyter notebooks in the notebooks/ directory to view and run the code for each milestone.

## Conclusion
This project provides a framework for predicting order amounts using Machine Learning techniques. By following the milestones and implementing the necessary tasks, you can build and evaluate models for order amount prediction. Feel free to customize and expand upon the project to suit your specific requirements.

If you have any questions or need further assistance, please feel free to reach out.

