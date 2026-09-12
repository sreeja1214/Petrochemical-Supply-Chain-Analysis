**# Trade, Supply Chain \& Energy Analytics**





**An end-to-end data analytics project analyzing trade, supply chain, and energy datasets to extract meaningful insights and support business decision-making, with a focus on India.**



**## Overview**



**In the modern data-driven economy, organizations rely heavily on data analytics to make strategic decisions. This project integrates multiple domains — trade, logistics, and energy — to provide a comprehensive understanding of economic and operational dynamics. It follows a complete pipeline: data quality assessment, cleaning, exploratory data analysis (EDA), statistical validation, feature engineering, machine learning, SQL-based querying, and dashboard visualization using Power BI.**



**## Objectives**



**- Analyze import-export trends and evaluate trade balance**

**- Identify inefficiencies and risks in supply chain operations**

**- Study energy consumption patterns and renewable energy adoption**

**- Validate insights using statistical methods**

**- Enhance datasets using feature engineering**

**- Build a predictive model using machine learning**

**- Derive business insights using SQL queries**

**- Present findings through interactive dashboards**



**## Data Sources**



**- Supply chain dataset**

**- Petrol**

**- Chemical**

**- Imports**

**- Exports**

**- Logistics dataset**

**- Energy dataset**



**## Pipeline**



**1. \*\*Data Quality Audit \& Preparation\*\* — assessed column meanings, data types, and distributions; identified missing values, duplicates, inconsistent formats, aggregated "Total" rows, and irrelevant columns.**

**2. \*\*Data Cleaning\*\* — removed duplicate/irrelevant rows, dropped aggregated rows, converted year columns to numeric, handled missing values, standardized column names, filtered for India-specific analysis.**

**3. \*\*Data Transformation \& Standardization\*\* — reshaped data via melt/pivot, combined imports and exports into a unified trade dataset, and standardized column names, data types, units, categorical values, and date/year formats across all sources.**

**4. \*\*Exploratory Data Analysis (EDA)\*\* — trade, supply chain, and energy trends and relationships.**

**5. \*\*Statistical Analysis\*\* — descriptive statistics, correlation analysis, and hypothesis testing.**

**6. \*\*Feature Engineering\*\* — created trade, supply chain, and energy features to improve interpretability and predictive power.**

**7. \*\*Machine Learning\*\* — Linear Regression model to predict trade balance.**

**8. \*\*SQL (Business Queries)\*\* — extracted key business insights (top products, profit, category performance, risk, cost, energy trends).**

**9. \*\*Dashboards (Power BI)\*\* — three interactive dashboards: Trade Performance, Supply Chain \& Logistics, and Energy \& Sustainability.**



**## Key Insights**



**- \*\*Persistent trade imbalance\*\* — imports consistently exceed exports, with the deficit widening sharply after 2020.**

**- \*\*Logistics inefficiency\*\* — traffic conditions, especially expressway disruptions, are the leading driver of longer delivery times.**

**- \*\*Slow renewable adoption\*\* — renewable energy share is growing, but fossil fuels still dominate India's energy mix.**



**## Statistical Validation**



**All three hypothesis tests (α = 0.05) were rejected, confirming:**

**- A genuine trade imbalance between imports and exports**

**- A real impact of traffic conditions on delivery/travel time**

**- Real growth in renewable energy share over time**



**## Machine Learning**



**- \*\*Model:\*\* Linear Regression (chosen for simplicity and interpretability)**

**- \*\*Objective:\*\* Predict trade balance**

**- \*\*Process:\*\* Feature selection → train-test split → model training → prediction**

**- \*\*Evaluation metrics:\*\* Mean Absolute Error (MAE), R² Score**

**- \*\*Conclusion:\*\* The model effectively captures the relationship between imports and exports.**



**## Dashboards (Power BI)**



**| Dashboard | KPIs |**

**|---|---|**

**| Trade Performance | Total Exports (48M), Total Imports (107M), Trade Balance (-59M) |**

**| Supply Chain \& Logistics | Avg Supply Risk (34.08), Avg Travel Time (20.78), Avg Operational Cost (₹44.25) |**

**| Energy \& Sustainability | Total Energy Consumption (9.36K), Avg Renewable Share (7.99%), Total Electricity Demand (16.50K) |**



**## Business Recommendations**



**1. Reduce dependency on imports**

**2. Improve logistics efficiency**

**3. Optimize operational costs**

**4. Increase renewable energy investment**

**5. Diversify export markets**



**## Conclusion**



**This project demonstrates a complete data analytics pipeline from data preparation to visualization. It highlights key issues such as trade imbalance, supply chain inefficiencies, and increasing energy demand — grounded in cleaned data, validated statistically, and made actionable through models, SQL, and dashboards.**



**## Future Scope**



**- Use advanced ML models**

**- Include real-time data**

**- Expand to global analysis**

**- Improve predictive accuracy**



**## Project Structure (suggested)**



**```**

**├── data/                  # Raw and cleaned datasets**

**├── notebooks/             # EDA, statistical analysis, feature engineering, ML**

**├── sql/                   # Business query scripts**

**├── dashboards/            # Power BI (.pbix) files**

**├── reports/               # Final report and presentation**

**└── README.md**

**```**



**## Tools \& Technologies**



**- \*\*Data Cleaning \& Analysis:\*\* Python (pandas, numpy)**

**- \*\*Visualization:\*\* matplotlib / seaborn, Power BI**

**- \*\*Statistics:\*\* scipy / statsmodels**

**- \*\*Machine Learning:\*\* scikit-learn (Linear Regression)**

**- \*\*Querying:\*\* SQL**

