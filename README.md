# Sales-Performance-Analysis
##  Project Overview
The **Sales Performance Analysis Dashboard** is a data analytics project that focuses on analyzing sales data to identify trends, regional performance, product categories, and profitability.  
The project uses **Python for data preprocessing and analysis** and **Power BI for interactive dashboard visualization** to support business decision-making.

##  Project Objectives
- Analyze **sales and profit trends** over time
- Identify **top-performing and low-performing regions**
- Compare **category and sub-category performance**
- Visualize key metrics using an **interactive Power BI dashboard**

##  Tech Stack
- **Python**
- **Pandas**
- **Matplotlib / Seaborn**
- **Power BI**
- **CSV Dataset (Kaggle)**


##  Dataset Description
The dataset used in this project is sourced from **Kaggle**, a popular platform for open datasets used in data science and analytics projects.

The cleaned dataset contains the following columns:

Order Date
Region
Category
Sub-Category
Sales
Quantity
Profit

### Column Description:
- **Order Date** – Used for monthly and time-based trend analysis  
- **Region** – Helps compare sales performance across regions  
- **Category** – High-level product classification  
- **Sub-Category** – Detailed product grouping  
- **Sales** – Total revenue generated  
- **Quantity** – Number of units sold  
- **Profit** – Net profit from sales  

> Note: The dataset was preprocessed and cleaned using Python before dashboard creation.


##  Analysis Performed
The following analyses were performed using Python:
- Revenue by Region
- Category and Sub-Category Performance
- Monthly Sales Trends
- Profitability Analysis
- Identification of Low-Performing Products

Exploratory visualizations were created using **Matplotlib and Seaborn**, followed by an **interactive Power BI dashboard**.


##  Power BI Dashboard Features
The Power BI dashboard includes:
- **KPI Cards**:
  - Total Sales
  - Total Profit
  - Total Quantity Sold
- **Bar Chart**: Sales by Region
- **Line Chart**: Monthly Sales Trend
- **Bar Chart**: Top & Bottom Sub-Categories
- **Pie/Donut Chart**: Category-wise Sales Contribution
- **Slicers**: Region and Category filters for interactivity

##  Project Structure

Sales-Performance-Analysis/
│
├── data/
│   ├── Extracting_dataset.ipynb
│   ├── sales_dataset.csv
│   └── dashboard_sales_data.csv
│
├── notebooks/
│   └── sales_analysis.ipynb
│
├── dashboard/
│   └── sales_dashboard.pbix
│
└── README.md

##  How to Run the Project
1. Clone the repository:
git clone https://github.com/Tanuja256/Sales-Performance-Analysis.git

2. Open the Jupyter Notebook:
jupyter notebook notebooks/sales_analysis.ipynb

3. Run all cells to perform data analysis.

4. Open the Power BI dashboard:
Launch Power BI Desktop
Open dashboard/sales_dashboard.pbix
