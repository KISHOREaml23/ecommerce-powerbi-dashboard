# 🛒 E-Commerce Sales & Business Analytics Dashboard

<p align="center">
  <b>Interactive E-Commerce Sales, Product, Customer & Regional Analytics Dashboard</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/DAX-512BD4?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Power%20Query-217346?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white"/>
</p>

---

## 📊 Project Overview

The **E-Commerce Sales & Business Analytics Dashboard** is an interactive Power BI project designed to analyze e-commerce business performance across sales, products, customers, and regions.

The dashboard transforms raw transactional data into meaningful business insights using **Power BI, DAX, Power Query, and interactive data visualizations**.

---

## 🎯 Business Objective

The main objective of this project is to help business users:

- Monitor overall sales performance
- Analyze revenue and profit
- Identify top-performing products
- Understand customer purchasing behavior
- Compare regional performance
- Track order status
- Identify high-performing categories
- Support data-driven business decisions

---

# 📑 Dashboard Pages

## 🏠 1. Home Page

A professional landing page providing easy navigation to all dashboard sections.

### Features
- Executive Overview
- Product Analysis
- Customer Analysis
- Regional Analysis
- Interactive page navigation

---

## 📊 2. Executive Overview

Provides a high-level summary of overall business performance.

### KPIs
- Total Revenue
- Total Profit
- Total Quantity
- Total Orders

### Visuals
- Monthly Revenue Trend
- Revenue by Category
- Top 10 Products by Revenue
- Revenue by City
- Profit by Category
- Order Status

### Filters
- Year
- State
- Date

---

## 📦 3. Product Analysis

Provides detailed insights into product-level performance.

### KPIs
- Total Products
- Products Sold
- Product Revenue
- Product Profit

### Visuals
- Top 10 Products by Revenue
- Top 10 Products by Profit
- Category-wise Revenue
- Category-wise Profit
- Product Sales Trend
- Product Quantity by Category
- Product Performance Table

---

## 👥 4. Customer Analysis

Analyzes customer purchasing behavior and contribution.

### KPIs
- Total Customers
- Customer Revenue
- Customer Profit
- Customer Orders
- Average Order Value

### Visuals
- Top 10 Customers by Revenue
- Customer Revenue by City
- Customer Revenue Trend
- Orders by Category
- Customer Profit by Category
- Customer Performance Table

---

## 📍 5. Regional Analysis

Analyzes business performance across different regions and states.

### KPIs
- Total Regions
- Regional Revenue
- Regional Profit
- Regional Orders

### Visuals
- Revenue by State
- Profit by State
- Revenue by City
- Orders by Region
- Regional Revenue Trend
- Revenue Share by State
- Regional Sales Performance Map
- Regional Performance Table

---

# 📈 Key KPIs

| KPI | Description |
|---|---|
| 💰 Total Revenue | Overall revenue generated |
| 📈 Total Profit | Overall profit generated |
| 📦 Total Quantity | Total quantity sold |
| 🛒 Total Orders | Number of unique orders |
| 👥 Total Customers | Number of unique customers |
| 📊 Profit Margin | Profit as a percentage of revenue |
| 💵 Average Order Value | Average revenue per order |

---

# 🧮 DAX Measures

### Total Revenue
```DAX
Total Revenue =
SUM(Order_Items[Revenue])
```

### Total Profit
```DAX
Total Profit =
SUM(Order_Items[Profit])
```

### Total Quantity
```DAX
Total Quantity =
SUM(Order_Items[Quantity])
```

### Total Orders
```DAX
Total Orders =
DISTINCTCOUNT(Orders[OrderID])
```

### Total Customers
```DAX
Total Customers =
DISTINCTCOUNT(Customers[CustomerID])
```

### Profit Margin
```DAX
Profit Margin =
DIVIDE(
    [Total Profit],
    [Total Revenue],
    0
)
```

### Average Order Value
```DAX
Average Order Value =
DIVIDE(
    [Total Revenue],
    [Total Orders],
    0
)
```

---

# 🛠️ Tools & Technologies

### Data & Processing
- Microsoft Excel
- Power Query

### Data Visualization
- Microsoft Power BI
- Interactive Charts
- KPI Cards
- Maps
- Slicers
- Tables
- Donut Charts

### Analytics
- DAX
- Data Modeling
- Data Cleaning
- Data Transformation
- Business Intelligence

---

# 🔄 Data Workflow

```text
Raw E-Commerce Data
        ↓
Data Cleaning
        ↓
Power Query
        ↓
Data Transformation
        ↓
Data Modeling
        ↓
DAX Measures
        ↓
Interactive Visualizations
        ↓
Business Insights
```

---

# 📊 Data Model

The project contains multiple business entities:

```text
Customers
    │
    ├── Orders
    │      │
    │      └── Order_Items
    │               │
    │               └── Products
    │
    ├── Regions
    ├── Sellers
    └── Suppliers

Calendar
    │
    └── Orders / Order_Items
```

---

# 🎨 Dashboard Features

- 🔹 Professional dashboard theme
- 🔹 Interactive navigation
- 🔹 Dynamic KPI cards
- 🔹 Date filtering
- 🔹 Year filtering
- 🔹 State filtering
- 🔹 Category filtering
- 🔹 Product filtering
- 🔹 Top-N analysis
- 🔹 Interactive maps
- 🔹 Revenue analysis
- 🔹 Profit analysis
- 🔹 Customer analysis
- 🔹 Product analysis
- 🔹 Regional analysis

---

# 💡 Business Insights

The dashboard can help identify:

- Top revenue-generating products
- Most profitable categories
- High-value customers
- Best-performing cities and states
- Revenue trends over time
- Order status distribution
- Regional sales contribution
- Product performance patterns

---

# 📸 Dashboard Preview

Add your screenshots to the `screenshots/` folder and keep these names:

### 🏠 Home Page
![Home Page](screenshots/home.png)

### 📊 Executive Overview
![Executive Overview](screenshots/executive-overview.png)

### 📦 Product Analysis
![Product Analysis](screenshots/product-analysis.png)

### 👥 Customer Analysis
![Customer Analysis](screenshots/customer-analysis.png)

### 📍 Regional Analysis
![Regional Analysis](screenshots/regional-analysis.png)

---

# 📁 Project Structure

```text
E-Commerce-PowerBI/
│
├── ECOMMERCE.pbix
│
├── screenshots/
│   ├── home.png
│   ├── executive-overview.png
│   ├── product-analysis.png
│   ├── customer-analysis.png
│   └── regional-analysis.png
│
└── README.md
```

---

# 🚀 How to Use

1. Download or clone this repository.
2. Open `ECOMMERCE.pbix` using Power BI Desktop.
3. Refresh the dataset if required.
4. Navigate through the dashboard using the sidebar.
5. Use slicers to filter the analysis.
6. Explore product, customer, and regional insights.

---

# 🎯 Skills Demonstrated

- Power BI Dashboard Development
- Data Cleaning
- Data Transformation
- Data Modeling
- DAX
- Business Analytics
- Data Visualization
- KPI Development
- Interactive Dashboard Design
- Geographical Analysis
- Customer Analytics
- Product Analytics
- Regional Analytics

---

# 👨‍💻 Author

## KISHORE V

**B.Tech Artificial Intelligence & Machine Learning**

Aspiring Data Analyst | Power BI | Python | SQL

---

⭐ If you find this project useful, consider giving the repository a **Star**.
