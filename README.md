Newspaper Subscriber Trend Prediction Analysis

This project analyzes historical subscription data to identify patterns and predict future newspaper subscriber trends. Using time series forecasting and regression models, it helps media companies understand reader behavior and make informed decisions about content planning, marketing, and resource allocation.

Objective
	•	Analyze subscriber trends over time using historical data
	•	Forecast future subscription levels using time series models
	•	Identify key features that influence subscriber retention and drop-off
	•	Support data-driven decisions for optimizing audience engagement

Dataset Overview
	•	Source: Public or internal subscription datasets
	•	Features:
	•	Subscription Date
	•	Subscription Type (digital, print, bundled)
	•	User Demographics (age, location, income)
	•	Reading Frequency / Engagement Metrics
	•	Cancellation Date / Churn Labels (if available)

Project Workflow

Data Preprocessing:
	•	Cleaned and filtered date-based subscriber data
	•	Created derived features like active days, retention rate, and plan duration
	•	Handled missing values and outliers in engagement metrics

Modeling:
	•	Applied ARIMA and Prophet models for time-based forecasting
	•	Used Linear Regression and Decision Tree Regressor for non-temporal features
	•	Evaluated models with metrics such as MAE, RMSE, and R² score

Visualization:
	•	Trend lines showing subscriber growth or decline
	•	Seasonal decomposition of time series
	•	Feature importance and correlation heatmaps

Results and Insights
	•	Identified strong seasonal patterns in subscription behavior
	•	Found that digital plans had more churn resilience compared to print
	•	Forecasted next-quarter subscription volume with high confidence using Prophet
	•	Revealed engagement frequency and plan type as key predictors of retention

Tools and Technologies
	•	Programming Language: Python
	•	Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, statsmodels, fbprophet
	•	Techniques: Time Series Forecasting, Regression Analysis, Feature Engineering, Exploratory Data Analysis

Future Improvements
	•	Add real-time dashboard using Streamlit for live forecasting
	•	Integrate external signals (news events, promotions) to improve predictions
	•	Apply classification models to detect high-risk churn users


