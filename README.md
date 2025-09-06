📊 Bank Transaction Fraud Detection & Insights
📌 Project Overview

This project focuses on analyzing bank transaction data to uncover patterns, detect potential fraud, and generate actionable business insights.
The workflow includes:

Data Cleaning & Preprocessing

Exploratory Data Analysis (EDA)

Fraud Detection using Isolation Forest

Interactive Dashboard with Power BI

The project demonstrates the end-to-end process of data analysis — from raw data to business-ready insights.
🔎 From the Python Notebook

Libraries used: pandas, matplotlib, seaborn, scikit-learn (Isolation Forest, StandardScaler).

Dataset: bank_transactions_data_2.csv.

Preprocessing: Converted TransactionDate and PreviousTransactionDate to datetime.

EDA (Exploratory Data Analysis):

Calculated total transactions, unique accounts, merchants, and stats on transaction amounts.

Distribution of TransactionAmount.

Bar chart: Transactions by Channel.

Line chart: Transactions over time.

Fraud Detection:

Features used: TransactionAmount, TransactionDuration, LoginAttempts, AccountBalance.

Applied Isolation Forest (3% contamination rate).

Added Anomaly column → 1 = Fraud, 0 = Normal.

Visualizations of anomalies:

Fraud vs. non-fraud by Channel (stacked bar).

Top 10 Locations with Fraudulent Transactions (horizontal bar).

📊 From the Power BI Dashboard

Based on your earlier messages, the .pbix file includes:

Transactions over Year/Quarter/Month.

Top 10 Locations analysis.

Fraud vs Non-Fraud transactions.

Pie chart (e.g., channel share or fraud percentage).

Heatmap (e.g., billing amounts across locations/periods).

KPIs for total transactions, fraud rate, average billing.

Now I’ll write you a README.md file that matches your exact code + dashboard.

📊 Bank Transaction Fraud Detection & Insights
📌 Project Overview

This project analyzes bank transaction data to detect fraudulent activities and generate actionable insights.
It combines Python (for data analysis & fraud detection) with Power BI (for storytelling dashboards).

🗂️ Files in Repository

Untitled83.ipynb → Python notebook for data cleaning, EDA, anomaly detection, and visualizations.

Bank Transaction Fraud Detection Dashboard.pbix → Power BI dashboard with interactive insights.

README.md → Documentation.

🛠️ Tools & Technologies

Python: pandas, matplotlib, seaborn, scikit-learn

Machine Learning: Isolation Forest (fraud detection)

Data Visualization: Matplotlib, Seaborn, Power BI

Dataset Features: TransactionDate, TransactionAmount, TransactionDuration, LoginAttempts, AccountBalance, Channel, Location, MerchantID, AccountID

🚀 Key Features
🔹 Python Notebook

EDA Summary: Transactions, unique accounts, merchants, avg/min/max transaction amounts.

Transaction Distribution: Histogram of transaction amounts.

Channel Analysis: Transactions count per channel.

Time Series: Transactions trend over time.

Fraud Detection: Isolation Forest identifies anomalies (frauds).

Fraud Insights:

Anomalies by Channel (stacked bar).

Top 10 Fraud Locations (horizontal bar).

🔹 Power BI Dashboard

📅 Trends: Transactions over Year/Quarter/Month.

📍 Top 10 Locations by transaction volume/fraud count.

🔴 Fraud vs Non-Fraud: Distribution of anomalies.

🥧 Pie Chart: Channel share or fraud distribution.

🌡️ Heatmap: Billing amount/transaction density by location.

📊 KPIs: Total Transactions, Fraud Rate, Avg Transaction Amount.

📂 Project Workflow

Data Import → Load CSV into Python.

Data Cleaning → Convert dates, check dataset structure.

EDA → Explore amounts, channels, and trends.

Fraud Detection → Isolation Forest on selected features.

Visualization → Python charts & Power BI dashboard.

📸 Sample Dashboard Preview

(Insert screenshot of Power BI dashboard here)

📈 Future Improvements

Add more advanced fraud models (XGBoost, Neural Networks).

Deploy real-time fraud detection as a web app.

Connect dashboard to live transaction streams.

👤 Author

E ROHITH

B.Tech CSE (Specialization: Data Science)

Skills: Python, SQL, Power BI, Machine Learning, Data Analysis
