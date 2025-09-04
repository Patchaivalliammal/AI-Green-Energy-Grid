Week 2 – Forecasting Waste and Energy Demand

In Week 2 of the AI-Powered Green Energy Grid project, we extended our work from Week 1 by building simple forecasting models. The goal was to predict future waste generation and energy demand, which are key inputs for planning pollution-to-energy conversion.

🔹 Work Done in Week 2

Loaded the simulated dataset created in Week 1 (simulated_data.csv).

Preprocessed the data and created a time index for modeling.

Trained Linear Regression models to capture basic trends in:

Waste generation (tons/day)

Energy demand (kWh)

Generated 7-day forecasts for both waste and energy demand.

Exported results as:

forecast_df.csv → Table of forecast values.

forecast_plot.png → Visualization of actual vs. predicted trends.

📊 Results

The forecasted values help estimate how much waste and energy demand can be expected in the near future.

This prediction can later be used to optimize plant scheduling and reduce pollution waste.

🛠️ Tools & Libraries

Python

Pandas

NumPy

Matplotlib

Scikit-learn (Linear Regression)

📁 Files in This Folder

week2_forecasting.ipynb → Main notebook with code.

forecast_df.csv → Saved forecasted values.

forecast_plot.png → Visualization of forecasts.

