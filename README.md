# Banking Customer Analytics

## Overview

Banking Customer Analytics is an end-to-end data analytics project that analyzes customer demographics, banking relationships, deposits, loans, credit card balances, profitability, and risk metrics. The project leverages Python for data processing and analysis, SQL for querying and extracting business insights, and Power BI for interactive data visualization.

The objective is to transform raw banking data into meaningful insights that support data-driven decision-making, customer segmentation, and business growth strategies.

---

## Dataset

The dataset contains banking customer records with information related to:

* Customer Demographics (Age, Gender, Nationality)
* Banking Relationships
* Deposits and Account Balances
* Loans and Business Lending
* Credit Card Balances
* Customer Profitability
* Risk Weighting
* Product Ownership
* Income and Financial Metrics

**Dataset Size**

* Records: 3,001
* Features: 25

---

## Tools & Technologies

### Programming & Analysis

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

### Database

* MySQL / SQL Server
* SQLAlchemy

### Data Visualization

* Power BI

### Reporting & Presentation

* Microsoft PowerPoint
* Gamma

---

## Project Steps

### 1. Data Loading

* Imported the dataset using Pandas.
* Inspected data structure, dimensions, and data types.

### 2. Data Cleaning

* Checked and handled missing values.
* Standardized column names.
* Improved data consistency and quality.

### 3. Exploratory Data Analysis (EDA)

* Performed univariate, bivariate, and multivariate analysis.
* Analyzed customer demographics and financial behavior.
* Explored deposits, loans, credit card balances, and profitability metrics.
* Generated visualizations and statistical summaries.

### 4. Feature Engineering

* Created income-based customer segments.
* Derived additional analytical features for customer analysis.
* Enhanced data for business intelligence reporting.

### 5. SQL Analysis

Executed SQL queries to generate business insights, including:

* Total Clients
* Total Deposits
* Total Loans
* Credit Card Amount
* Savings Account Amount
* Loan by Income Band
* Loan by Nationality
* Deposit by Income Band
* Deposit by Nationality
* Loyalty Classification Analysis
* Customer Segmentation Analysis

### 6. Dashboard Development

Built an interactive Power BI dashboard to visualize key performance indicators and customer insights.

### 7. Reporting & Presentation

* Created a comprehensive analytics report summarizing findings and recommendations.
* Developed a professional presentation using Gamma to communicate business insights.

---

## Dashboard

The Power BI dashboard consists of the following pages:

### Home Page
<img width="1117" height="630" alt="Screenshot 2026-08-01 104454" src="https://github.com/user-attachments/assets/3516d13c-54b0-4516-b516-c1c93461af2f" />

* Overview of key banking metrics and KPIs.

### Loan Analysis
<img width="1113" height="620" alt="Screenshot 2026-08-01 104733" src="https://github.com/user-attachments/assets/41eb9262-0b99-44e1-843d-d6a34d6ce6e2" />

* Analysis of loan distribution across customer segments.

### Deposit Analysis
<img width="1116" height="635" alt="Screenshot 2026-08-01 105020" src="https://github.com/user-attachments/assets/bc374bbc-3759-487e-bf65-f617c7b79c8f" />

* Insights into deposits, savings accounts, and customer balances.

### Summary Page
<img width="1111" height="621" alt="Screenshot 2026-08-01 105234" src="https://github.com/user-attachments/assets/a8a40f70-2afc-4392-9b0d-a92c953f47ae" />

* Consolidated view of overall banking performance.

### Drill-Through Page
<img width="1111" height="626" alt="Screenshot 2026-08-01 105552" src="https://github.com/user-attachments/assets/ca1b41b5-0985-4026-aa68-34cfca2350ec" />

* Detailed customer-level analysis for deeper business insights.

---

## Results

Key outcomes of the project include:

* Identified customer segments based on income and banking relationships.
* Analyzed deposit and loan distribution patterns.
* Evaluated customer profitability and risk exposure.
* Examined customer loyalty classifications and engagement trends.
* Generated actionable business recommendations to support growth and retention strategies.
* Delivered interactive dashboards for efficient decision-making.

---

## Project Structure

```text
Banking_Customer_Analytics/
│
├── Dataset/
│   └── Banking.csv
│
├── Python/
│   ├── data_loading.py
│   ├── data_cleaning.py
│   ├── eda.py
│   └── feature_engineering.py
│
├── SQL/
│   ├── database_creation.sql
│   └── analysis_queries.sql
│
├── PowerBI/
│   └── Banking_Customer_Analytics.pbix
│
├── Reports/
│   └── Banking_Customer_Analytics_Report.pdf
│
├── Presentation/
│   └── Banking_Customer_Analytics_Presentation.pptx
│
├── Images/
│   └── Dashboard_Screenshots/
│
└── README.md
```

---

## How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Banking_Customer_Analytics.git
cd Banking_Customer_Analytics
```

### 2. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy pymysql
```

### 3. Run Python Analysis

```bash
python analysis.py
```

### 4. Execute SQL Queries

* Import the dataset into MySQL or SQL Server.
* Run the SQL scripts available in the `SQL` folder.

### 5. Open Power BI Dashboard

* Open the `.pbix` file in Power BI Desktop.
* Refresh the data connection.
* Explore the interactive dashboard.

---

## Conclusion

This project demonstrates a complete data analytics workflow, from data preparation and exploratory analysis to SQL-based business analysis, dashboard development, reporting, and presentation. It showcases practical skills in Python, SQL, and Power BI while delivering valuable insights into customer behavior and banking performance.

