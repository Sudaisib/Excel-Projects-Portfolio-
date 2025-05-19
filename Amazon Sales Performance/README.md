# 📦 Amazon Sales Performance Dashboard – 2025  

![Amazon](https://github.com/user-attachments/assets/a1b5315c-43d2-4b71-bc2c-cc340bc35825)

---

## 📌 Table of Contents  
1. [📊 Project Overview](#-project-overview)  
2. [📌 Business Use Case](#-business-use-case)  
3. [📂 Data Sources](#-data-sources)  
4. [🛠 Tools & Technologies](#-tools--technologies)  
5. [📈 KPIs Monitored](#-kpis-monitored)  
6. [🧹 Data Cleaning](#-data-cleaning)  
7. [📈 Key Insights](#-key-insights)  
8. [🎯 Recommendations](#-recommendations)  
9. [⚠️ Limitations](#-limitations)  
10. [🎥 Video Tutorials & Walkthroughs](#-video-tutorials--walkthroughs)  
11. [🚀 Future Improvements & Roadmap](#-future-improvements--roadmap)  
12. [📊 Interact with the Dashboard](#-interact-with-the-dashboard)  
13. [🖼️ Dashboard Preview](#-dashboard-preview)  
14. [✍️ Author](#-author)  
15. [📌 License](#-license)  

---

## 📊 Project Overview  

### 🛍️ Understanding Amazon's Sales Performance  
The Amazon Sales Performance Dashboard is an Excel-based analytics solution aimed at uncovering performance patterns across sales channels, product categories, and customer behavior. It supports data-driven decision-making by visualizing key sales metrics, fulfillment issues, and revenue trends in a simplified, interactive format.  

This dashboard allows stakeholders—such as sales managers, product owners, and supply chain leaders—to:  
- Identify high-performing and underperforming products.  
- Monitor real-time revenue across multiple time frames.  
- Detect operational bottlenecks in order processing and fulfillment.  
- Align strategic efforts with actual customer behavior patterns.

It acts as both a diagnostic and predictive tool for boosting performance and profitability.

---

## 📌 Business Use Case  
This dashboard is designed for e-commerce decision-makers within Amazon or similar retail platforms. Business needs addressed include:  
- **Performance Tracking:** What products and categories are driving growth?  
- **Operational Efficiency:** Where are delays and cancellations occurring most?  
- **Customer Preferences:** Which days, methods, or months perform best?  
- **Revenue Strategy:** Which months and categories need re-optimization?
  
---

## 📂 Data Sources  
- **Amazon Sales 2025 Dataset**  
Fields include:  
- `Order ID`, `Product`, `Category`, `Payment Method`, `Order Date`, `Sales Revenue`, `Order Quantity`, `Order Status`, etc.  
---

## 🛠 Tools & Technologies  
- **Microsoft Excel**: Core tool for data analysis and visualization.  
- **Pivot Tables & Charts**: Used to summarize large datasets.  
- **Data Cleaning Techniques**: For accuracy and consistency.  
- **Interactive Dashboards**: Visual storytelling for insights.

---

## 📈 KPIs Monitored  

| KPI | Value | Description |
|-----|-------|-------------|
| 💰 **Total Revenue** | `$243,845` | Total sales generated across all orders. |
| 📦 **Total Quantity Sold** | `714` | Total number of product units sold. |
| 🧾 **Order Volume** | `250` | Total number of unique orders placed. |
| 🧮 **Average Order Value (AOV)** | `$342` | Average revenue generated per order (`Revenue ÷ Orders`). |
| ⭐ **Top-Selling Product** | `Refrigerator – $78,000` | Product with the highest revenue contribution. |
| 👤 **Best Customer** | `Olivia Wilson – $36,170` | Customer with the highest total purchases. |

---

## 🧹 Data Cleaning  
### Data Transformation Steps:  
1. **Date Standardization** – Ensured a consistent format across all date fields.  
2. **Duplicates & Nulls** – Removed irrelevant or empty records.  
3. **Category Consolidation** – Merged overlapping or duplicate product categories.  
4. **Field Formatting** – Applied appropriate number, currency, and text formatting.  
5. **Derived Columns** – Added Month and Day-of-Week columns for time-series analysis.

---

## 📈 Key Insights  

### 💰 Top Products by Revenue  
- **Refrigerators, Laptops, and Smartphones** generated over **60% of total revenue**.  
- **Smartwatches and Washing Machines** are secondary contributors.  
- **Books, T-Shirts, and Jeans** contributed the least — potentially low-margin or under-marketed.

### 💳 Payment Methods  
- **PayPal** is the leading method, followed by **Credit** and **Debit Cards**.  
- **Amazon Pay and Gift Cards** are underutilized, suggesting promotion opportunities.  
- The **diverse payment mix** reflects customers’ demand for flexibility.

### 📆 Monthly Sales Trends  
- **February had the highest revenue** ($122,695), despite **March having the most orders** (131).  
- **April experienced a significant dip** in both revenue and volume — potential marketing or logistics issues.

### 📦 Category-Wise Quantity  
- **Electronics (348 units)** far exceed all other categories.  
- **Clothing (115)** and **Home Appliances (110)** follow.  
- **Books (69)** and **Footwear (72)** lag in volume.

### 📅 Day-of-Week Sales  
- **Monday and Tuesday** are the best-performing days in terms of revenue.  
- **Saturday has the lowest sales** ($19,625), signaling low engagement.  
- **Thursday and Sunday** show promising weekend traffic.

### ✅ Order Fulfillment Status  
- **Completed orders (88)** barely outnumber **Pending (85)** and **Cancelled (77)** — a sign of potential inefficiencies.  
- High cancellation and pending rates point to **order fulfillment or payment issues**.

---

## 🎯 Recommendations  

### 🔧 Product Strategy  
- Prioritize **Refrigerators, Laptops, and Smartphones** in marketing and stock management.  
- Assess viability of low-performing items like **Books and T-Shirts**.  
- Upsell **Smartwatches** and **Headphones** with flagship electronics.

### 💳 Payment Optimization  
- Enhance **PayPal and Credit/Debit** integrations.  
- Promote **Amazon Pay and Gift Cards** using discounts or cashback incentives.

### 📈 Monthly Sales Strategy  
- Investigate **April's drop** — check inventory, marketing, or seasonal factors.  
- **Replicate strategies** from February and March across other months.

### 🛍️ Category Optimization  
- Continue pushing **Electronics** with smart bundles.  
- Use **cross-category promotions** to lift underperforming segments.  
- Consider phasing out or rebranding low-margin products.

### 📅 Weekday Campaign Strategy  
- Launch **weekly deals early in the week** to ride Monday–Tuesday peaks.  
- Address **Saturday’s underperformance** with weekend flash sales or free shipping.

### 🚚 Order Fulfillment  
- Audit **pending/cancelled orders**: inventory, payments, logistics.  
- Implement **automated alerts** and improve delivery experience.  
- Create **feedback loops** for customer cancellation reasons.

---

## ⚠️ Limitations  

While this project offers clear insights, it has certain limitations that should be addressed in future iterations:

1. **Customer Segmentation Missing**  
   - No demographic or geographic data to personalize recommendations or identify buyer personas.

2. **No Promotional Influence Captured**  
   - Sales spikes may be influenced by promotions or external events, which are not reflected in the dataset.

3. **No Marketing Attribution**  
   - Can't assess if users arrived via ads, organic search, social media, etc.

4. **Fulfillment Complexity Hidden**  
   - Doesn’t account for internal logistics delays or third-party shipping performance.

5. **Limited Time Span**  
   - Data is constrained to 2025, restricting long-term trend analysis or seasonality benchmarking.

---

## 🎥 Video Tutorials & Walkthroughs  

### ▶️ Watch the Full Dashboard Tour  
Walkthrough on how to explore the Amazon Sales Dashboard in Excel:  
📽️ [Click here to watch the tutorial](https://youtu.be/example-link) *(replace with actual YouTube link)*

### 🔧 Excel Dashboard Creation Steps  
- Importing Data via Power Query  
- Cleaning and Transforming Data  
- Building PivotTables  
- Creating Charts and Slicers  
- Designing the Final Dashboard Layout  

---
## 🚀 Future Improvements & Roadmap  

| Feature | Status | ETA |
|--------|--------|-----|
| Add Customer Demographics | ⬜ Planned | Q2 2025 |
| Connect to Power BI version | ⬜ Planned | Q3 2025 |
| Predictive Analytics using Excel Forecasting | ⬜ Planned | Q2 2025 |
| Integration with Real-Time API Feed | ⬜ Planned | Q4 2025 |
| Automated Email Reports | ⬜ Planned | Q4 2025 |
| Sentiment Analysis from Customer Reviews | ⬜ Planned | 2026 |

---
## 📊 Interact with the Dashboard  
Explore the Amazon Sales Dashboard built in Microsoft Excel:  
📎 **[Click here to view the dashboard](#)** (insert OneDrive/Google Drive link or GitHub repo preview)

---

## 🖼️ Dashboard Preview

### 📊 Amazon Sales Dashboard (Excel – 2025)

![Amazon Sales Dashboard Image](https://github.com/user-attachments/assets/bf8592c0-daca-4531-bf91-620b04805848)


*A snapshot of the interactive dashboard built with Excel, showcasing revenue performance, product analysis, and fulfillment status.*

---

## ✍️ Author

**Oladosu Ibrahim Adeniyi**
*Data Analyst | Cloud Enthusiast | Business Intelligence Developer*

📧 **Email**: [oladosuadeniyi39@gmail.com](mailto:oladosuadeniyi39@gmail.com)
🔗 **LinkedIn**: [linkedin.com/in/oladosu-ibrahim-12427b197](https://www.linkedin.com/in/oladosu-ibrahim-12427b197)

---

## 📌 License  
This project is licensed under the MIT License 


---


