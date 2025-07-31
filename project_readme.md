# 📦 Vendor Performance & Inventory Analytics

**Comprehensive analysis of vendor performance, inventory efficiency, and purchasing behavior using Python, SQL, and Power BI**

---

## 🔍 Overview

This project delivers a **data-driven vendor performance analysis** built on top of a SQLite database. Through **exploratory data analysis (EDA)**, interactive **Power BI dashboards**, and step-by-step Python visualizations, it uncovers key insights in purchasing trends, profitability, and inventory health — enabling smarter procurement and supply chain decisions.

The project includes:

- 📊 Step-by-step **EDA with visual storytelling**
- 🧮 Key metric calculations (sales, gross profit, contribution %, unsold capital)
- 📈 **Pareto analysis** and vendor segmentation
- 📌 Integration with **Power BI** (coming soon)
- 💡 Real-world business insights from raw transactional data

---

## 🧱 Project Structure

my_vendor/
├── data/ # Raw or intermediate data files
├── logs/ # Logs for data processing and ingestion
├── inventory.db # Source SQLite database
├── ingestion_db.py # Script to connect and ingest data from SQLite
├── get_vendor_summary.py # Script to compute vendor KPIs
├── exploratory_data_analysis.ipynb # Notebook: EDA with visualizations
├── my_vendor.ipynb # Notebook: End-to-end analysis
├── vendor_performance_analysis.ipynb # Notebook: KPI metrics & charts
├── README.md # Project documentation


---

## 📌 Business Context

In supply chain and procurement-driven organizations, **tracking vendor performance and managing inventory risk** is crucial. This project simulates a real-world scenario in which:

- Historical purchase and sales data is stored in a relational database
- Business users need insights on:
  - Who are the top vendors by value?
  - What percentage of purchases are concentrated among a few suppliers?
  - How much capital is locked in unsold inventory?
  - Which vendors have high margins but low sales?

This project addresses all of these questions — visually and analytically.

---

## 🛠️ Technologies Used

- **Python 3.8+**
  - `pandas`, `matplotlib`, `seaborn` for analysis & visualizations
  - `sqlite3` for database access
- **Jupyter Notebooks** for step-by-step EDA and model development
- **Power BI** *(coming soon)* for dashboards & interactive reporting
- **Git & GitHub** for version control

---

## 📊 Key Visualizations

The EDA notebook walks through the data storytelling process with:

- **Pareto chart**: Cumulative contribution of vendors to total purchases  
- **Donut chart**: Capital distribution across vendors  
- **Bar charts**: Top vendors by gross profit, margin, and unsold value  
- **Formatted tables**: Contribution %, unsold inventory, and performance ranking  

Each plot includes annotations, labels, and clean formatting — focusing on **clarity and business interpretation**.

---

## 📈 Metrics Computed

- **Total Sales Dollars**
- **Total Purchase Dollars**
- **Gross Profit** and **Profit Margin**
- **Purchase Contribution %** and **Cumulative Contribution %**
- **Unsold Inventory Value**
- **Vendor segmentation** based on performance

All metrics are aggregated and visualized to allow **comparative vendor analysis**.

---

## 🧾 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/your-username/my_vendor.git
cd my_vendor

## Upcoming Power BI Report
A fully interactive Power BI dashboard will be added to this repo, visualizing:

KPI cards (Gross Profit, Unsold Value, Total Vendors)

Vendor ranking tables with slicers

Pareto contribution curves

Unsold capital by product or category

📌 Stay tuned — .pbix file and dashboard screenshots will be included.

*Contact*
Made with love by Gul Amiz Ibrahimi
Feel free to reach out via LinkedIn or raise an issue for feedback.
