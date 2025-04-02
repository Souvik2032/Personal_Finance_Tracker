# Personal_Finance_Tracker
Personal Finance Tracker outlines the structured approach taken to develop, implement, and deploy the system. This section details the planning, design, technology stack, and machine learning models used for transaction categorization, expense forecasting, and anomaly detection.

Technology Stack
Component	Technology Used	Purpose
Frontend	Streamlit	User interface for data visualization
Backend	Python	Data processing & model execution
Machine Learning	Random Forest, ARIMA, Isolation Forest	Categorization, forecasting, and anomaly detection
Data Handling	Pandas, NumPy	Data manipulation and processing
Visualization	Matplotlib, Seaborn	Graphs and charts for insights

Implementation of Machine Learning Models:-
A. Transaction Categorization - Random Forest
•	The Random Forest algorithm is used to automatically classify transactions based on past spending patterns.
•	It learns from historical financial data and predicts the correct category for new transactions (e.g., classifying a "Zomato" payment as "Food & Dining").
•	Compared to other models like Logistic Regression and Decision Trees, Random Forest provides better accuracy and avoids overfitting.

________________________________________
B. Expense Forecasting - ARIMA (AutoRegressive Integrated Moving Average)
•	ARIMA is used to predict future expenses based on historical transaction trends.
•	It identifies spending patterns and provides users with estimates of their upcoming expenses.
•	Helps users in better budgeting by forecasting how much they might spend in a particular category (e.g., monthly groceries).

________________________________________
C. Anomaly Detection - Isolation Forest
•	The Isolation Forest algorithm detects unusual transactions by learning typical spending behavior and flagging deviations.
•	If a transaction differs significantly from past spending habits, the system raises an alert.
•	Useful for identifying fraudulent transactions or unexpected spikes in spending.

