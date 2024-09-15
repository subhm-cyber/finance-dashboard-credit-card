# Credit Card Financial Dashboard

This project involves the development of a **comprehensive credit card weekly financial dashboard** that provides **real-time insights** into key performance metrics and trends. The dashboard enables stakeholders to monitor and analyze credit card operations, ensuring informed decision-making through data-driven insights.

---

## Project Objective
To design a credit card performance dashboard that tracks metrics such as **revenue growth**, **transaction volume**, and **customer behavior trends**. The dashboard visualizes crucial information, empowering businesses to optimize their operations and boost efficiency.

---

## Data Overview

- Source: The dataset used in this project was sourced from "Kaggle". It includes detailed credit card transaction data, customer demographics, and other financial metrics.
- Storage: Data has been stored and managed using an "SQL Database" for efficient querying and retrieval.
- Visualization: The data has been visualized using "Power BI", a leading business intelligence tool, to create dynamic and interactive dashboards.

---

# Key Insights

- Week 53 (31st Dec) Week-over-Week (WoW) Change:
  - Revenue Growth: Increased by "28.8%"
  - Total Transaction Amount & Count: Increased by "XX%" & "XX%"
  - Customer Count: Increased by "XX%"

- Year-to-Date (YTD) Overview:
  - Total Revenue: "57M"
  - Total Interest: "8M"
  - Total Transactions: "46M"
  - Male vs Female Contributions: Males contributed "31M", Females contributed "26M"

- Additional Insights:
  - Top Performing Cards: Blue & Silver credit cards contribute to "93%" of overall transactions
  - Top Contributing States: "TX", "NY", and "CA" contribute to "68%" of total transactions
  - Activation Rate: "57.5%"
  - Overall Delinquency Rate: "6.06%"

---

# Features of the Dashboard

- Interactive Charts: Dynamic visualizations that allow users to drill down into the data by different customer demographics, card types, and locations.
- Key Metrics: Displays revenue, transaction volume, and delinquency rates at a glance, with the ability to filter by week, month, or year.
- Custom Reports: Includes transaction and customer reports in PDF format for easy sharing and analysis.
  
---

# Tools & Technologies

- SQL: For database management and efficient data querying.
- Power BI: Used for data visualization and dashboard creation, enabling real-time interaction with the dataset.
- Python: For preprocessing and analyzing data.
- Kaggle: Data source for credit card-related financial records.

---

# File Structure

```bash
.
├── data
│   ├── cc_add.csv                    # Credit card additional information
│   ├── credit_card.csv                # Main dataset
│   ├── cust_add.csv                   # Customer additional data
│   ├── customer.csv                   # Customer information
├── reports
│   ├── credit_card_report.pbit        # Power BI report template
│   ├── credit_card_customer_report.pdf # Customer report
│   ├── credit_card_transaction_report.pdf # Transaction report
├── SQL
│   └── Financial Dashboard Data.sql   # SQL queries for data processing
├── README.md                          # Project documentation
```

---

# Installation

1. Clone the repository:

    ```bash
   git clone https://github.com/Harshit-Kandoi/Credit-Card-Financial-Dashboard.git
   cd Credit-Card-Financial-Dashboard
   ```

3. Set up a virtual environment (optional):

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

4. Install dependencies:
   The project uses **SQL** and **Power BI**. Ensure you have SQL server and Power BI installed locally.

5. Run the SQL Queries:
   Execute the SQL queries from the `SQL/Financial Dashboard Data.sql` file to set up the necessary database tables and populate the data.

# How to Use

1. SQL Database Setup: 
   Run the SQL script to set up the database and populate the data tables from the CSV files.
   
2. Power BI Dashboard: 
   Import the `credit_card_report.pbit` template into Power BI to explore the interactive dashboard.
   
3. Generate Reports:
   Utilize the Power BI interface to generate custom reports based on the visualized data.
   
# Conclusion

This project provides a detailed analysis of credit card performance over time, allowing businesses to track financial trends, customer demographics, and key operational metrics in real-time. By leveraging **Power BI** for visualization and **SQL** for data management, this dashboard offers a powerful tool for financial analysts and business managers.
