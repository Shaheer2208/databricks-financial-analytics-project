# databricks-financial-analytics-project

# Financial Transaction Analytics Platform 
Built using Medallion Architecture (Bronze → Silver → Gold) to transform raw financial transactions into business-ready analytical insights.

End-to-End Data Engineering & Analytics Project using Databricks, Delta Lake, SQL, DAX and Power BI.

## Overview 
This project builds a financial transaction analytics solution using a layered data architecture.

The solution: 
* Ingests raw transaction data
* Transforms and cleans data
* Creates business-ready tables
* Builds analytical dashboards

--- 
## Architecture 
<img width="1031" alt="Architecture" src="https://github.com/user-attachments/assets/0236e9f0-2bad-42bc-aa9b-9253e970eb4d" />

---
## Tech Stack 
* Databricks
* Delta Lake
* SQL
* Power BI
* DAX
* Data Modeling

--- 
## Dashboard Pages

### Executive Overview
<img width="1367" alt="Executive Overview" src="https://github.com/user-attachments/assets/40c8e875-5ab2-40d5-bdbc-b63348134bf2" />

KPIs and business summary.

--- 
### Fraud Analysis
<img width="1367" alt="Fraud Analysis" src="https://github.com/user-attachments/assets/7db6deb4-3018-491c-8bed-1685b625b967" />

Fraud trends and transaction monitoring.

--- 
### Customer Insights

<img width="1282" alt="Customer Insights" src="https://github.com/user-attachments/assets/c74705e8-62c8-4bef-bd07-5859ff76a0cc" />

Customer segmentation and behavior.

---
### Transaction Analysis & Trends

<img width="1192" alt="Transaction Analysis and Trends" src="https://github.com/user-attachments/assets/811d3e5b-426f-4f89-a6fc-39728966c76a" />

Transaction trend analysis and operational performance monitoring.
--- 
## Key KPIs

* Total Amount
* Total Transactions
* Fraud Amount
* Fraud Rate %
* Active Customers

---
## Key Insights
1. Total transaction volume exceeded 1T, indicating large-scale financial activity.
2. Fraud transactions represented only a small percentage of total transactions while contributing significant financial impact.
3. Fraud activity was concentrated mainly in CASH_OUT and TRANSFER transaction types.
4. Customer spending distribution showed a small group of customers contributed most transaction value.
5. Transaction activity peaked during specific hours of the day.
6. High-value transactions formed a major portion of total transaction amount.
7. Transaction patterns varied across transaction types.
8. Customer segmentation highlighted concentration across selected value bands.

--- 
## Business Impact
* Delivered centralized monitoring for financial transactions.
* Improved fraud visibility through transaction analytics.
* Enabled customer segmentation and behavioral analysis.
* Reduced manual reporting effort through interactive dashboards.
* Supported operational decision-making using trend analysis.

---
## Future Improvements
* Implement incremental loading
* Add real-time streaming pipeline
* Deploy Power BI Service reporting
* Add anomaly detection

---
## Project Structure
architecture/
notebook/
powerbi/
screenshots/
docs/
README.md

---
## Data Engineering Workflow 
1. Ingest raw transaction dataset using PySpark
2. Apply cleansing and transformation logic
3. Store processed data into Bronze layer
4. Create Silver layer for business rules
5. Build Gold layer for reporting
6. Connect Power BI for visualization

--- 
## Notebooks

| Notebook | Purpose |
|----------|---------|
| 01_data_ingestion | Load raw transaction data |
| 02_data_cleaning | Handle nulls and transformations |
| 03_data_transformation | Build business logic |
| 04_gold_layer_creation | Prepare reporting layer |

--- 
## Dashboard Report
View Dashboard PDF
(Financial_Transaction_Analytics.pdf)



