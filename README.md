# Sales Performance Dashboard | Power BI | FY 2026

![Dashboard Preview](Dashboard.png)

## 📊 Project Overview
Interactive Power BI dashboard analyzing ₹16.6M sales revenue across 1,000 orders. Built for business stakeholders to track KPIs, identify regional performance gaps, and drive data-backed strategy.

## 🛠️ Tools & Technologies
- **Power BI Desktop** - Data modeling & visualization
- **DAX** - 5 custom measures + Time Intelligence
- **Data Source** - Simulated e-commerce sales data: 1K rows, FY 2026

## 📈 Key KPIs Tracked
| Metric | Value |
| --- | --- |
| Total Revenue | ₹16.6M |
| Total Orders | 1K |
| Average Order Value | ₹16.64K |
| Profit Margin % | 14.50% |

## 🎯 Key Business Insights
1. **North region** contributes highest revenue, while **West** has lowest revenue share
2. **Technology category** dominates with **71.5%** of total revenue - high dependency risk
3. **Jun-2026** recorded peak revenue at **₹2.0M+** with steady growth from Sep-2025
4. **Business Action**: Leverage North + Tech strength. Investigate West region drop and push high-margin Tech products to improve overall margin from 14.5% to 18%+

## ⚙️ Dashboard Features
1. **Dynamic Slicers** - Filter by Date, Region, Category for real-time analysis
2. **Time Intelligence** - Monthly revenue trend using custom Date table + DAX
3. **Top N Filtering** - Top 5 Products by Revenue for focused view
4. **Interactive Charts** - Donut, Bar, Line charts with cross-filtering

## 📂 Files in Repository
- `Sales_Dashboard.pbix` - Power BI source file
- `Sales_Dashboard.pdf` - 1-page PDF for quick viewing
- `Dashboard.png` - Screenshot for preview

## 🚀 How to Use
1. Download `Sales_Dashboard.pbix`
2. Open in Power BI Desktop
3. Use slicers on the left to interact with data
4. Hover on charts for detailed tooltips

## 💡 DAX Measures Used
- `Total Revenue` = SUM(Sales[Revenue])
- `Total Orders` = DISTINCTCOUNT(Sales[OrderID])
- `AOV` = DIVIDE([Total Revenue], [Total Orders])
- `Profit Margin %` = DIVIDE(SUM(Sales[Profit]), [Total Revenue])
- `Date Table` with MonthNo for proper sorting

---
**Connect with me on [LinkedIn](www.linkedin.com/in/abhishek-kumar-a5a819283)** | Open to Data Analyst roles
