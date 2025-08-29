# Car-sales-analysis
Data analysis and machine learning to predict vehicle's optimal prices and improve inventory strategies

## Project Description
This project addresses the challenge of optimal price determination in the used car market. Through exploratory data analysis and a machine learning model, the optimal sale price is predicted based on key attributes such as mileage, year, make, and condition. The goal is to identify profit margin opportunities and optimize inventory decisions for dealerships.

## 🎯 Key Objectives
1.  **Predictive:** Build a model that estimates the sale price with greater accuracy than the base MMR (Manheim Market Report).
2.  **Strategic:** Identify vehicles with high profit potential (estimated sale price vs. MMR).
3.  **Tactical:** Provide data-driven inventory recommendations (which cars to prioritize for buying/selling).

## 🔧 Technologies Used
- **Programming Languages:** `Python`
- **Python Libraries:** `Pandas`, `NumPy`, `Scikit-learn`, `Matplotlib`, `Seaborn`
- **Tools & Platforms:** `Git`, `GitHub`, `Power BI`,  `Excel`,  `Jupyter Notebook`

## 📁 Repository Structure

*   `notebooks/` - Contains the end-to-end Jupyter Notebook (`Automotive_market_analysis.ipynb`) performing the complete data analysis, from data cleaning and exploration to model building and evaluation.
*   `output/` - Contains final deliverables and results:
    *   `auto_sales_performance.pbix` - The interactive Power BI dashboard file.
    *   `cars_valuation_tool.xlsx` - The Excel file with price calculator and key tables for inventory strategies.
*   `data/` - Contains the raw data and a document outlining the data sources and descriptions.

## 📊 Key Findings and Conclusions
*   **Model Performance:** While both the Clasical and Random Forest Regressor achieved good R² scores and low RMSE, however the solution goes beyond predicting the "perfect price". It is crucial to understand that this model does not compete with MMR, instead, it complements and refines it. The model systematically reduces the gap between the MMR benchmark and the final sale price, an achievement that directly translates into enhanced pricing precision and margin optimization.
*   **Feature Importance:** Vehicle's year, condition, model, and mileage were the strongest attributes on predicting value.
*   **Business Insight:** Analysis revealed that 35% of the vehicles were sold 10% above/below MMR, presenting an opportunity for a predictive model in order to optimize selling prices.
*   **Recommendation:** To increase the model's accuracy and business value, the analysis should be repeated with data from the last five years. This would provide a more relevant baseline for implementing a dynamic pricing strategy that accounts for long-term trends and seasonal fluctuations, ultimately maximizing revenue potential.

