# Customer Shopping Behavior Analysis

End-to-end data analytics project analyzing customer purchasing patterns using **Python, SQL, and Power BI** — from raw data to a stakeholder-ready dashboard and report.

---

## 📌 Overview

This project analyzes retail customer transaction data to uncover purchasing trends, customer segments, and revenue drivers. It follows a complete analytics workflow: data cleaning and exploration in Python, business-question querying in SQL, visualization in Power BI, and a final report summarizing insights and recommendations.

**Goal:** Identify key patterns in customer behavior (spending, loyalty, discounts, categories) to support data-driven business decisions.

---

## 🛠️ Tools & Technologies

| Stage | Tool |
|---|---|
| Data Cleaning & EDA | Python (Pandas, Matplotlib/Seaborn) |
| Querying & Analysis | SQL (PostgreSQL / MySQL / SQL Server) |
| Dashboard | Power BI |
| Reporting | Business report (PDF) + presentation (Gamma) |

---

## 🔎 Project Workflow

1. **Data Loading & Cleaning** — Imported the raw dataset into Python, handled missing values, fixed data types, and standardized categorical fields.
2. **Exploratory Data Analysis (EDA)** — Used Python to explore distributions, outliers, and relationships between variables (e.g., spend by category, age, gender).
3. **SQL Analysis** — Loaded the cleaned dataset into a relational database and wrote SQL queries to answer specific business questions (e.g., revenue by segment, discount impact, top products).
4. **Dashboard Development** — Built an interactive Power BI dashboard to visualize key metrics and trends for non-technical stakeholders.
5. **Reporting & Presentation** — Summarized findings into a business report and a stakeholder-facing presentation (built using Gamma).

---

## 📊 Dashboard

The Power BI dashboard highlights:
- Revenue breakdown by category, gender, and customer segment
- Discount usage and its effect on purchase behavior
- Customer loyalty segmentation (New / Returning / Loyal)
- Subscription status vs. spending patterns

📁 Dashboard file: `customer_behavior_dashboard.pbix`
🖼️ Screenshots: see `/screenshots` folder *(add if included)*

---

## 📈 Results & Key Insights

*(Replace with your actual findings — example structure below)*

- Identified a significant revenue gap between customer segments, informing targeted marketing strategies
- Found that [X]% of transactions involved a discount, with certain categories relying heavily on promotions
- Segmented customers into loyalty tiers, revealing that [X]% of the customer base falls into the "Loyal" segment
- Discovered that subscription status had [minimal/significant] impact on average spend — a counterintuitive finding worth further investigation

---

## ▶️ How to Run This Project

**1. Clone the repository**
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```

**2. Set up Python environment**
```bash
pip install pandas numpy matplotlib seaborn
```

**3. Run the analysis**
Open and run `Customer_Shopping_Behavior_Analysis.ipynb` in Jupyter Notebook or VS Code.

**4. Run SQL queries**
- Import `customer_shopping_behavior.csv` into your database of choice (PostgreSQL / MySQL / SQL Server)
- Run the queries in `customer_behavior_sql_queries.sql`

**5. Explore the dashboard**
Open `customer_behavior_dashboard.pbix` in Power BI Desktop.

---

## 📁 Repository Structure

```
├── customer_shopping_behavior.csv        # Raw dataset
├── Customer_Shopping_Behavior_Analysis.ipynb   # Python EDA & cleaning
├── customer_behavior_sql_queries.sql     # SQL business-question queries
├── customer_behavior_dashboard.pbix      # Power BI dashboard
├── Customer Shopping Behavior Analysis.pdf     # Final report
├── Business Problem Document.pdf         # Problem framing
└── README.md
```

---


