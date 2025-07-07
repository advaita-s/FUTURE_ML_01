# 📊 AI-Powered Sales Forecasting Dashboard

This project is a real-world implementation of a sales forecasting solution using AI, developed during a Machine Learning Internship at **Future Interns**. The goal is to forecast future retail sales using machine learning models and deliver business insights through a dynamic Power BI dashboard.

## Project Summary

The project leverages historical sales data from the Superstore dataset to predict upcoming sales trends. It combines data cleaning, feature engineering, and time series forecasting with Prophet to support informed decision-making in retail businesses.

---

## 📁 Dataset Used

- **Source**: Sample Superstore Sales Dataset (CSV)
- **Forecast Output**: `sales_forecast (1).csv` (includes predicted sales)

---

## 🧰 Tools & Technologies

| Tool                | Purpose                                      |
|---------------------|----------------------------------------------|
| **Python**          | Data processing and modeling                 |
| **Pandas**          | Data cleaning and manipulation               |
| **Facebook Prophet**| Time series forecasting                      |
| **Jupyter Notebook**| Development and experimentation              |
| **Power BI**        | Interactive dashboard and business insights  |
| **Excel** (optional)| Initial preprocessing or review              |

---

## 🔄 Workflow Summary

1. **Data Cleaning**
   - Removed missing values
   - Converted `Order Date` to datetime format
   - Filtered unnecessary columns

2. **Feature Engineering**
   - Renamed `Order Date` to `ds` and `Sales` to `y` for Prophet
   - Extracted date-based components (month, year)

3. **Model Training**
   - Used Facebook Prophet to train a forecasting model
   - Forecasted sales for the next 90 days

4. **Forecast Output**
   - Saved the forecast (date + predicted sales) as `sales_forecast (1).csv`

5. **Power BI Dashboard**
   - Imported forecast data and built visuals:
     - Actual vs Predicted Sales trend
     - Monthly/Yearly filters
     - Top-selling products
     - Insight cards

---

## 🎯 Skills Gained

| Skill                          | Description |
|-------------------------------|-------------|
| **Time Series Forecasting**   | With Prophet |
| **Data Cleaning & Processing**| With Pandas |
| **EDA**                       | Jupyter & Python |
| **Dashboarding**              | Power BI |
| **Business Interpretation**   | Translating trends into decisions |

## 👤 Developed By

**Advaita S S**  

BSc Computer Science (Data Analytics) Student

📌 This project is an independently developed academic and portfolio work focused on applying data analysis, machine learning, and business intelligence using real-world datasets.

