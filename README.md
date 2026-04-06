# 🏡 **Housing Price Prediction — Linear Regression**

## **Overview**

This project develops a linear regression model to predict housing prices using a King County-style dataset. The workflow follows a structured data science pipeline, including data preprocessing, exploratory analysis, feature engineering, and model development.

The final model emphasizes both predictive performance and interpretability, providing insight into the key factors that drive housing prices.


## **Objectives**

- Build an interpretable regression model for housing price prediction
- Evaluate model performance using out-of-sample metrics (RMSE, R²)
- Identify and quantify the impact of structural and quality-related features
- Balance predictive accuracy with model simplicity and explainability


## **Project Structure**

**1_EDA/**
- Data cleaning
- Imputation
- Outlier handling
- Feature engineering

**2_Visualization/**
- Data analysis
- Distributions
- Correlations
- Curated visualizations

**3_Model/**
- Model development
- Evaluation
- Diagnostics
- Interpretation


## **Methodology**

### Data Preprocessing

- Imputed missing values using variable-specific methods
- Removed extreme outliers using a 3×IQR threshold
- Applied log transformations to address skewness
- Engineered features such as:
    - Renovation indicator
    - Living-to-lot ratio
    - House age (including nonlinear terms)


### Exploratory Analysis

- Evaluated distributions and normality
- Assessed correlations and multicollinearity
- Identified key relationships through bivariate and curated visualizations


### Modeling Approach

- Used linear regression with log(price) as the target variable
- Applied consistent train/test splits across all models
- Evaluated models using RMSE (primary) and R²
- Performed iterative feature selection based on:
    - statistical significance
    - redundancy
    - out-of-sample performance


## **Model Selection**

Final model selected based on:
- lowest test RMSE
- stability across datasets
- interpretability

Key predictors include:
- living space
- grade and condition
- house age (nonlinear)
- lot size
- amenities (waterfront, view)


## **Results**

- The log(price) model outperformed a model using raw price in terms of RMSE
- Feature engineering and outlier handling improved model stability
- The final model captures the primary drivers of housing prices while remaining interpretable


## **Key Insights**

- Living space and grade are the strongest predictors of price
- House age exhibits a nonlinear relationship with price
- Log transformations significantly improve model fit and linearity
- Larger lot sizes may reflect location effects rather than intrinsic value


## **Tools & Technologies**

- Python (Pandas, NumPy, Matplotlib, Seaborn, Statsmodels)
- Jupyter Notebook
- Git/GitHub


## **Authors**

Asher Frank

Jordan Blackman

## AI Usage Disclosure

AI tools (e.g., Gemini, ChatGPT) were used in a supplementary capacity during this project to assist with code formatting, debugging, and refining written explanations for clarity and organization.

All data preprocessing, feature engineering, model development, and interpretation of results were independently developed and validated by the authors. AI-generated suggestions were reviewed and incorporated only when fully understood, reproducible, and appropriate to the analysis.


## Notes

This project was completed as part of a graduate-level data science course at the University of San Diego.