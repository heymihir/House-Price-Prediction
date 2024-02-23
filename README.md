## House Price Prediction

#### Overview

 A US-based company, is planning to enter the Australian real estate market. The company aims to use advanced regression techniques, specifically Ridge Regression, to predict house prices accurately. The dataset, provided in the 'test.csv' file, consists of information from the sale of houses in Australia.

The primary objectives are:

1. **Identify significant variables that predict the price of a house.**
2. **Assess the predictive power of these variables.**

#### Approach

The repository follows a systematic approach to build a regression model using Ridge Regression. The key steps include:

1. **Exploratory Data Analysis (EDA):** Understanding the dataset through visualizations and summary statistics.

2. **Data Preprocessing:**
   - Handling missing values.
   - Creating dummy variables for categorical features.
   - Feature engineering to extract meaningful information.

3. **Feature Selection:**
   - Using Ridge Regression with GridSearchCV to find the optimum alpha.
   - Applying Recursive Feature Elimination (RFE) to select the top features.

4. **Model Building:**
   - Building the Ridge Regression model with the selected features.
   - Evaluating the model's performance on the test dataset.

5. **Result Analysis:**
   - Displaying the coefficients of the model.
   - Identifying and removing redundant features.