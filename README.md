# Sales Data Analysis

## Project Overview
This project focuses on analyzing retail sales data to identify sales trends, profitability patterns, and the impact of discounts on overall business performance. Python was used for exploratory data analysis, and Power BI was used to build an interactive one-page dashboard for visual storytelling.

The project demonstrates an end-to-end data analysis workflow, from raw data exploration to business-focused insights.

---

## Dataset
**Source:** Kaggle – Sample Superstore Dataset  
**Link:** https://www.kaggle.com/datasets/bravehart101/sample-supermarket-dataset/data

The dataset contains retail transaction data with the following attributes:
- Category and Sub-Category
- Sales, Profit, and Quantity
- Discount
- Region and Customer Segment

---

## Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook
- Power BI
- Git & GitHub

---

## Project Structure
sales-data-analysis/
│
├── data/
│ └── SampleSuperstore.csv
├── notebooks/
│ └── sales_data_analysis.ipynb
├── powerbi/
│ ├── sales_performance_dashboard.pbix
│ └── sales_performance_dashboard.pdf
├── images/
│ └── sales_dashboard_preview.png
├── README.md
└── requirements.txt

---

## Steps Performed

### 1. Data Loading and Understanding
- Loaded the dataset using Pandas
- Reviewed dataset shape, columns, and data types
- Verified that the dataset contained no missing values

### 2. Data Cleaning and Preparation
- Removed non-essential columns such as Postal Code
- Identified categorical and numerical features for analysis

### 3. Exploratory Data Analysis (Python)
- Analyzed total sales and profit by category and sub-category
- Examined regional sales performance
- Studied the relationship between discount levels and profit
- Created visualizations using Matplotlib and Seaborn

### 4. Dashboard Development (Power BI)
- Built a one-page interactive dashboard using Power BI
- Used Card visuals to display key metrics:
  - Total Sales
  - Total Profit
  - Total Quantity Sold
- Created category-wise, sub-category-wise, and region-wise charts
- Added slicers for Customer Segment and Region to enable dynamic filtering

---

## Key Insights and Learnings
- The **Technology** category generated the highest sales and profit
- **Furniture** showed lower profitability despite relatively high sales
- The **West** region contributed the highest total sales
- Higher **discounts** were frequently associated with reduced or negative profit
- **Phones** and **Chairs** emerged as top-performing sub-categories in terms of revenue

---

## Business Value
The analysis highlights areas of strong performance as well as potential inefficiencies. The insights can support better decision-making related to pricing strategies, discount policies, and regional sales planning.

---

## Dashboard Access
- The interactive Power BI file is available as a `.pbix` file in the `powerbi/` folder
- A PDF version of the dashboard is also provided for easy viewing without Power BI

---

## Conclusion
This project strengthened my understanding of data analysis workflows, business interpretation of data, and dashboard development using Power BI. It provided hands-on experience with real-world data and improved my ability to communicate insights in a clear and professional manner.