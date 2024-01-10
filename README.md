# Machine-Learning
This repo contains three main projects completed in the course Machine Learning during graduate school: Stock Analysis, Anomaly Detection.

## Stock Analysis
The stock analysis project involves implementing two distinct trading strategies in Python, based on Machine Learning Classification modeling approaches. The strategies generate 'buy' or 'sell' signals for a given security based on feature variables. Strategy 1 has a signal 'Buy' if the next trading day's close price is greater than today's close price, otherwise 'Sell'. Strategy 2 has a signal utilize the golden cross (50-day MA crossing above 200-day MA) as a bullish (buying) signal. 
#### Machine Learning Models
*K-Nearest Neighbors (KNN)
*Random Forest (RF)
*Gradient Boosting (GB)
*Support Vector Machines (SVMs)
*XGBoost (XGB)

## Anomaly Detection
The anomaly detection project focuses on detecting anomalies in a dataset containing device temperatures over time. Unsupervised Learning models are employed for this task. Feature engineering is performed to create a new feature, 'dtcat' (date-time-category), indicating the day of the week and time of the day. K-means algorithm is applied to determine the best value for k.
#### Outlier Detection
*Use the 1.5 x IQR rule to identify outliers.
*Apply the Gaussian distribution (EllipticEnvelope) algorithm to detect anomalies.
*Apply the Isolation Forest algorithm for anomaly detection.

## Heart Failure Survival
This project involves classification tasks on a dataset containing medical records of patients who had heart failure. Various machine learning models are employed, and interpretability tasks are performed.
#### Machine Learning Models
*Logistic Regression (LR)
*Decision Tree (DT)
*Random Forest (RF)
*XGBoost (XGB)
#### Interpretation/Explanation
*Use the 'eli5' library to interpret the "white box" models of Logistic Regression and Decision Tree.
*Use LIME to explain Random Forest and XGBoost models.
*Use SHAP library to interpret the XGBoost model with TreeExplainer.
*Visualize explanations using the 'force_plot' function and create feature importance plots.
