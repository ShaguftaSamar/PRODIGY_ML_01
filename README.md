# Task 01
Implement a linear regression model to predict the prices of houses based on their square footage and the number of bedrooms and bathrooms.

## Objective

The objective of this task is to **implement a Linear Regression model** to predict house prices based on **square footage, number of bedrooms, and number of bathrooms**.

---

## Dataset

The dataset used is the **House Prices – Advanced Regression Techniques** dataset from Kaggle:
[House Prices Dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)

* **Training data:** Contains house features and their corresponding sale prices.
* **Test data:** Contains house features for which the sale prices need to be predicted.

---

## Steps Implemented

### Step 1: Import Required Libraries

Used Python libraries such as:

* `pandas` & `numpy` for data handling
* `matplotlib` & `seaborn` for visualization
* `sklearn` for machine learning

### Step 2: Load Dataset

Loaded training and test datasets from CSV files.

### Step 3: Dataset Exploration

* Checked for **missing values** and **duplicates**
* Explored dataset dimensions and column information

### Step 4: Feature Engineering

* Created a new feature `TotalBath` = `FullBath + 0.5 * HalfBath`
* Selected features: `GrLivArea` (square footage), `BedroomAbvGr` (number of bedrooms), `TotalBath`

### Step 5: Exploratory Data Analysis (EDA)

* Visualized **SalePrice distribution**
* Checked **correlation** of selected features with SalePrice
* Plotted **scatter plots** and **heatmaps** for better understanding

### Step 6: Train/Test Split and Model Training

* Split the training data into **training** and **validation** sets
* Trained a **Linear Regression** model
* Predicted Sale Prices on validation data
* Visualized **Actual vs Predicted Sale Prices** and **residuals**

### Step 7: Example Prediction

* Created an example input with sample house features
* Predicted the house price using the trained model

### Step 8: Predict on Test Data

* Prepared the test dataset
* Predicted Sale Prices using the trained model

### Step 9: Save Submission

* Saved the predicted prices for the test data in a CSV file `submission.csv`

---

## Key Learnings

* Hands-on experience with **data preprocessing** and handling missing values
* Feature engineering to improve model input
* Applied **Linear Regression** on a real-world dataset
* Performed **visualizations** to evaluate predictions

---

## Results

* Successfully trained the model on the selected features
* Generated predictions for unseen test data
