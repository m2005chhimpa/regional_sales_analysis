# regional_sales_analysis

# Regional Sales Analysis

## 📊 Project Overview
This project analyzes regional sales data to uncover key revenue and profit drivers across products, channels, and regions. It includes data cleaning, feature engineering, and exploratory data analysis (EDA) with visualizations to identify trends, outliers, and performance against budgets.

## 📂 Dataset
The dataset consists of multiple sheets:
- **Sales Orders**: Order details including quantity, unit price, revenue, and costs.
- **Customers**: Customer index and names.
- **Regions**: Geographic and demographic information (state, county, population, median income).
- **Products**: Product catalog.
- **State Regions**: Mapping of states to regions.
- **2017 Budgets**: Budget allocations per product.

## 🛠️ Workflow
1. **Data Cleaning & Wrangling**
   - Merge sales with customers, products, regions, and budgets.
   - Handle missing values and redundant columns.
   - Standardize column names.

2. **Feature Engineering**
   - Calculate total cost, profit, and profit margin.
   - Create time-based features (monthly sales trends).

3. **Exploratory Data Analysis**
   - Monthly sales trends.
   - Top/bottom products by revenue.
   - Sales by channel.
   - State-level performance (revenue & order count).
   - Customer segmentation (revenue vs. profit margin).
   - Correlation heatmaps.

4. **Insights**
   - Identify high-value customers and regions.
   - Compare actuals vs. 2017 budgets.
   - Highlight opportunities for pricing and promotions.

## 📈 Visualizations
- Line charts for monthly sales trends.
- Bar charts for top/bottom products and states.
- Pie chart for sales by channel.
- Scatter plot for customer segmentation.
- Heatmap for correlation analysis.

## 🚀 Technologies Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter/Colab Notebooks
- Power BI (for dashboarding)

## 📑 How to Run
