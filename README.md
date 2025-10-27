
# California House Price Predictor

## Project Goal
The goal of this project was to build a simple linear regression model to predict the median house value in California districts, based on features from the 1990 census.

## Dataset
This project uses the **California Housing Prices** dataset, which is included in the Scikit-learn library.

## Project Steps
1.  **Data Loading:** Loaded the dataset and converted it into a Pandas DataFrame.
2.  **Exploratory Data Analysis (EDA):** * Checked for missing values (found none).
    * Plotted `Median Income` vs. `Price` to find a positive relationship.
3.  **Data Preparation:** Separated the data into features (`X`) and the target (`y`).
4.  **Train/Test Split:** Split the data into an 80% training set and a 20% test set.
5.  **Modeling:** * Chose a **Linear Regression** model.
    * Trained (fit) the model on the training data.
6.  **Evaluation:** * Tested the model on the unseen test data.
    * Evaluated the model's performance using R-squared and Mean Absolute Error (MAE).

## Results
The final model achieved the following performance on the test set:
* **R-squared ($R^2$):** 0.59 (The model explains 59% of the price variance)
* **Mean Absolute Error (MAE):** $51,139 (On average, the model's price prediction was off by this amount)

## Tools Used
* Python
* Pandas
* Scikit-learn
* Matplotlib
