[Final project information](https://sandiego.instructure.com/courses/26534/pages/review-final-team-project-introduction?module_item_id=1046527)

- Group - Asher and Jordan
- Dataset - Dataset 2 (House Sales)
- Language - Python
- Analysis Type - Multiple Linear Regression

Ideas
- Multiple Linear Regression (MLR) - predict price (dependent variable) from some combination of some of the independent variables. "What is the specific dollar value of this house?"

Steps for MLR
Data pre-processing/cleaning (EDA process)
- Handle missing values and outliers
- Engineer any features (year built minus date after converting date to year, zip code regions through first three numbers, etc.)
- Scaling variables or any other data transformations for non-linear relationships, also interaction effects. This may change after data visualization.
Data Visualization
- Correlation heatmap, box plots (both individual and over key groups), scatter plots, distribution plots, qq plots.
Data Analysis
- Check for multicollinearity (VIF), drop variables based on overlap from correlation heatmaps to reduce VIF.
- Check for model fit - do not over fit.
- Check residuals (heteroskedasticity, Durbin-Watson)
    - Repeat until satisfied.


### Asher – Initial Notes (3/11)

- I agree that the House Sales dataset offers strong flexibility both for portfolio value and for exploring different analytical approaches.
- My initial instinct is that a regression-focused approach may be the most straightforward place to start, since sale price provides a clear target variable. If time allows, I would be open to exploring both supervised and unsupervised methods.
- I can begin by reviewing the dataset structure, checking for missing values, and identifying candidate features for preprocessing and early EDA.
- Looking forward to discussing the best collaborative workflow during our first meeting on 3/12.


### Summary of Jordan's work on 3/15

- Perform all steps laid out below from the final team project introduction page
    - Data Importing and Pre-processing
        - Import dataset and describe characteristics such as dimensions, data types, file types, and import methods used
        - Clean, wrangle, and handle missing data
        - Transform data appropriately using techniques such as aggregation, normalization, and feature construction
        - Reduce redundant data and perform need-based discretization
