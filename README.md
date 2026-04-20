# House-Price-Analysis-Prediction

**Project Overview:**

- End-to-end data analytics and machine learning project to analyze key drivers of house prices and build a predictive model for accurate price estimation.

 **Tech Stack:**

- Python (Pandas, NumPy, Scikit-learn)
- Power BI (Dashboard & Visualization)
- Machine Learning (Random Forest, Linear Regression)

**Key Steps:**

- Data cleaning & missing value handling
- Exploratory Data Analysis (EDA)
- Feature selection based on correlation
- Model building & evaluation
- Prediction generation
- Interactive dashboard creation in Power BI


**Key Insights & Recommendations:**

**1. Construction Quality drives price**

 - Higher OverallQual significantly increases property value
 **Recommendation:** Focus on improving build quality to maximize returns

**2. Living Area has strong positive impact**

 - Larger GrLivArea correlates with higher prices
**Recommendation:** Optimize usable living space in property design

**3. Structural features influence pricing**

 - Garage capacity and basement size contribute to value
 **Recommendation:** Include functional features like parking and storage

**4. Newer properties command higher prices**

 - YearBuilt shows upward pricing trend
 **Recommendation:** Invest in modern construction and renovations

**Dashboard:**


**Machine Learning:**

- Built Linear Regression (baseline) and Random Forest (final model)

- Random Forest achieved **R²** = **0.88** & **MAE** = **19485.75**, capturing non-linear relationships better & performed well than linear regression model, so it was chosen as the final model 

- When Feature importance was found it confirms:

- OverallQual (dominant factor)

- GrLivArea (secondary driver)

- Model validated using actual vs predicted comparison and error analysis

