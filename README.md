# Customer-Churn-Analysis-Dashboard 
A comprehensive churn analysis using both Power BI and Python on a customer dataset. This dual approach showcases how the same dataset can be explored using drag-and-drop BI tools and code-first data science techniques — ideal for hybrid data roles.
## 🚀 Project Overview
A data has been collected from kaggle of random website churn analysis. Churn means how many people withdrawn their subscription of that specific website. In this dashboard I've analyze data on both Python and Power-bi.

- 📊 **Power BI** for business intelligence and drag-and-drop visual dashboards

- 🐍 **Python** (Matplotlib & Pandas) for programmatic analysis and visualization

It highlights how the same dataset can be analyzed using both no-code and code-first approaches — ideal for hybrid data roles.
 
### 🔧Tools & Libraries Used
|Tools      |Purpose                           |
|-----------|----------------------------------|
|Power BI   | Business dashboard and DAX KPIs  |
|Python     | Data analysis and static charts  |
|Pandas     | Data wrangling                   |
|Matplotlib | Visualization (bar, line, funnel)|

### 📊KPIs Tracked
🧍 Total Customers

✅ Total Active Users

🔄 Total Churned Users

📈 Churn Rate

🕒 Average Tenure

📞 Support Calls

⏳ Average Payment Delay

💸 Average Total Spend

## 📊Power BI Dashboard
> Found in `customer-churn-dashboard-power-bi`
### Charts
- **Bar Chart:**
- **Area Chart:**
- **Pie Chart:**

### 📌 Features:
- Interactive filter (Subscription type).
- Bar Charts showing the major difference in churn analysis.
- Visuals: Pie chart, different bar charts, age-series area chart, KPI cards.
  
## 🐍Python Dashboard
> Found in `customer-churn-dashboard-python`
### Charts
- **Bar Chart:**
- **Box Chart**
- **Pie Chart**

### 📌 Features:
- KPI calculations using Pandas (`.sum()`, `.mean()`)
- Bar charts for churn and activity analysis by gender, churn by subscription and contract length before churn.
- Box plot for age distribution over users.
- Histogram of distribution of total spend.
- Pie chart for churn analysis. 

## 📂 Dataset

A sample churn dataset was used containing the following fields:
- `Customer Id`
- `Age`
- `Gender`
- `Tenure `
- `Usage Frequency`
- `Support Call`
- `Payment Delay`
- `Subscription Type`
- `Contract Length`
- `Total Spend`
- `Last Interaction`
- `Churn`

*(Dataset file included in `Churn-analysis.xlsx`)*

## 📚 Learning Outcomes

- 📊 Build interactive dashboards in Power BI using DAX and visuals
- 🐍 Perform the same analysis in Python using code and charts
- 🧠 Interpret KPIs like revenue trends, conversion rates, and category performance
- 🔀 Gain versatility in using both business-friendly and technical tools


## 📎 How to Use

1. Clone or download the repo
2. Open the `.pbix` file in Power BI Desktop
3. Open the `.ipynb` file in Jupyter Notebook
4. Run the cells and explore the dashboard visuals
