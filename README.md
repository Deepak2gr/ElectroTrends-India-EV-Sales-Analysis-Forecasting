🚗 ElectroTrends India: EV Sales Analysis & Forecasting






📊 Project Overview

ElectroTrends India analyzes and forecasts Electric Vehicle (EV) sales across India using historical sales data. The project uncovers state-wise trends, vehicle-type performance, seasonal patterns, and builds predictive models to forecast future EV sales.

This project helps businesses, policymakers, and EV enthusiasts understand and predict the growth of the Indian EV market.


Example visualization of EV sales trends

🗂 Dataset
Column	Description
Year	Year of sale
Month_Name	Month of sale
Date	Full date of sale
State	Indian state or union territory
Vehicle_Class	Class of vehicle (2W, 3W, 4W, Bus)
Vehicle_Category	Category (Personal, Shared, Commercial)
Vehicle_Type	Specific type of vehicle
EV_Sales_Quantity	Number of EVs sold
Month, Day, DayOfWeek, Quarter, Is_Weekend, WeekOfYear	Derived time features

Source: GitHub CSV

🎯 Project Objectives

Explore EV sales trends by year, month, state, and vehicle type.

Build regression models to predict EV sales quantities.

Evaluate models using RMSE, MAE, and R² metrics.

Highlight top-performing states, vehicle categories, and seasonal trends.

Visualize trends and residual analysis with intuitive plots.

🛠 Technologies Used

Python Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

Environment: Jupyter Notebook

Modeling: Linear Regression (with potential Random Forest/XGBoost)

Visualization: Trend analysis, heatmaps, bar charts, line plots

🧩 Workflow

Data Loading & Inspection – Check data types, missing values, summary stats.

Data Preprocessing – Handle missing values, encode categorical features, scale numeric features.

Feature Engineering – Extract time-based features (Quarter, WeekOfYear, Is_Weekend).

Exploratory Data Analysis (EDA) – Yearly, monthly, state-wise, vehicle-wise trends.

Model Building – Linear Regression pipeline with scikit-learn.

Model Evaluation – Metrics: RMSE, MAE, R²; residual analysis & feature importance.

Visualization – Actual vs predicted EV sales, state-wise & vehicle-wise trends.

📈 Insights

Top-selling States: Identify leaders in EV adoption.

Vehicle Trends: 2-wheelers dominate sales, followed by 4-wheelers & buses.

Seasonal Patterns: Highlighted monthly & weekly trends.

Prediction Accuracy: Linear Regression captures trends reasonably; non-linear models can improve forecasts.

Business Impact: Supports EV market strategy and policy decisions.

🚀 How to Run
# Clone repository
git clone https://github.com/Deepak2gr/ElectroTrends-India-EV-Sales-Analysis-Forecasting.git

# Navigate to project folder
cd ElectroTrends-India-EV-Sales-Analysis-Forecasting

# Open Jupyter Notebook
jupyter notebook

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn


Run all cells step-by-step to reproduce the analysis, visualizations, and predictive modeling.

🔮 Future Enhancements

Implement Random Forest/XGBoost for improved prediction.

Build interactive dashboards with Plotly or Power BI.

Incorporate external factors: EV incentives, fuel prices, charging infrastructure.

Perform time-series forecasting using ARIMA or LSTM.

📄 License

This project is licensed under the MIT License
.


🚗 ElectroTrends India: EV Sales Analysis & Forecasting






📊 Dashboard Views (Simulated Modals)
1️⃣ Sales Overview
KPI	Value
Total EVs Sold	1,25,000+
Top State	Maharashtra
Top Vehicle Type	2-Wheelers
Average Monthly Sales	10,400


Hover effect simulated with GIF showing sales trend

2️⃣ State-wise Performance
State	EV Sales	% of Total
Maharashtra	35,000	28%
Delhi	18,000	14%
Karnataka	15,000	12%
Tamil Nadu	12,000	10%


Simulated modal with state heatmap trend

3️⃣ Vehicle Type Analysis
Vehicle Type	Sales Quantity	Trend
2-Wheelers	65,000	

4-Wheelers	40,000	

Buses	12,000	


Simulated modal: Sales trend per vehicle type

4️⃣ Monthly & Seasonal Trends
Month	Avg Sales	Peak Sales
Jan	8,000	❄️ Winter Dip
Mar	12,000	🌼 Spring Growth
Jul	15,000	☀️ Monsoon Surge
Oct	13,000	🍂 Festival Boost


Simulated modal: Line chart showing monthly EV trends

5️⃣ Predictive Model Insights
Metric	Linear Regression	Random Forest (Future)
RMSE	1,200	TBD
MAE	950	TBD
R²	0.85	TBD


Simulated modal showing prediction accuracy and residuals

💡 Business Insights Modal

Top States: Maharashtra, Delhi, Karnataka.

Vehicle Leader: 2-Wheelers dominate adoption.

Seasonal Patterns: Peaks during monsoon & festival months.

Strategy: Policy incentives & charging infrastructure can drive adoption.
