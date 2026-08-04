# Sales-Customer-Performance-Dashboard
Interactive Power BI dashboard for enterprise sales, customer engagement, and product return analytics using DAX and multi-dimensional data modeling.
# 📊 Sales & Customer Performance Dashboard (Power BI)

## 📌 Project Overview
The **Sales & Customer Performance Dashboard** is a comprehensive Business Intelligence solution built in Power BI. It provides real-time visibility into key performance indicators (KPIs), regional sales distribution, product category revenue, and customer return behaviors to support data-driven business decisions[cite: 1].

---

## 🔑 Key Features & Insights
* **Executive Metrics (KPIs):** Tracks Total Revenue ($844.02K), Active Customers (198), Total Orders (~1K), Average Selling Price ($152.93), and Total Returns (50)[cite: 1].
* **Regional & Category Breakdown:** Evaluates revenue performance across North, South, East, and West sales territories, and categorizes performance by Office Supplies, Furniture, and Technology[cite: 1].
* **Time-Series Trend Analysis:** Visualizes monthly and yearly revenue patterns to identify peak purchasing cycles and seasonal trends[cite: 1].
* **Operational Analytics:** Highlights top-performing product SKUs, sub-category drivers (e.g., Chairs, Phones, Paper), and daily transaction spikes[cite: 1].
* **Customer & Return Drivers:** Maps active customer engagement and pinpoints categories with elevated return rates (such as Office Supplies)[cite: 1].

---

## 🛠️ Data Model & DAX Logic
The project utilizes a relational star-schema connecting **Customers**, **Orders**, **Products**, **Sales**, **Returns**, and **Regions** datasets[cite: 1].

### Key DAX Measures Included:
* `Total_Sale`: Aggregates total gross revenue generated[cite: 1].
* `Active customers`: Calculates distinct active customer counts within the active context[cite: 1].
* `Average Price Per Unit`: Evaluates average unit selling price (`Total Revenue / Volume`)[cite: 1].
* `sales last year` & `YTD`: Time-intelligence metrics evaluating prior period benchmarks and accumulated annual revenue[cite: 1].
* `Premium_transtion_Count(>1000)`: Tracks high-value orders exceeding $1,000[cite: 1].

---

## 📁 Repository Structure
```text
├── Power BI final PR.pbix       # Power BI Dashboard file
├── final project Report.pdf    # Detailed project documentation report
└── README.md                   # Project description and documentation
