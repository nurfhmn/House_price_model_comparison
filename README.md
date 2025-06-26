# California Housing Price Forecast Model Comparison

This project compares three different regression algorithms—Linear Regression, Support Vector Regression (SVR), and Random Forest—to predict median house values in California based on a variety of geographic and demographic features.

## Project Overview

California’s housing data contains features such as location (latitude and longitude), population, total bedrooms/rooms, median income, and proximity to the ocean. In this analysis, we:

1. **Clean and impute** missing values in the `total_bedrooms` field.  
2. **One-hot encode** the `ocean_proximity` categorical variable.  
3. **Split** the data into training (80%) and testing (20%) sets.  
4. **Train** three regression models:  
   - Linear Regression  
   - Support Vector Regression (SVR)  
   - Random Forest  
5. **Evaluate** each model on Mean Squared Error (MSE), Mean Absolute Error (MAE), and R².

## Features & Dependencies

- **Language & Framework**: R, R Markdown  
- **Key Packages**:  
  - `tidyverse` for data manipulation  
  - `caret` for data partitioning  
  - `randomForest` for ensemble modeling  
  - `e1071` for SVR  

Make sure you have R ≥ 4.0 and the above packages installed:

```r
install.packages(c("tidyverse", "caret", "randomForest", "e1071"))
