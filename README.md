Machine Learning & Data Science Internship Portfolio
This repository showcases my solutions for the 2026 AI/ML Internship. It demonstrates proficiency in data preprocessing, statistical visualization, and building predictive models for finance, healthcare, and real estate.
 Project Summary
Task	Domain	Technique	Key Metric
Task 1	Botany / EDA	Multivariate Analysis	Visual Class Separation
Task 2	Finance	Time-Series Regression	Root Mean Square Error ($RMSE$)
Task 3	Healthcare	Binary Classification	92% Accuracy
Task 6	Real Estate	Multi-variable Regression	Mean Absolute Error ($MAE$)
________________________________________
🛠 Project Deep Dives
Task 1: Iris Feature Exploration
•	Objective: Analyze the relationship between floral measurements and species classification.
•	Insights: Utilized Seaborn pairplots to identify that Petal width and length provide the highest variance for species differentiation.
•	Visuals: Included Histograms for distribution analysis and Box Plots for identifying outliers in sepal measurements.
Task 2: AAPL Stock Price Forecasting
•	Objective: Predict the next day's closing price for Apple Inc. using historical OHLC data.
•	Methodology: Implemented a 1-day lag on the target variable to ensure the model predicts future values based on current market indicators.
•	Results: The model successfully captured major price trends over the 2022-2024 period.
Task 3: Heart Disease Risk Assessment
•	Objective: Develop a diagnostic tool to predict heart disease risk using the UCI repository data.
•	Pipeline: Data cleaning (missing value handling), feature encoding, and Logistic Regression training.
•	Outcome: Achieved a balanced F1-score and an Accuracy of 92%.
•	Evaluation: Validated results using a Confusion Matrix and ROC Curve to minimize false negatives in a medical context.
Task 6: Residential Property Valuation
•	Objective: Estimate house prices using physical attributes like square footage and room count.
•	Evaluation: Focused on Mean Absolute Error (MAE) to understand the average dollar-value deviation in predictions.
•	Visuals: Created an Actual vs. Predicted scatter plot with a regression trendline to assess model variance.
________________________________________
 Technical Stack
•	Languages: Python 3.14
•	Data Analysis: Pandas, NumPy
•	Visualization: Matplotlib, Seaborn
•	Machine Learning: Scikit-Learn (Linear & Logistic Regression)
•	APIs: yfinance for real-time financial data
 Getting Started
1.	Clone the Repo: git clone [repository-link]
2.	Setup Environment: Ensure you have the required libraries installed via pip.
3.	Run Notebooks: Open the .ipynb files in any Jupyter-supported environment to view full code execution and insights.
