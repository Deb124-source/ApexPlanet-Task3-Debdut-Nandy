
# ApexPlanet Data Analytics Internship — Task 3

## Data Visualization & Dashboarding

This project is part of my **30-Day Data Analytics Internship at ApexPlanet**.

Task 3 focuses on transforming the cleaned Online Retail dataset into meaningful visual insights using **Python** and an interactive **Power BI dashboard**.

The objective was to move beyond data analysis and present business insights in a clear, visual and accessible way.

---

## Project Overview

The project uses the **Online Retail dataset** to analyze e-commerce sales performance, product revenue, customer activity and sales trends.

The analysis was performed using:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Power BI

---

## Objectives

The main objectives of Task 3 were:

- Create meaningful data visualizations using Python.
- Analyze sales and revenue trends.
- Identify top-performing products and countries.
- Analyze customer revenue contribution.
- Explore relationships between sales variables.
- Build an interactive Power BI dashboard.
- Present key business insights through visual storytelling.

---

## Dataset

The project uses the **Online Retail dataset** from the UCI Machine Learning Repository.

The dataset contains transactional information from an online retail business, including:

- Invoice Number
- Stock Code
- Product Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country
- Sales Amount

The dataset was cleaned and prepared during Task 1 of the internship.

### Dataset Source

UCI Machine Learning Repository — Online Retail

https://archive.ics.uci.edu/dataset/352/online+retail

The large cleaned dataset is not included in this repository to keep the repository lightweight.

---

# Python Data Visualization

Python was used to explore the dataset and generate detailed visualizations.

## Visualizations Created

### 1. Monthly Order Trend

Shows how the number of unique orders changed over time.

### 2. Monthly Revenue Trend

Shows the change in total revenue across the available months.

### 3. Top 10 Products by Revenue

Identifies the products generating the highest total revenue.

### 4. Top 10 Countries by Revenue

Compares revenue contribution across countries.

### 5. Top 10 Countries by Number of Orders

Shows which countries generated the highest number of orders.

### 6. Top 10 Customers by Revenue

Identifies customers with the highest total purchase value.

### 7. Quantity Distribution

Examines the distribution of quantities purchased across transactions.

### 8. Sales Amount Distribution

Shows the distribution of transaction-level sales amounts.

### 9. Quantity vs Sales Amount

Explores the relationship between quantity sold and transaction revenue.

### 10. Correlation Heatmap

Examines correlations between:

- Quantity
- Unit Price
- Sales Amount

---

# Power BI Dashboard

An interactive Power BI dashboard was developed to provide a consolidated view of e-commerce performance.

## Dashboard Features

The dashboard includes KPI cards and analytical visuals covering:

- Total Revenue
- Total Orders
- Units Sold
- Unique Customers
- Monthly Revenue Trends
- Monthly Order Trends
- Top Products
- Country-level Revenue
- Customer Revenue
- Quantity and Revenue relationships

The dashboard also includes interactive filters to allow users to explore the data by different dimensions such as:

- Year
- Month
- Country
- Product

---

## Dashboard Design

The Power BI dashboard was designed with a dark analytics-style theme to provide a clear and professional presentation of the results.

The dashboard combines:

- KPI cards
- Bar charts
- Line charts
- Donut charts
- Scatter plots
- Interactive slicers

---

# Key Insights

The analysis provided several observations about the Online Retail dataset:

- The United Kingdom accounts for the largest share of transaction activity.
- Certain products contribute significantly more revenue than others.
- Revenue and order activity vary considerably across countries.
- Customer revenue is concentrated among a smaller group of high-value customers.
- Quantity and Sales Amount show a positive relationship, although the relationship is not perfect.
- Monthly sales and order activity vary throughout the available period.

**Note:** December 2011 contains only partial data in the dataset, so comparisons involving that month should be interpreted carefully.

---

# Project Structure


ApexPlanet-Data-Analytics-Task-3/
│
├── notebooks/
│   └── Task_3_Visualizations.ipynb
│
├── dashboards/
│   └── Task_3_Ecommerce_Dashboard.pbix
│
├── visualizations/
│   ├── monthly_revenue.png
│   ├── monthly_orders.png
│   ├── top_10_products.png
│   ├── top_10_countries.png
│   ├── top_10_customers.png
│   └── correlation_heatmap.png
│
├── screenshots/
│   └── power_bi_dashboard.png
│
├── README.md
│
└── requirements.txt


---

Technologies Used

Technology	Purpose

Python	Data analysis and visualization
Pandas	Data manipulation
NumPy	Numerical operations
Matplotlib	Data visualization
Seaborn	Statistical visualization
Plotly	Interactive visualization
Power BI	Interactive dashboard development
Google Colab	Python development environment



---

How to Run the Python Notebook

1. Install the required libraries

pip install -r requirements.txt

2. Obtain the dataset

Download the Online Retail dataset from the UCI Machine Learning Repository.

3. Load the cleaned dataset

Place the cleaned CSV in the appropriate working directory.

4. Open the notebook

Open:

notebooks/Task_3_Visualizations.ipynb

The notebook contains the complete Python visualization workflow.


---

Power BI Dashboard

The Power BI dashboard is available as:

dashboards/Task_3_Ecommerce_Dashboard.pbix

Open the .pbix file using Microsoft Power BI Desktop.

If the dataset path has changed, update the data source from Power BI's data transformation/source settings.


---

Task 3 Deliverables

The following deliverables were completed for Task 3:

Python visualization notebook

Python-generated visualizations

Interactive Power BI dashboard

Power BI dashboard screenshot

Project documentation

GitHub repository



---

Internship

Program: 30-Day Data Analytics Internship
Organization: ApexPlanet
Task: Task 3 — Data Visualization & Dashboarding


---

Author

Debdut Nandy

B.Tech CSE (AI & ML) Student
Brainware University

GitHub: Deb124-source


---

Learning Outcome

Task 3 helped strengthen my understanding of how analytical results can be transformed into visual insights and interactive dashboards.

The project provided practical experience in combining Python-based data visualization with Power BI dashboard development to communicate patterns in business data more effectively.

### `requirements.txt`

For the repository, use this:

pandas
numpy
matplotlib
seaborn
plotly
