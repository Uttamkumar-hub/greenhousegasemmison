# greenhousegasemmison
# Week 1 – Emission Data Cleaning & Visualization

 The task involved working on a dataset of **Supply Chain Emission Factors for US Industries (2016)**.

## ✅ Tasks Completed

1. **Data Loading**  
   The Excel file `SupplyChainEmissionFactorsforUSIndustriesCommodities2.xlsx` was loaded using Pandas.

2. **Data Cleaning**  
   - Rows with null values in the `Supply Chain GHG Emission Factors for US Commodities and Industries` column were removed.
   - Duplicate rows were also removed.

3. **Data Analysis**  
   - Emissions were aggregated by industry.
   - The top 10 industries with the highest emissions were identified.

4. **Data Visualization**  
   - A **bar chart** shows the top 10 industries with the highest emissions.
   - A **histogram** illustrates the overall emission distribution across all industries.

## 📊 Output Files

- `top_10_industries_emissions.png`: Bar chart of top emitters.
- `emission_distribution_histogram.png`: Histogram of emission distribution.

## 📦 Tools Used

- Python
- Pandas
- Seaborn
- Matplotlib
## week2
📝 Tasks Performed

Data Cleaning: Removed missing values and irrelevant columns from the supply chain emissions dataset.

Feature Selection: Chose relevant features to predict greenhouse gas emissions.

Model Training: Trained three regression models – Linear Regression, Decision Tree, and Random Forest.

Model Evaluation: Assessed models using MAE, RMSE, and R² metrics.

Hyperparameter Tuning: Applied GridSearchCV to optimize the Random Forest model.

Result Comparison: Compared model performances to select the best one for emission prediction.

Week 3: 
Optimization, Insights, and Future Prediction
✅ Hyperparameter Tuning:
Performed GridSearchCV on Random Forest for optimal n_estimators, max_depth, and min_samples_split.
✅ Residual Analysis:
Visualized residual distribution for the best model to assess bias and variance.
✅ Feature Importance:
Identified key drivers of emissions using feature_importances_ of the tuned Random Forest model.
✅ Model Comparison:
Aggregated and visualized performance of all models side-by-side using grouped bar plots.
✅ Future Emission Prediction:
Projected emissions for the next year using the most recent data.
Merged predictions with industry names for better interpretability.



