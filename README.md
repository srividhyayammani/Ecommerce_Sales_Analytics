# Ecommerce_Sales_Analytics
End-to-end E-Commerce Sales Analytics project: Python (cleaning + RFM), SQL (data extraction), Power BI (dashboard &amp; forecasting).

# 🛒 E-Commerce Sales Analytics Dashboard

## 📌 Problem Statement
E-commerce businesses need to track revenue, orders, and customer behavior to improve sales and retention.  
This project builds an **end-to-end pipeline**:
- SQL/Python preprocessing of raw order data
- Power BI dashboard (Revenue, Customers, Avg. Order Value, Trends)
- Customer RFM segmentation

---

## 🔧 Tools & Skills
- **Python** → pandas, matplotlib, scikit-learn (for cleaning + RFM)
- **SQL** → extracting & transforming raw tables
- **Power BI** → KPIs, trend analysis, forecasting

---

## 📂 Project Structure
Ecommerce_Sales_Analytics/
│── data/ (sample ecommerce dataset)
│── notebooks/ (Python cleaning + RFM notebook)
│── sql/ (queries for preprocessing)
│── powerbi/ (Ecommerce_Dashboard.pbix)
│── screenshots/ (Dashboard visuals)
│── README.md


---

## 📊 Dashboard (Screenshots)
### Main Dashboard
![Dashboard Screenshot](screenshots/dashboard_full.png)

**KPIs included**:
- Total Revenue = `SUM(Amount)`
- Active Customers = `DISTINCTCOUNT(CustomerID)`
- Avg Order Value = `SUM(Amount) / COUNTROWS(VALUES(InvoiceNo))`

### Trend with Forecast
![Revenue Trend](screenshots/revenue_trend.png)

---

## 📈 Key Insights
- 📦 Revenue trend is **seasonal**, with spikes before festivals.  
- 👩‍💻 Top 10 customers contribute **X% of total revenue**.  
- 💳 Avg. Order Value is **₹Y**, higher for repeat customers.  
- 🎯 RFM shows **Champions** segment has the highest lifetime value.  

---

## 🚀 How to Reproduce
1. Get dataset → [Online Retail Dataset (UCI)](https://archive.ics.uci.edu/ml/datasets/Online+Retail).  
2. Run preprocessing notebook → outputs `transactions_cleaned.csv`.  
3. Load CSV into **Power BI** → refresh visuals.  

---

## 📢 Next Enhancements
- Forecasting in Power BI (Analytics pane).  
- Bookmarks → "Executive View" vs "Customer View".  
- Python clustering → integrate into Power BI.  

---

## 📜 License
MIT License © 2025 Your Name









