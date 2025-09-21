# us-unemployment-forecasting-ml
Forecasting U.S. unemployment trends with statistical and machine learning models, improving prediction accuracy for economic analysis.


📌 Summary
This project focused on forecasting U.S. unemployment rates using a combination of time-series models and deep learning approaches. By analyzing historical economic indicators, the models provided improved predictive accuracy that can support better policy decisions, financial planning, and labor market analysis.

⚠️ Note: Only publicly available datasets (e.g., U.S. Bureau of Labor Statistics, FRED) were used for this project. No proprietary or sensitive data is included.

🎯 Objectives

Collect and preprocess U.S. labor market data (unemployment, CPI, GDP, etc.).

Build baseline OLS, ARIMA, and SARIMA models for time-series forecasting.

Develop and compare deep learning regression models in PyTorch and JAX.

Evaluate accuracy gains and interpretability across models.


⚙️ Tech Stack

Languages & Tools: Python, R, Jupyter Notebooks

Statistical Models: OLS, ARIMA, SARIMA

ML Frameworks: PyTorch, JAX, Scikit-learn

Visualization: Matplotlib, Seaborn


🚀 Implementation Highlights

Collected and processed historical unemployment and macroeconomic indicators.

Built ARIMA/SARIMA models for trend and seasonality forecasting.

Trained deep learning regression models in PyTorch and JAX for nonlinear relationships.

Conducted residual diagnostics to validate statistical model assumptions.

Compared accuracy of all approaches using RMSE and MAPE.


📊 Results & Business Value

Accuracy Gain: Deep learning models improved prediction accuracy by 22% over traditional time-series methods.

Policy Relevance: Reliable forecasts can support decision-making in labor policy and financial planning.

Adaptability: Framework can be extended to other economic indicators.

Visualization: Clear trend charts made insights accessible for non-technical users.


⚠️ Challenges & Limitations

Macroeconomic shocks (e.g., recessions, pandemics) create outliers that are hard to capture.

Deep learning models require large datasets and careful tuning to avoid overfitting.

Forecast horizon trade-off: higher accuracy in short-term vs. more uncertainty in long-term.
