# HOUSE-PRICE-PREDICTION-MODEL

This project uses machine learning to predict house prices based on features like area, bedrooms, and location.

## Data

* Dataset: Housing.csv
* Contains information about houses, including area, bedrooms, bathrooms, location, etc.

## Steps

1. **Data Loading and Cleaning:**
    * Loaded the dataset using pandas.
    * Converted categorical variables into numerical representations. 
2. **Exploratory Data Analysis:**
   * Analyzed the relationship between features and price using correlation and box plots.
3. **Feature Selection and Engineering:**
   * Selected relevant features for the model. 
4. **Model Building:**
    * Split the data into training and testing sets (80% train, 20% test).
    * Trained a Linear Regression model, Support Vector Machine and Decision Tree.
5. **Evaluation:**
    * Evaluated the model using the R-squared metric.
    * Calculated model coefficients and intercept.


## Results

* The Linear Regression model achieved an accuracy of 60% on the test set.
* Other models were also explored (Support Vector Machine, Decision Tree) but results are not included in this README.

## Usage

To use this notebook, upload your `Housing.csv` file to Google Colab and run the code cells sequentially. You can modify the code to experiment with different models and parameters.
