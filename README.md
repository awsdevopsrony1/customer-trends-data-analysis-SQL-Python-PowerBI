# 🛍️ Customer Trends Data Analysis

An end-to-end data analytics project exploring customer purchasing behavior using **Python**, **SQL**, and **Power BI**.

![Dashboard Preview](dashboard_preview.png)

---

## 📌 Project Overview

This project analyzes customer behavior and purchasing trends from an e-commerce dataset. It follows a complete data analytics workflow — from raw data ingestion and exploratory analysis to interactive dashboarding and stakeholder reporting.

**Key business questions answered:**
- What are the revenue and sales distributions across product categories?
- How do different age groups contribute to overall revenue?
- What is the subscription status breakdown among customers?
- How does gender influence purchasing patterns?
- Which shipping types are most preferred?

---

## 🔄 Project Workflow

```
Business Problem → Python (EDA) → SQL Database → Power BI Dashboard → Report → Presentation → GitHub
```

| Step | Tool | Description |
|------|------|-------------|
| 1 | — | Define business problem statement |
| 2 | Python | Data modelling & Exploratory Data Analysis (EDA) |
| 3 | SQL | Load data to database and run analysis queries |
| 4 | Power BI | Build interactive dashboard |
| 5 | — | Write project report summarizing findings |
| 6 | Gamma AI | Create stakeholder presentation |
| 7 | GitHub | Publish all project files to repository |

---

## 📊 Dashboard Highlights

The Power BI dashboard includes:

- **KPI Cards** — Total customers (4K), Average purchase amount ($59.76), Average review rating (3.75)
- **Subscription Status** — Donut chart showing 73% non-subscribers vs 27% subscribers
- **Revenue by Category** — Clothing leads at $104K, followed by Accessories ($74K), Footwear ($36K), Outerwear ($19K)
- **Sales by Category** — Clothing (1,737 units), Accessories (1,240), Footwear (599), Outerwear (324)
- **Revenue & Sales by Age Group** — Young Adults generate the highest revenue ($62K) and sales (1,028 units)
- **Filters** — Gender toggle, subscription status, product category, and shipping type slicers

---

## 🗂️ Repository Structure

```
customer-trends-data-analysis/
│
├── data/
│   └── customer_trends.csv          # Raw dataset
│
├── python/
│   └── eda_analysis.ipynb           # Data cleaning & EDA notebook
│
├── sql/
│   └── analysis_queries.sql         # SQL queries for data analysis
│
├── powerbi/
│   └── customer_behavior.pbix       # Power BI dashboard file
│
├── report/
│   └── project_report.pdf           # Summary report of findings
│
└── README.md
```

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Python** (Pandas, Matplotlib, Seaborn) | Data cleaning, EDA, visualization |
| **SQL** | Data storage and analytical querying |
| **Power BI** | Interactive dashboard |
| **Gamma AI** | Stakeholder presentation |
| **GitHub** | Version control and project hosting |

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- SQL Server / PostgreSQL / SQLite
- Power BI Desktop

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/awsdevopsrony1/customer-trends-data-analysis-SQL-Python-PowerBI.git
   cd customer-trends-data-analysis-SQL-Python-PowerBI
   ```

2. **Install Python dependencies**
   ```bash
   pip install pandas matplotlib seaborn jupyter
   ```

3. **Run EDA notebook**
   ```bash
   jupyter notebook python/eda_analysis.ipynb
   ```

4. **Load data into SQL**  
   Import the cleaned dataset into your SQL database and run the queries in `sql/analysis_queries.sql`.

5. **Open Power BI Dashboard**  
   Open `powerbi/customer_behavior.pbix` in Power BI Desktop and connect it to your SQL database.

---

## 📈 Key Findings

- **Clothing** is the top-performing category by both revenue and sales volume.
- **Young Adults** are the most valuable customer segment.
- The majority of customers (**73%**) are not subscribed, indicating a growth opportunity.
- Revenue is fairly evenly distributed across age groups, with seniors being competitive buyers.
- **Standard** and **Free Shipping** are the most commonly used shipping types.

---

## 🤝 Contributing

Contributions and suggestions are welcome! Feel free to open an issue or submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👤 Author

**Rony**  
GitHub: [@awsdevopsrony1](https://github.com/awsdevopsrony1)
