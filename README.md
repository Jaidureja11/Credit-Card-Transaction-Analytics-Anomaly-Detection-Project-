# Credit Card Transaction Analytics & Anomaly Detection
Project Overview
This project demonstrates a complete analytics workflow to detect anomalous (potentially fraudulent) credit card transactions and generate actionable business insights. The solution includes data cleaning, exploratory analysis, feature engineering, machine learning–based anomaly detection, and executive-quality dashboard outputs.

Data Cleaning and Preparation

All raw credit card transaction data was standardized and validated. Columns were cleaned and renamed for consistency, missing values were imputed, and key fields such as unique transaction, customer, and merchant IDs were created. This ensures data quality and prepares the dataset for reliable downstream analysis.

Exploratory Data Analysis (EDA)

The project explores transaction patterns using statistical summaries and visualizations. Key insights include:
Typical ranges and outliers in transaction amounts.
Monthly and seasonal changes in transaction volume.
Major contributors by merchant and category.
Customer behavior segmented by demographics and spend category.

Feature Engineering

Business-driven features were engineered to mirror real-world banking analytics, such as:
Average spend and transaction frequency per customer.
Unique customer counts for each merchant.
Flags to detect if a customer is transacting with a merchant for the first time.

Anomaly Detection

An Isolation Forest algorithm was implemented to flag unusual transactions. This model is well suited to financial data because it can efficiently identify outliers without requiring labeled fraud examples. Each flagged transaction is accompanied by an automated, human-readable explanation, helping analysts and decision-makers interpret results.

Business Impact Quantification

The solution quantifies and reports on critical KPIs, such as:
Estimated fraud loss avoided (sum of flagged anomaly amounts).
Anomaly rates by merchant, category, and customer cohort.
Precision of detection, validated with sample manual review.
Validation and Reporting
Sampled anomalies were reviewed with human judgment to verify model effectiveness. The final dataset can be exported for further reporting or loaded directly into Power BI dashboards for interactive, executive-level exploration.

What Makes This Project Unique

Every detected anomaly is translated into plain-language explanations for maximum business transparency.
Risk and financial impact are quantified using live KPIs, not just technical scores.
The workflow mirrors best practices used in banking and fintech: from raw data to actionable and interpretable insight.
The project is structured for easy extension to additional currencies, transaction types, or more advanced analytics.

Screenshot of dashboard : 
<img width="1417" height="792" alt="Screenshot 2025-07-20 160758" src="https://github.com/user-attachments/assets/384593e5-3fc3-4824-8e1f-95e24d9abaa9" />

