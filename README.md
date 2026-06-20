E-Commerce Sales Analytics Dashboard
Overview

This project analyzes the Global Superstore dataset to uncover meaningful business insights related to sales performance, customer behavior, product profitability, regional trends, and seasonal patterns.

The goal of this analysis is to move beyond basic reporting and answer important business questions such as:

Which customers contribute the most value to the business?
Which products generate the highest profits?
Which regions perform well and which need improvement?
How do discounts affect profitability?
Are there any seasonal sales patterns?

The project follows a complete data analytics workflow, from data understanding and cleaning to visualization and business recommendations.

Dataset

The analysis is based on the Global Superstore dataset, which contains transactional data including:

Order details
Customer information
Product information
Sales and profit metrics
Regional data
Shipping details
Project Objectives

The main objectives of this project are:

Understand the structure and quality of the dataset
Clean and prepare the data for analysis
Explore customer, product, and regional performance
Identify key drivers of sales and profit
Analyze trends over time
Create visualizations that support business decision-making
Project Workflow
Data Understanding
Examined dataset dimensions and structure
Reviewed data types and column information
Identified missing values
Checked for duplicate records
Data Cleaning
Removed duplicate entries
Handled missing values
Converted date columns to datetime format
Created additional features such as:
Order Month
Order Year
Profit Margin
Exploratory Data Analysis

The analysis focused on the following areas:

Business Performance
Total Sales
Total Profit
Total Orders
Average Order Value
Customer Analysis
Top customers by sales
Most profitable customers
Customer segment performance
Product Analysis
Top-selling products
Most profitable products
Loss-making products
Regional Analysis
Sales and profit by region
Best and worst performing states
Time Series Analysis
Monthly sales trends
Year-over-year growth
Seasonal demand patterns
Key Insights
The Consumer segment generated the highest profit among all customer segments.
Higher sales generally led to higher profits, but several high-sales orders resulted in losses.
Discounts showed a strong negative relationship with profit margins.
Shipping costs increased with larger order values.
The business demonstrated steady growth over time with noticeable seasonal patterns.
Most orders had relatively low sales values, while a small number of orders contributed significantly to overall revenue.
Visualizations

The project includes more than 15 visualizations, including:

Sales trend analysis
Profit trend analysis
Category-wise sales and profit
Customer performance charts
Product performance charts
Regional analysis charts
Correlation heatmap
Histograms
Boxplots
Pairplots
Scatter plots
Monthly order trends
Technologies Used
Python
Google Colab
Pandas
NumPy
Matplotlib
Seaborn
Project Structure
E-Commerce-Sales-Analytics-Dashboard/

├── data/
│   └── Global_Superstore2.csv

├── notebooks/
│   └── E-Commerce Sales Analytics Dashboard.ipynb

├── images/
│   └── visualizations/

├── README.md
Getting Started
Clone the repository
git clone https://github.com/your-username/e-commerce-sales-analytics-dashboard.git
Navigate to the project directory
cd e-commerce-sales-analytics-dashboard
Install the required libraries
pip install pandas numpy matplotlib seaborn
Run the notebook

Open the notebook in Google Colab or Jupyter Notebook and execute the cells sequentially.

Future Improvements

Potential enhancements for this project include:

Building an interactive dashboard using Power BI or Streamlit
Developing customer segmentation models
Forecasting future sales using time series models
Creating a customer churn prediction model
Performing market basket analysis
Automating reporting workflows
Conclusion

This project demonstrates how data analysis can transform raw transactional data into actionable business insights. By combining data cleaning, exploratory analysis, and visualization techniques, the project highlights opportunities to improve profitability, optimize discount strategies, strengthen customer relationships, and support data-driven decision-making.

Author

Piyush Rawat

If you have any feedback or suggestions, feel free to connect or open an issue in this repository.
