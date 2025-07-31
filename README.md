# Vendor Performance Analysis - Data Analytics Case Study

Welcome to my Data Analytics Case Study focused on **Vendor Performance Analysis**! This project demonstrates a real-world use case where we analyze vendor data to assess their performance, identify patterns, and provide actionable insights. The entire project spans from data ingestion, cleaning, exploratory data analysis (EDA), hypothesis testing, and visualization in Power BI.


## Project Overview

In this project, I follow a comprehensive data analytics workflow that is applicable in real-world scenarios, utilizing tools such as SQL, Python, and Power BI to analyze vendor performance data. Here's a quick rundown of the process:

1. **Understanding the Business Problem** – We begin by defining the project scope and determining the business questions that need to be answered.
2. **Data Ingestion & Cleaning** – SQL is used to ingest data and clean it for analysis, ensuring accuracy and consistency.
3. **Exploratory Data Analysis (EDA)** – Python libraries such as Pandas, Matplotlib, and Seaborn are employed for data visualization and statistical analysis.
4. **Hypothesis Testing & Confidence Interval** – Statistical testing is performed to validate our assumptions and provide confidence in the analysis results.
5. **Power BI Dashboard** – A dynamic Power BI dashboard is built to visualize the data insights and track vendor performance in real-time.
6. **Report Writing** – A final report is generated summarizing the analysis and presenting actionable insights to stakeholders.

## Datasets Used

### 1. **`vendor_invoice.csv`**
   - Contains detailed records of vendor invoices, including invoice numbers, dates, amounts, and vendor IDs.
   - **Usage**: This data was used to analyze the financial transactions with vendors, assessing whether vendors meet agreed-upon terms such as pricing and delivery schedules.

### 2. **`sales.csv`**
   - Contains sales data including sales transactions, dates, quantities sold, and sales prices.
   - **Usage**: Sales performance is one of the key metrics to evaluate vendor success. This data was analyzed to measure each vendor’s contribution to the overall sales performance.

### 3. **`purchases.csv`**
   - Tracks purchase transactions, including item IDs, quantities purchased, dates, and associated vendor information.
   - **Usage**: The data from `purchases.csv` was used to evaluate the efficiency of vendors in fulfilling orders and the volume of purchases made from each vendor.

### 4. **`purchase_prices.csv`**
   - Contains information about the price of products from different vendors.
   - **Usage**: This data was used to assess the cost-effectiveness of each vendor and compare the prices for similar products across vendors.

### 5. **`end_inventory.csv`**
   - Includes information on the stock levels at the end of a given period.
   - **Usage**: This data is useful for understanding how vendor performance affects inventory levels and sales forecasts.

### 6. **`begin_inventory.csv`**
   - Contains information on the stock levels at the beginning of a given period.
   - **Usage**: Used in conjunction with `end_inventory.csv` to track inventory changes and assess vendor performance in maintaining stock levels.

---

## Tools and Technologies Used

- **SQL**: For data ingestion, querying, and cleaning.
- **Python**:
  - **Pandas**: For data manipulation and cleaning.
  - **Matplotlib/Seaborn**: For data visualization and creating insightful charts.
  - **SciPy**: For hypothesis testing and statistical analysis.
- **Power BI**: For creating an interactive dashboard that tracks vendor performance in real-time.
- **SQLite**: Used for storing the vendor data in the `inventory.db` file.
- **Jupyter Notebooks**: For documenting the entire process, including EDA and insights generation.

---

## Data Description

The datasets used in this project are detailed below. Each dataset contributes specific insights into evaluating vendor performance:

- **`vendor_invoice.csv`**: Contains invoice data with key metrics like invoice amount, dates, and vendor IDs.
- **`sales.csv`**: Holds information on sales transactions, allowing for sales analysis and vendor contribution evaluation.
- **`purchases.csv`**: Provides purchase transaction data, which is used to evaluate vendor fulfillment and purchasing trends.
- **`purchase_prices.csv`**: Tracks price information from vendors, helping us assess cost efficiency.
- **`end_inventory.csv`** and **`begin_inventory.csv`**: Inventory data used to measure how vendor performance affects stock levels and how accurately vendors forecast their supply.

---

## Steps & Process

### 1. **Understanding the Business Problem**
We begin by outlining the core business question: How can we assess and improve vendor performance based on key metrics?

### 2. **Data Ingestion & Cleaning**
- **SQL** is used to pull data from the `inventory.db` SQLite database.
- We clean the data by handling missing values, removing duplicates, and ensuring data consistency.

### 3. **Exploratory Data Analysis (EDA)**
- Using **Python (Pandas, Matplotlib, Seaborn)**, we perform data visualization to spot trends, correlations, and outliers.
- We generate histograms, bar charts, scatter plots, and heatmaps to make the data more understandable.

### 4. **Hypothesis Testing & Confidence Interval**
- To validate assumptions, we perform hypothesis testing (e.g., T-tests) and calculate confidence intervals to ensure the findings are statistically significant.

### 5. **Power BI Dashboard**
- After analyzing the data, we create an interactive Power BI dashboard that visualizes the most important vendor performance metrics. This includes KPIs such as on-time delivery, customer satisfaction, and sales performance.

### 6. **Report Writing**
- A comprehensive report is generated that summarizes all findings, visualizations, and recommendations for improving vendor performance. This report is intended for business stakeholders to make informed decisions.

---

## How to Run

### Prerequisites
- Python 3.x
- Required Python Libraries: `pandas`, `matplotlib`, `seaborn`, `scipy`, `sqlite3`, `pyodbc`
- Power BI Desktop (for visualizing the dashboard)

## Future Improvements
- **Expand Data Sources**: Integrate additional data sources to get a more holistic view of vendor performance.

- **Automated Reporting**: Automate the generation of reports using Python or Power BI services.

- **Advanced Predictive Analytics**: Implement machine learning models to predict future vendor performance.

## Conclusion
This project showcases a work through a full data analytics lifecycle — from data ingestion, cleaning, and analysis to creating interactive dashboards and generating insightful reports. I used industry-standard tools such as SQL, Python, and Power BI, ensuring a solid understanding of data analytics in real-world scenarios.

Feel free to explore the project, try the code, and get in touch for any questions or feedback!

## Contact
- LinkedIn
- Email: ibrah23g@mtholyoke.edu
- GitHub
