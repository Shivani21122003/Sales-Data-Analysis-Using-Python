# Sales-Data-Analysis-Using-Python
# 📊 Sales Data Analysis Using Python

## 📌 Project Overview

This project focuses on analyzing sales data using Python to understand sales performance, product contribution, regional performance, and salesperson performance.

The project involves data cleaning, data manipulation, statistical analysis, and data visualization to convert raw sales data into meaningful business insights.

## 🎯 Project Objectives

- Analyze sales performance across different regions.
- Understand product-wise sales and quantity sold.
- Evaluate salesperson performance.
- Identify monthly sales trends.
- Analyze discount and profit margin patterns.
- Create visualizations to communicate business insights.

## 🛠️ Technologies & Libraries Used

- **Python** – Programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical and statistical calculations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **Plotly** – Interactive data visualization
- **Jupyter Notebook** – Development environment
- **Excel** – Source dataset

## 📂 Dataset Information

The project uses sales transaction data containing 90 records and 10 columns.

The dataset includes:

| Column | Description |
|---|---|
| Order Id | Unique order identifier |
| Date | Order date |
| Region | Sales region |
| Salesperson | Name of salesperson |
| Product | Product category |
| Quantity Sold | Number of units sold |
| Sales Amount | Sales amount |
| Discount (%) | Discount percentage |
| Profit Margin (%) | Profit margin percentage |
| Total Sales Amount | Total sales value |

## 🔍 Project Workflow

### 1. Data Loading and Exploration
- Imported the Excel dataset using Pandas.
- Displayed the first five and last five records.
- Checked dataset dimensions and column names.
- Examined data types using `df.dtypes`.
- Inspected dataset information using `df.info()`.

### 2. Data Cleaning and Preparation
- Identified missing values using `isnull().sum()`.
- Handled missing numerical values using mean imputation.
- Checked duplicate records.
- Explored duplicate removal using `drop_duplicates()`.
- Reviewed dataset statistics using `describe()`.

### 3. Data Analysis
Performed analysis using Pandas and NumPy:

- Mean, median, sum, minimum, and maximum.
- Standard deviation.
- Product-wise sales aggregation.
- Salesperson-wise sales analysis.
- Regional sales analysis.
- Monthly sales trends.
- Quantity sold by product.
- Profit margin comparison.
- Discount and sales relationship.
- Correlation analysis.

### 4. Data Visualization

Created different visualizations using Matplotlib, Seaborn, and Plotly.

**Matplotlib and Seaborn:**
- Bar charts
- Pie charts
- Line charts
- Histograms
- Scatter plots
- Correlation heatmaps
- Stacked bar charts

**Plotly:**
- Interactive regional sales charts
- Product-wise sales charts
- Monthly sales trend charts
- Salesperson performance charts
- Regional sales contribution
- Interactive scatter plots
- Correlation heatmaps

## 📈 Key Analysis Areas

1. Regional Sales Performance
2. Product-wise Sales Analysis
3. Monthly Sales Trends
4. Salesperson Performance
5. Quantity Sold by Product
6. Discount vs Total Sales Analysis
7. Average Profit Margin by Product
8. Region-wise Product Sales Comparison
9. Correlation Analysis of Sales Variables

## 📁 Project Structure

```text
Sales-Data-Analysis/
│
├── PROJECT.ipynb
├── Data.xlsx
└── README.md
```

## ▶️ How to Run This Project

1. Clone this repository:

```bash
git clone SALES-DATA-ANALYSIS-USING-PYTHON (https://github.com/Shivani21122003/Sales-Data-Analysis-Using-Python)
```

2. Navigate to the project folder:

```bash
cd Sales-Data-Analysis
```

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn plotly openpyxl jupyter
```

4. Open Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `PROJECT.ipynb` and run the cells.

**Note:** Keep `Data.xlsx` in the project folder or update the dataset file path in the notebook.

## 💡 Skills Demonstrated

- Python Programming
- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Data Manipulation using Pandas
- Numerical Analysis using NumPy
- Data Visualization
- Statistical Analysis
- Business Data Analysis
- Interactive Visualization

## 👩‍💻 Author

**Siraveni Shivani**

B.Tech Information Technology Graduate | Aspiring Data Analyst

- GitHub: https://github.com/Shivani21122003
- LinkedIn: https://linkedin.com/in/Shivani-da

---
⭐ If you find this project useful, feel free to explore the repository!
