# House Price Prediction using Linear Regression

## Project Overview
This project aims to predict house prices using a Linear Regression model.  
The prediction is based on important features such as area, number of bedrooms, and number of bathrooms.

The objective of this project is to build a complete end-to-end machine learning pipeline including data preprocessing, model training, evaluation, visualization, and model interpretation.

The goal is to understand how housing characteristics influence price and evaluate the effectiveness of Linear Regression for price prediction.

## Dataset Information
The dataset contains housing-related features used to predict house prices.

### Total Records:
545

### Total Features:
13

### Features Used:
- Area
- Bedrooms
- Bathrooms

### Target Variable:
- Price

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Project Workflow

1. Importing Required Libraries  
2. Loading the Dataset  
3. Initial Data Exploration  
   - Checking dataset shape  
   - Viewing data structure  
4. Data Cleaning  
   - Handling missing values using Mean Imputation  
   - Removing duplicate records  
5. Feature Selection  
   - Defining input features (X) and target variable (y)  
6. Train-Test Split (80% Training, 20% Testing)  
7. Model Training using Linear Regression  
8. Model Prediction  
9. Model Evaluation using:
   - Mean Squared Error (MSE)
   - R² Score  
10. Visualization of Actual vs Predicted Prices  
11. Interpretation of Model Coefficients  

##  Model Performance

- Mean Squared Error (MSE): 2750040479309.0522  
- R² Score: 0.4559  

The R² score of **0.4559** indicates that approximately **46% of the variation in house prices** is explained by the selected features (area, bedrooms, and bathrooms).  

This suggests **moderate predictive performance**, meaning the model captures some patterns but may require additional features or advanced techniques for improved accuracy.

Since house prices are represented in large numerical values, the MSE appears large due to the squared error calculation.

##  Visualization

A scatter plot was created to compare Actual Prices vs Predicted Prices.  
If the data points lie close to the diagonal reference line, it indicates better model performance.

The visualization helps in understanding how closely the predicted values align with actual house prices.

## Key Insights

- The model successfully identified relationships between housing features and price.
- Area has the strongest impact on house price based on coefficient analysis.
- The current model explains nearly half of the price variation.
- Additional features such as location, age of property, amenities, and condition may improve performance.

## Conclusion

This project demonstrates a complete regression modeling workflow using Linear Regression.  

The dataset was cleaned, explored, and prepared before training the model. The trained model was evaluated using MSE and R² Score and further interpreted using coefficient analysis.

Although the model shows moderate performance, it provides meaningful insights into how housing characteristics influence price.

### Future Improvements:
- Add more relevant features
- Perform outlier analysis
- Apply feature scaling
- Try advanced models such as Random Forest or Gradient Boosting
- Perform cross-validation for more robust evaluation

## Author
Aditi
