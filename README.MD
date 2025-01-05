# House Price Prediction: Analysis and Model Pipeline

## Overview
This project explores the **House Price Dataset of India**, focusing on predicting house prices based on various features. It involves **data analysis**, **model building**, and **error analysis** to evaluate the performance of a baseline machine learning model. The primary objective is to understand which features are most predictive of house prices and identify the model's strengths and weaknesses.

## Dataset
The dataset used in this project is the **House Price Dataset of India**. It contains information about house properties in India, including attributes like:
- Number of bedrooms
- Number of bathrooms
- Living area
- Lot area
- Year built
- Condition of the house
- Waterfront status, and more.

The dataset can be accessed from Kaggle here: [House Price Dataset of India](https://www.kaggle.com/datasets/mohamedafsal007/house-price-dataset-of-india/)

## Project Sections

### 1. **Dataset Selection and Exploration**
   - Data exploration and visualization are performed to understand the distribution of key features, including the **target feature** (`Price`).
   - Visualizations include **correlation heatmaps** and **scatter plots** to explore relationships between features and the target.

### 2. **Feature Selection and Preprocessing**
   - Relevant features like **living area**, **number of bedrooms**, and **grade of the house** are selected for the model.
   - Data preprocessing includes handling missing values and scaling the features for better model performance.

### 3. **Model Building**
   - A **baseline model** is created using **XGBoost regressor** (or a similar model).
   - The dataset is split into training and testing sets, and the model is trained using default configurations.
   - Performance is evaluated using **Mean Squared Error (MSE)**, **Root Mean Squared Error (RMSE)**, and **R-squared**.

### 4. **Error Analysis**
   - A detailed error analysis is conducted by plotting residuals (differences between predicted and actual prices).
   - The model's performance is examined for both **low-priced** and **high-priced** properties.
   - Commonalities in the **top 10 largest errors** are explored to identify patterns and weaknesses in the model.

### 5. **Conclusions and Future Work**
   - Based on the error analysis, the model's **strengths** and **weaknesses** are summarized.
   - Suggestions for improvement are provided, including potential feature engineering and model optimization.

## Requirements
You can install the necessary packages using the following command:
```bash
pip install requirements.txt
