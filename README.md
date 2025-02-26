# Customer and Credit Card Transaction Analysis

## Overview
This project analyzes **customer and credit card transaction data** to gain insights into customer behavior, spending patterns, and credit card performance. The goal is to help businesses **improve customer satisfaction, increase credit card usage, and optimize marketing strategies**.

The project includes:
- **Datasets** with customer demographics and transaction data.
- **SQL queries** to extract and analyze key insights.
- **Visual dashboards** for a clear understanding of customer activity.

---

## 📂 Files in the Repository

### **1. Data Files (CSV)**
#### **customer.csv** (Customer Demographics)
| Column | Description |
|--------|-------------|
| Client_Num | Unique identifier for each customer |
| Customer_Age | Age of the customer |
| Gender | Gender (Male/Female) |
| Dependent_Count | Number of dependents |
| Education_Level | Customer's education level |
| Marital_Status | Marital status |
| state_cd | Customer's state code |
| Zipcode | Residential zipcode |
| Car_Owner | Owns a car (Yes/No) |
| House_Owner | Owns a house (Yes/No) |
| Personal_loan | Has a personal loan (Yes/No) |
| contact | Preferred contact method |
| Customer_Job | Customer's occupation |
| Income | Annual income |
| Cust_Satisfaction_Score | Customer satisfaction score |

#### **creditcard.csv** (Credit Card Transactions)
| Column | Description |
|--------|-------------|
| Client_Num | Unique identifier (links to customer.csv) |
| Card_Category | Type of credit card (e.g., Platinum, Gold) |
| Annual_Fees | Annual fee of the card |
| Activation_30_Days | Activated within 30 days (Yes/No) |
| Customer_Acq_Cost | Cost to acquire the customer |
| Week_Start_Date | Start date of transaction week |
| Week_Num | Week number in the year |
| Qtr | Quarter of the transaction (1-4) |
| current_year | Transaction year |
| Credit_Limit | Credit limit assigned to the customer |
| Total_Revolving_Bal | Total revolving balance (outstanding debt) |
| Total_Trans_Amt | Total transaction amount |
| Total_Trans_Vol | Total number of transactions |
| Avg_Utilization_Ratio | Credit balance to limit ratio |
| Use Chip | Used chip functionality (Yes/No) |
| Exp Type | Expense type (Personal, Business) |
| Interest_Earned | Interest earned from the customer |
| Delinquent_Acc | Number of delinquent accounts |

#### **Additional Data Files**
- **cc_add.csv**: Additional credit card details (limits, types, etc.).
- **cust_add.csv**: Customer address details for geographic analysis.

### **2. SQL Queries**
- **sql_q.sql**: Contains SQL queries for analyzing customer behavior and spending patterns. The queries:
  - Join customer and credit card datasets.
  - Calculate total transactions, usage ratios, and satisfaction scores.
  - Identify high-value customers and delinquent accounts.

### **3. Visual Dashboards (PDF)**
- **credit_card_report_dashboard1.pdf**: Visual summary of credit card usage and transaction patterns.
- **customer_credit_card_report_dashboard2.pdf**: Insights into customer demographics and credit card behavior.

---

## 🚀 How to Use This Project
### **1. Data Analysis**
- Load the CSV files into a tool like **Python (Pandas), Excel, or SQL**.
- Explore customer demographics and spending patterns.

### **2. SQL Queries**
- Use `sql_q.sql` to analyze customer transactions and behavior.
- Execute queries in **MySQL, PostgreSQL, or any SQL database**.

### **3. Visual Insights**
- Review the PDF dashboards for a quick summary of key findings.
- Use **Power BI or Tableau** for further data visualization.

---

## 🎯 Project Goals
✅ **Understand Customer Behavior**: Segment customers based on spending habits and demographics.  
✅ **Optimize Marketing Strategies**: Identify high-value customers and create targeted campaigns.  
✅ **Reduce Financial Risk**: Detect delinquent accounts and assess credit card usage risks.  
✅ **Improve Customer Retention**: Use transaction data to enhance customer loyalty programs.  

---

## 🛠️ Tools Used
- **SQL**: Data querying and analysis.
- **Python (Pandas, Matplotlib, Seaborn)**: Data manipulation and visualization.
- **Excel**: Basic data exploration.
- **Tableau / Power BI**: Interactive dashboards and visual reports.

---

## 🔮 Future Enhancements
🔹 **Predictive Analytics**: Forecast customer behavior and credit card usage.  
🔹 **Real-time Dashboards**: Monitor customer activity dynamically.  
🔹 **External Data Integration**: Include economic trends for better insights.  

---

## 📩 Contact & Contributions
- Feel free to **contribute** by improving queries, adding visualizations, or suggesting new insights.
- **Issues & Feedback**: Report any issues or suggest improvements via GitHub Issues.

🔗 **Stay Connected & Keep Exploring!** 🚀

