# Inventory Demand Prediction

## Executive Summary

I demonstrate an inventory demand forecasting solution using advanced machine learning techniques in Python. The solution helps track demand trends over time, optimize inventory levels, and provide actionable insights for upper management. By incorporating interactive visualizations, thus enhancing the inventory management system, enabling better data-driven decisions.

The analysis identified key demand patterns over a 62-day period. Accurate forecasting enables management to:

1. Maintain optimal inventory levels.

2. Minimize stock outs and overstock scenarios.

3. Improve operational efficiency and reduce costs.

### Key Recommendations to the product team:

1. Use the SARIMA-based forecasting model for future demand prediction.

2. Integrate interactive visualizations for real-time monitoring.

3. Optimize inventory replenishment cycles based on forecast results.

### Business Problem

Inventory mismanagement, such as stockouts or overstocking, has lead to significant financial losses and inefficiencies. The goal of this project was to analyze historical demand data, identify trends, and build an accurate forecasting model to optimize inventory levels.

By addressing demand variability and providing reliable predictions, this solution ensures that businesses can maintain the right inventory at the right time.

### Methodology

1. Data Preprocessing: 

   a. Removed unnecessary columns and formatted the date column.
  
   b. Aggregated demand data to create a clean time series.

2. Exploratory Data Analysis (EDA):
 
   a. Visualized demand trends over time.
  
   b. Analyzed seasonality, autocorrelation (ACF), and partial autocorrelation (PACF) to   
   determine SARIMA parameters.

![image](https://github.com/user-attachments/assets/2a396c18-3f44-45a9-b7a6-e33a7be972f6)

![image](https://github.com/user-attachments/assets/3acfa93b-c1c0-41fd-9974-b819f54c590c)

3. Model Selection & Training:
     
     a. Used the SARIMA model (Seasonal ARIMA) for forecasting demand.
   
     b. Validated the model to ensure accuracy using time series metrics.

4. Interactive Visualizations:
   
     a. Built hover-capable graphs and trend lines for detailed insights.
   
     b. Created user-friendly visualizations for upper management to monitor inventory trends.

### Skills:

Python: pandas, numpy, statsmodels, matplotlib, plotly

Machine Learning: Time series forecasting using SARIMA

Visualization: Plotly Express, Matplotlib

Statistical Analysis: ACF, PACF for model parameter estimation

### Results & Business Recommendation

#### Results:

1. Accurate Forecasting:
   
   a. SARIMA model successfully forecasted demand trends for a specific product over 62     days.

   b. Model performance was validated through error metrics, ensuring reliability.

2. Insights from Visualizations:

   a. The interactive plots provided a clear understanding of demand patterns.

   b. Management can now identify peak demand periods and adjust inventory accordingly.

3. Improved Decision-Making:

   a. Forecasting enabled precise inventory optimization, reducing both overstocking and  
      stockouts.

### Business Recommendations:

1. Adopt the SARIMA Model for future demand forecasting.

2. Enhance Inventory Systems with interactive dashboards for real-time monitoring.

3. Implement Automated Alerts for inventory thresholds based on forecasted demand.

4. Integrate this system for each product section in the ERP's Inventory System

### Next Steps

1. Fine-tune the SARIMA model with additional seasonal data.

2. Integrate real-time data feeds for dynamic demand forecasting in current Inventory Management module of ERP.

