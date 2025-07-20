# Credit_Card_Dashboard-Project

# Credit Card Dashboard Project (Power BI + PostgreSQL)

This project consists of two interactive dashboards built using Power BI to visualize and analyze credit card transaction trends and customer insights. The data is managed through a PostgreSQL database, and CSV files are used as the data source.

##  Dashboards Included

1. Credit Card Transaction Report
2. Customer Credit Card Report

Each dashboard provides in-depth business insights based on transactional and demographic data.



##  Technology

- Power BI – Data visualization
- PostgreSQL – Relational database backend
- CSV Data – Uploaded and queried through PostgreSQL
- SQL – For table creation and data management


##  Data Sources

- `credit_card.csv`: Contains transaction-level data like amount, interest, card type, channel (swipe, chip, online), etc.
- `customer_credit_card.csv`: Contains customer-level data like age, income group, marital status, job type, etc.

Both CSVs were imported into PostgreSQL using `COPY` and queried through Power BI.



## Key Insights

###  Dashboard 1: Credit Card Transaction Report
- Highest Revenue by Card Type: Blue Card generates the most revenue ($46M+).
- Top Transaction Channel: Swipe is the most common (63%), followed by Chip (31%).
- Customer Profession: Businessmen and white-collar workers contribute the most to revenue.
- Quarterly Trends: Highest total transaction count observed in Q3.
- Expenditure Category: Bills, entertainment, and fuel are top spending areas.

###  Dashboard 2: Customer Credit Card Report
- Revenue by Income Group: Low-income group surprisingly generates the highest revenue ($10M).
- Top Performing Age Group: 40–60 years old have the highest card usage.
- State-wise Revenue: California, Texas, and New York show high usage.
- Gender-based Trends: Males slightly dominate revenue generation.
- Job-wise Revenue: Businessmen are the most profitable segment, followed by white-collar professionals.
- Card Type: Silver card leads in revenue contribution.


