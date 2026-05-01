# 🍔 Swiggy Food Delivery Analytics Dashboard

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Data%20Analytics-orange?style=for-the-badge&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Year-2025-blue?style=for-the-badge" />
</p>

<p align="center">
  An end-to-end Power BI analytics dashboard built on Swiggy food delivery data, enabling business stakeholders to monitor sales performance, customer satisfaction, and order trends across cities and restaurant chains.
</p>

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Problem Statement](#-problem-statement)
- [KPIs Tracked](#-kpis-tracked)
- [Dashboard Features](#-dashboard-features)
- [Visualizations](#-visualizations)
- [Dataset Highlights](#-dataset-highlights)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Screenshots](#-screenshots)
- [Project Structure](#-project-structure)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🧭 Overview

This project delivers a comprehensive **Power BI Dashboard** for Swiggy's food delivery operations. Built as a Business Requirements Document (BRD)-driven analytics solution, it provides data-driven insights into sales trends, location-wise performance, restaurant rankings, and customer behaviour — all in a single interactive interface.

> **Data Year:** 2025 | **Total Orders:** 197K | **Total Sales:** ₹53.01M | **Cities Covered:** Across India

---

## 📋 Problem Statement

Swiggy generates massive volumes of transactional data daily across hundreds of cities and thousands of restaurants. The challenge was to consolidate this data into a single, intuitive dashboard that empowers business teams to:

- Monitor real-time and historical sales performance
- Identify high-performing cities, restaurants, and food categories
- Understand customer satisfaction trends across regions
- Make informed decisions on promotions, expansions, and resource allocation

---

## 📊 KPIs Tracked

| KPI | Description |
|-----|-------------|
| 💰 **Total Sales (₹)** | Overall revenue generated from food orders |
| ⭐ **Average Rating** | Customer satisfaction level across all restaurants |
| 🛒 **Average Order Value (₹)** | Revenue per individual order |
| 📝 **Ratings Count** | Total number of customer reviews submitted |
| 📦 **Total Orders** | Number of food orders received across all channels |

---

## 🚀 Dashboard Features

- ✅ **197K Total Orders** processed across the platform
- ✅ **₹53.01M Total Sales** tracked with monthly breakdowns
- ✅ **984 Restaurants** and **942 Locations** covered
- ✅ **4,731 Food Categories** analysed
- ✅ Interactive **Year** and **Dish Name** slicers for dynamic filtering
- ✅ Drill-down capability by city, month, restaurant, and dish

---

## 📈 Visualizations

### Charts Included

| Chart | Purpose |
|-------|---------|
| 📅 **Monthly Sales Trend** | Shows total sales fluctuation month by month |
| 📆 **Daily Sales Trend** | Highlights order and revenue variations across days of the week |
| 🥗 **Total Sales by Food Type** | Compares revenue by Veg vs. Non-Veg cuisine |
| 🗺️ **Total Sales by State (Map)** | Displays state-wise revenue distribution on an interactive map |
| 📊 **Quarterly Performance Summary** | Combines Sales, Ratings, and Orders by Quarter |
| 🏙️ **Top 5 Cities by Sales** | Identifies leading cities contributing the most revenue |
| 📉 **Weekly Trend Analysis** | Monitors weekly sales fluctuations to identify peak periods |
| 🍕 **Top 5 Orders by Location (Pie Chart)** | Visualises order share across top locations |
| 🏪 **Orders & Sales by Restaurant** | Bar + line combo chart across all restaurant chains |

---

## 🗂️ Dataset Highlights

- **Time Period:** January 2025 – August 2025
- **Top Cities:** Bengaluru, Lucknow, Hyderabad, Mumbai, Kolkata
- **Top Locations by Orders:** Yelahanka, Gomti Nagar, Whitefield, Nerul, Thakurpukur
- **Notable Restaurant Chains:** McDonald's, KFC, Burger King, Pizza Hut, Domino's, Starbucks, Subway
- **Sample Top Dishes:** Vietnamese Iced Coffee, McVeggie Xplode VM, Chicken Surprise, Golden Crispy Pops

**Quarterly Snapshot:**

| Quarter | Sales | Avg Rating | Total Orders |
|---------|-------|------------|--------------|
| Q1 | ₹19.2M | 4.3 | 73.1K |
| Q2 | ₹19.9M | 4.5 | 74.2K |
| Q3 | ₹13.4M | 4.3 | 50.2K |

---

## 🛠️ Tech Stack

- **Visualisation:** Microsoft Power BI Desktop
- **Map Integration:** Microsoft Bing Maps
- **Data Processing:** Power Query (M Language)
- **DAX Measures:** Custom KPI calculations
- **Data Source:** Swiggy order-level transactional data (CSV/Excel)

---

## 🏁 Getting Started

### Prerequisites

- [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) (latest version recommended)
- Windows 10 / 11

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/swiggy-powerbi-dashboard.git
   cd swiggy-powerbi-dashboard
   ```

2. **Open the dashboard:**
   - Launch Power BI Desktop
   - Open `Swiggy_Dashboard.pbix`

3. **Connect your data source:**
   - Go to `Home → Transform Data → Data Source Settings`
   - Update the file path to point to your local dataset

4. **Refresh the data:**
   - Click `Home → Refresh` to load the latest data

5. **Explore the dashboard:**
   - Use the **Year** slicer to filter by time period
   - Use the **Dish Name** slicer to drill into specific items
   - Click on any chart element to cross-filter all visuals

---

## 🖼️ Screenshots

### Main Dashboard
![Swiggy Dashboard](./assets/swiggy_dashboard.png)

> *Full interactive dashboard showing KPI cards, pie chart, map, monthly trend, and restaurant-level bar chart.*

---

## 📁 Project Structure

```
swiggy-powerbi-dashboard/
│
├── 📊 Swiggy_Dashboard.pbix       # Main Power BI file
├── 📂 data/
│   └── swiggy_orders_2025.csv     # Raw dataset
├── 📂 assets/
│   └── swiggy_dashboard.png       # Dashboard screenshot
├── 📂 docs/
│   ├── BRD_KPIs.pdf               # Business Requirements - KPIs
│   └── BRD_Charts.pdf             # Business Requirements - Charts
└── 📄 README.md                   # Project documentation
```

---

## 🤝 Contributing

Contributions are welcome! If you'd like to improve the dashboard or add new features:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/new-visual`
3. Commit your changes: `git commit -m 'Add: new weekly trend visual'`
4. Push to the branch: `git push origin feature/new-visual`
5. Open a Pull Request

Please ensure your changes align with the BRD requirements documented in the `/docs` folder.

---

## 📜 License

This project is licensed under the [MIT License](./LICENSE).

---

## 🙋‍♂️ Author

**Your Name**
- GitHub: [@your-username](https://github.com/your-username)
- LinkedIn: [your-linkedin](https://linkedin.com/in/your-linkedin)

---

<p align="center">
  Made with ❤️ using Power BI &nbsp;|&nbsp; Data-Driven Decisions for Swiggy Analytics
</p>
