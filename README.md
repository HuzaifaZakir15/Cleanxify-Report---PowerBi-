# Cleanxify-Ecommerce-Dashboard

# 🧹 Cleanxify E-Commerce Sales Dashboard — Power BI

<p align="center">
<img width="888" height="498" alt="image" src="https://github.com/user-attachments/assets/ac014e67-c20d-453e-a100-2614e660c91a" />
</p>

---

## Overview

A three-page interactive Power BI report analyzing the sales performance, product profitability, and customer purchasing behavior of **Cleanxify**, a Pakistani e-commerce cleaning products brand. The dashboard provides actionable insights into revenue generation, order trends, product performance, customer engagement, and operational efficiency across multiple cities during **2024–2025**.

> *"Presents a comprehensive overview of business performance through sales analytics, product insights, customer behavior, and order management metrics."*

---

## Key Metrics at a Glance

| Metric            |      Value |
| :---------------- | ---------: |
| Total Revenue     |     **5M** |
| Total Profit      |     **3M** |
| Profit Margin     | **68.25%** |
| Total Orders      |  **3,735** |
| Return Rate       |  **4.15%** |
| Cancellation Rate |  **9.88%** |
| Products Tracked  |      **7** |
| Cities Covered    |     **12** |

---

## Dashboard Pages

### 1. Sales Overview

<img width="886" height="504" alt="image" src="https://github.com/user-attachments/assets/e66b16b6-c7a1-4c18-8820-ec7a8e4e0742" />

A high-level business overview designed for management and decision-makers.

**Visuals Included:**

* **Revenue KPI** — Total revenue of 5M
* **Profit KPI** — Total profit of 3M
* **Profit Margin KPI** — 68.25%
* **Order KPI** — 3,735 completed orders
* **Revenue by City** — Quetta generates the highest revenue (~0.51M)
* **Revenue & Profit by Quarter** — Quarterly performance comparison
* **Monthly Revenue Trend** — Month-over-month sales analysis
* **Year-over-Year Revenue Comparison** — Comparison between 2024 and 2025

---

### 2. Product Performance

<img width="887" height="500" alt="image" src="https://github.com/user-attachments/assets/2c4b952d-6ad5-4179-a43e-bded9f91fcad" />


Detailed analysis of product-level sales, profitability, and order volume.

**Visuals Included:**

* **Product Revenue, Profit & Margin Matrix**
* **Revenue vs Profit by Product**
* **Order Distribution by Product**
* **Product Performance Trend Analysis**
* **Product Sales Comparison Dashboard**

**Top Performing Products**

| Product                       | Revenue | Profit | Margin |
| :---------------------------- | ------: | -----: | -----: |
| Cleanxify All-Purpose Cleaner |   1.03M |  0.66M | 63.33% |
| Kitchen Degreaser             |   0.84M |  0.59M | 70.44% |
| Wood Cleaner                  |   0.63M |  0.46M | 73.12% |
| Marble & Tile Shiner          |   0.69M |  0.45M | 64.44% |

---

### 3. Order & Customer Analysis

<img width="882" height="500" alt="image" src="https://github.com/user-attachments/assets/ac8b00e9-8241-4c82-889c-f923f9ef9912" />

A customer-centric view of purchasing behavior, order fulfillment, and payment patterns.

**Visuals Included:**

* **Payment Status Breakdown**
* **Order Status Distribution**
* **Orders & Revenue by City**
* **Return vs Non-Return Orders**
* **Customer Order Insights**

**Payment Status Distribution**

| Status  | Percentage |
| :------ | ---------: |
| Paid    |     69.69% |
| Pending |     19.46% |
| Failed  |      7.76% |

**Order Status Highlights**

* Delivered orders account for the largest share (~2K orders)
* Shipped Orders: 31.27%
* Confirmed Orders: 22.37%
* Cancellation Rate: 20.79%

---

## Filters & Slicers

All report pages include synchronized filters for dynamic analysis.

| Filter         | Options                                                                                                                                             |
| :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------- |
| Product        |Cleanxify All-Purpose Cleaner · Cleanxify Marble & Tile Shiner · Kitchen Degreaser · Limescale Remover · Rust Remover · Sofa Cleaner · Wood Cleaner  |                              |
| City           | All Cities of Pakistan                                                                                                                              |
| Payment Status | Paid · Pending · Failed · Refunded                                                                                                                  |
| Order Status   | Delivered · Shipped · Confirmed · Cancelled · Processing                                                                                            |
| Year           | 2024 · 2025                                                                                                                                         |

A **Clear All Filters** button resets the report to its default state.

---

## Key Findings

* **Quetta** is the highest revenue-generating city with approximately 0.51M in sales.
* **Cleanxify All-Purpose Cleaner** generates the highest revenue among all products.
* **Kitchen Degreaser** has the highest order volume with 540 orders.
* **Wood Cleaner** achieves the highest profit margin at 73.12%.
* Revenue remains relatively stable across all quarters, indicating consistent demand.
* The **4.15% return rate** reflects strong customer satisfaction.
* Nearly **20% of orders are cancelled**, presenting an opportunity for operational improvements.

---

## Repository Structure

```text
cleanxify-ecommerce-dashboard/
│
├── Cleanxify_Report.pbix
│
├── data/
│   └── Cleanxify_Dataset.xlsx
│
├── screenshots/
│   ├── sales-overview.png
│   ├── product-performance.png
│   └── order-customer-analysis.png
│
└── README.md
```

---

## Getting Started

### Prerequisites

* Microsoft Power BI Desktop — latest version recommended
* Windows OS

### Steps

1. **Clone the repository**

```bash
git clone https://github.com/HuzaifaZakir15/Cleanxify-Ecommerce-Dashboard.git
cd Cleanxify-Ecommerce-Dashboard
```

2. **Open the report**

* Launch Power BI Desktop
* Go to **File → Open Report**
* Select **Cleanxify_Report.pbix**

3. **Explore**

* Navigate through the three dashboard pages
* Apply slicers to filter by city, product, payment status, and order status
* Use cross-filtering and drill-down functionality for deeper analysis

---

## Tech Stack

| Tool             | Purpose                                |
| :--------------- | :------------------------------------- |
| Power BI Desktop | Report Development & Visualization     |
| DAX              | KPI Calculations and Business Measures |
| Power Query (M)  | Data Cleaning and Transformation       |
| Excel            | Data Source                            |
| Data Modeling    | Relationship Management                |

---

## Data Model

The report is built using e-commerce transactional data with the following key entities:

**Orders:** `Order ID` · `Order Date` · `Order Status` · `Payment Status` · `Revenue` · `Profit`

**Products:** `Product Name` · `Category` · `Revenue` · `Profit Margin`

**Customers:** `Customer ID` · `Customer City` · `Customer Segment`

**Business Metrics:** `Revenue` · `Profit` · `Profit Margin %` · `Return Rate` · `Cancellation Rate` · `Order Count`

---

## License

This project is for educational and portfolio purposes. All data used is fictional and created for analytical demonstration purposes.

## 👤 Author

**Huzaifa Zakir**
BS Computer Science Student | Data Analyst

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/huzaifa-zakir)

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/HuzaifaZakir15)

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge\&logo=gmail\&logoColor=white)](mailto:huzaifazakir356@gmail.com)
