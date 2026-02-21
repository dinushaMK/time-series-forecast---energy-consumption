# time-series-forecast---energy-consumption 
Processed 145,000+ hourly energy records using Pandas and engineered time-based features (hour, day of week, month, quarter, year, day of year) to capture seasonal and cyclical patterns
Performed in-depth exploratory data analysis (EDA) with Seaborn & Matplotlib to uncover consumption trends across time
Implemented a time-series cross-validation strategy to prevent data leakage and ensure robust model evaluation
Trained an XGBoost Regressor on temporal features, achieving an RMSE of ~3,735 MW on unseen test data
Visualized predictions vs. ground truth and identified the worst-performing dates to drive further model improvement

Stack: Python · Pandas · NumPy · XGBoost · Scikit-learn · Matplotlib · Seaborn
