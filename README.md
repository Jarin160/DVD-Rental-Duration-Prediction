# DVD Rental Duration Prediction
---
This project aims to predict the **rental length of DVD** based on various features using different regression models.

## Project Overview
The notebook performs end-to-end data analysis and machine learning tasks to predict the duration (in days) of a movie rental. It includes data preprocessing, feature engineering, feature selection, model training, and evaluation.

---

## Project Structure

1. **Data Loading and Exploration**  
   - Loads the dataset and performs an initial inspection (data types, shape, missing values, value counts).

2. **Feature Engineering**  
   - Creates new features such as:
     - `rental_length_days`
     - `deleted_scenes`
     - `behind_the_scenes`
     - `trailers`

3. **Data Preprocessing**  
   - Drops unnecessary columns and encodes categorical variables for model compatibility.

4. **Feature Selection**  
   - Applies **Lasso Regression** to identify the most significant features for predicting rental length.

5. **Model Training and Evaluation**  
   - Trains and evaluates multiple regression models:
     - Linear Regression  
     - Decision Tree Regressor  
     - Random Forest Regressor  
     - XGBoost Regressor  
   - Evaluates models using **Mean Squared Error (MSE)** and **R-squared (R²)**.  
   - Performs **cross-validation** for robust performance estimation.

---

## Dataset

**File:** Predicting Movie Rental Durations: https://www.kaggle.com/datasets/anhdungdang/predicting-movie-rental-durations


---
