# E-Commerce-Orders-Data-Analysis
Analyzed e-commerce order data using Python, Pandas, NumPy, Matplotlib, and Seaborn. Performed data cleaning, missing value handling, product-wise revenue analysis, marketing channel analysis, and yearly order trend visualization.
# E-Commerce Orders Data Analysis

## Project Overview
E-Commerce Orders Data Analysis is a data analytics project developed using Python. The project analyzes e-commerce order data to understand product revenue, marketing channel performance, purchase trends, and shipping patterns.

Using Exploratory Data Analysis (EDA) and data visualization, this project transforms raw order data into meaningful insights that can support business decision-making.

## Objectives
- Analyze e-commerce order data.
- Clean and preprocess the dataset.
- Handle missing values and duplicate records.
- Analyze product-wise revenue.
- Understand orders by marketing channels.
- Identify weekly shipping patterns.
- Analyze yearly order volume trends.
- Visualize data using charts and graphs.

## Dataset
**Dataset file:** `orders-data.csv`

The dataset contains e-commerce order information, including product names, prices, marketing channels, purchase timestamps, and shipping timestamps.

### Important Columns

| Column Name | Description |
|---|---|
| `PRODUCT_NAME` | Name of the product |
| `USD_PRICE` | Product/order price in USD |
| `MARKETING_CHANNEL` | Marketing channel associated with the order |
| `PURCHASE_TS` | Purchase date and time |
| `SHIP_TS` | Shipping date and time |

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow

### 1. Data Loading
Load the CSV dataset using Pandas.

### 2. Exploratory Data Analysis
- Display the first five records.
- Check the number of rows and columns.
- Inspect column data types and non-null values.
- Generate descriptive statistics.
- Identify missing values.

### 3. Data Cleaning
- Remove unnecessary unnamed columns.
- Handle missing values in the `USD_PRICE` column using the mean.
- Identify and remove duplicate records.
- Convert purchase and shipping timestamps into datetime format.
- Handle invalid date values.

### 4. Data Analysis and Visualization

**Product-wise Revenue Analysis**

Calculate total revenue for each product and visualize the results using a bar chart.

**Orders by Marketing Channels**

Analyze the number of orders associated with each marketing channel.

**Weekly Shipping Patterns (2019–2021)**

Examine weekly shipping activity for the selected period using a line chart.

**Yearly Order Volume Trends**

Analyze the number of purchases recorded in each year.

**Orders Shipped by Year**

Compare annual shipping volumes using a bar chart.

## Key Business Questions
- Which products generate the highest recorded revenue?
- Which marketing channels have the most orders?
- How does shipping activity vary by week?
- How does purchase volume change over time?
- How many orders are shipped each year?

## Expected Outcomes
The analysis helps identify product revenue patterns, order distribution across marketing channels, and trends in purchasing and shipping activity.

Actual findings and numerical results can be added after running the analysis on the dataset.

## How to Run the Project

### Step 1: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 2: Prepare the Dataset

Place `orders-data.csv` in the project directory.

### Step 3: Open Jupyter Notebook

```bash
jupyter notebook
```

### Step 4: Run the Notebook

Open the project notebook and execute the cells in sequence.

## Project Structure

text
E-Commerce-Orders-Data-Analysis/
├── orders-data.csv
├── E-Commerce_Orders_Data_Analysis.ipynb
└── README.md


## Future Enhancements
- Analyze monthly and quarterly sales trends.
- Calculate average order value and revenue growth.
- Compare marketing channels by revenue.
- Analyze delivery duration using purchase and shipping dates.
- Build an interactive dashboard using Power BI or Tableau.
- Improve weekly trend analysis by comparing individual years.

## Author
Divya Rahane
