# HCP_Data-Hackathon

• Kharagpur Data Analytics Group Hackathon: Maximising Brand Rx:
• Pre-processed the HCP data (Health Care Practitioners) by label encoding the categorical feature, normalization etc
• Applying Binary-encoding to the physicians and built a Random Forest Regressor Model given features by maximizing
the Brand Rx (brand prescriptions) and scaling the Market Rx.
• Predicted the Best Promotional channel according to the given promotional constraints; keeping an eye on the correlation
factor of each feature with the Brand Rx for every physician ID.
• Model’s accuracy was compared against xgBoost Regressor model; hyperparameters were tuned using the
GridSearchCV.
• Furthermore, an expected Trx for the physician ID was calculated in the upcoming week by performing a time series analysis
using a supervised machine learning model of Linear Regression under the ARIMA model
