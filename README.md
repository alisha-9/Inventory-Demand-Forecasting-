# 📦 Inventory Demand Forecasting using Machine Learning

## 🧠 Overview
This project is focused on improving inventory management through accurate demand forecasting using machine learning models. By predicting future sales, businesses can make informed decisions on stock replenishment, reduce inventory costs, and avoid stockouts or overstocking.

The final output is visualized through an interactive **Power BI Dashboard** that displays sales trends, reorder insights, and forecast accuracy.

---

## 🔍 Problem Statement
Inventory mismanagement leads to significant financial losses and customer dissatisfaction. Traditional rule-based inventory planning often fails to adapt to dynamic demand. This project aims to:
- Forecast item-level sales across different stores
- Automatically flag items that need reordering
- Help stakeholders visualize trends through a dashboard

---
![DASHBOARD](https://github.com/user-attachments/assets/59157fc7-b7c4-4d4c-a670-a6a5d78c49d0)

## ✅ Features
- 📊 Exploratory Data Analysis (EDA)
- 🤖 Sales Forecasting using machine learning models
- 🚨 Reorder flag generation based on predicted demand
- 📈 Power BI Dashboard for interactive visualization

---

## 🧰 Tools & Technologies
- **Python**: pandas, numpy, scikit-learn, xgboost
- **Jupyter Notebook**: for modeling and experimentation
- **Power BI**: for dashboard and reporting
- **CSV Files**: as the primary dataset source
---

## 📈 Power BI Dashboard Highlights
The dashboard includes the following:
- **Line Chart**: Total Sales over Time
- **KPI Cards**: Total Sales, Reorder Rate, Total Reorders
- **Bar Chart**: Reorders by Item
- **Slicers**: Store, Item, and Date
- **Conditional Formatting**: Highlights items needing reorder

---

## 🚀 Getting Started

### Clone the Repository
```bash
git clone https://github.com/your-username/inventory-demand-forecasting.git
cd inventory-demand-forecasting

Run the Model
  1.Open the notebooks/forecast_model.ipynb
  2.Load your dataset and run all cells
  3.Export predictions to CSV

Load into Power BI
  1.Open dashboard/InventoryDashboard.pbix
  2.Replace data source with your exported CSV
  3.Refresh and explore the dashboard

📌 Future Enhancements
  1.Real-time prediction API with Flask or FastAPI
  2.Deployment of web-based dashboard
  3.Advanced forecasting models like Prophet or LSTM
  4.Integration with inventory management systems

