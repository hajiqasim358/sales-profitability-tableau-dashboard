# Analyzing Sales Performance and Profitability Across Regions Using Interactive Tableau Dashboards

## Project Overview

This project presents an interactive Business Intelligence and data visualization system developed using the Global Superstore dataset. The objective of the project is to analyze sales performance, profitability trends, customer behavior, discount strategies, and regional market performance through an interactive Tableau dashboard.

The workflow combines Python based data preprocessing with Tableau driven visual analytics to transform raw transactional retail data into actionable business insights.

The project was also documented in the form of an IEEE style research paper and presentation.

---

## Objectives

* Analyze sales and profitability across global markets and regions
* Identify high performing and low performing product categories
* Study the impact of discount strategies on profit margins
* Build an interactive Tableau dashboard for exploratory analysis
* Support business decision making through visual analytics

---

## Dataset

Dataset Used:

Global Superstore Dataset

The dataset contains:

* Sales transactions
* Customer segments
* Product categories and sub categories
* Regional and market information
* Shipping methods and order priorities
* Profit and discount related metrics

Location:

```text
/data/Global_Superstore.csv
```

---

## Tools and Technologies

| Tool             | Purpose                                    |
| ---------------- | ------------------------------------------ |
| Python           | Data preprocessing and feature engineering |
| Pandas           | Data manipulation and cleaning             |
| Jupyter Notebook | Preprocessing workflow                     |
| Tableau          | Interactive dashboard development          |
| GitHub           | Project hosting and version control        |
| LaTeX            | IEEE paper preparation                     |

---

## Data Preprocessing

Before visualization, the dataset was cleaned and processed using Python in Jupyter Notebook.

Preprocessing steps included:

* Verifying missing values and dataset consistency
* Converting date columns into datetime format
* Creating derived fields such as Year and Profit Ratio
* Removing redundant attributes
* Preparing a clean schema for Tableau integration

Notebook Location:

```text
/notebooks/data_preprocessing.ipynb
```

---

## Dashboard Features

The Tableau dashboard includes:

* KPI Cards for Sales, Profit, Orders, and Discounts
* Time series sales trend analysis
* Category level profitability analysis
* Market and segment distribution donut charts
* Regional performance comparison
* Discount versus Profit scatter plot
* Interactive cross filtering and highlight actions

Dashboard File:

```text
/dashboard/tableau_dashboard.twbx
```

---

## Key Findings

### 1. Sales Growth Trend

Sales increased steadily from 2012 to 2015, with the Consumer segment contributing the highest sales volume.

### 2. Furniture Profitability Issue

The Furniture category generated strong sales revenue but frequently produced negative profit margins, indicating inefficiencies in pricing and discount strategies.

### 3. Impact of Discounts

The scatter plot analysis revealed a strong negative relationship between discount levels and profitability. Higher discounts were often associated with lower or negative profit margins.

### 4. Interactive Exploration

Dashboard Actions enabled dynamic filtering and linked analysis between charts, allowing rapid identification of regional and category level anomalies.

---

## Dashboard Preview

### Main Interactive Dashboard

![Dashboard Preview](dashboard/dashboard_screenshots/main_dashboard.png)

### Sales Trend Analysis

![Sales Trend](dashboard/dashboard_screenshots/sales_trend.png)

### Category Profitability Analysis

![Category Profit](dashboard/dashboard_screenshots/category_profit.png)

### Discount vs Profit Scatter Plot

![Scatter Plot](dashboard/dashboard_screenshots/scatter_plot.png)

---

## Project Structure

```text
sales-profitability-tableau-dashboard/
│
├── README.md
├── requirements.txt
│
├── data/
│   └── Global_Superstore.csv
│
├── notebooks/
│   └── data_preprocessing.ipynb
│
├── dashboard/
│   ├── tableau_dashboard.twbx
│   └── dashboard_screenshots/
│       ├── main_dashboard.png
│       ├── sales_trend.png
│       ├── category_profit.png
│       └── scatter_plot.png
│
├── paper/
│   ├── ieee_paper.pdf
│   ├── ieee_paper.tex
│   └── references.bib
│
├── presentation/
│   └── presentation.pdf
```

---

## How to Run the Project

### Python Notebook

1. Open Jupyter Notebook
2. Navigate to the notebooks folder
3. Run the preprocessing notebook

### Tableau Dashboard

1. Open Tableau Desktop
2. Open the .twbx file from the dashboard folder
3. Interact with filters and dashboard actions

---

## Research Paper

The project was also documented as an IEEE style research paper discussing:

* Data preprocessing methodology
* Dashboard design architecture
* Interactive analytics
* Results and findings
* Business insights


## Future Improvements

Potential future extensions include:

* Predictive sales forecasting
* Machine learning based customer segmentation
* Real time dashboard integration
* Automated reporting pipelines
* Advanced regional optimization analysis

---

## Author

Haji Qasim


www.linkedin.com/in/hajiqasim358

---

## License

This project is intended for academic and educational purposes.
