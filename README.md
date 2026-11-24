# 📊 Superstore Sales Data Analysis

## 📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) of the Superstore Sales dataset using Python.

The objective is to analyze sales performance, profitability, product categories, regional performance, customer behavior, shipping methods, and discount impact to discover meaningful business insights.

The project uses Python libraries to clean, analyze, and visualize the dataset and generates an Excel report containing the analysis results.

## 🎯 Project Objectives

- Analyze overall sales and profit performance.
- Calculate important business KPIs.
- Identify the best-performing product categories.
- Analyze sales and profit by sub-category.
- Understand regional sales performance.
- Explore monthly and yearly sales trends.
- Identify top-selling and lowest-performing products.
- Analyze the relationship between discounts and profit.
- Understand customer purchasing patterns.
- Evaluate shipping methods and sales performance.
- Generate automatic business insights.
- Export analysis results into an Excel file.

## 📂 Dataset

**Dataset Name:** Superstore Dataset

**Source:** Kaggle

**Dataset Link:** https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

The dataset contains information about:
- Orders and customers
- Products and categories
- Sales and profit
- Quantity and discounts
- Order dates and shipping dates
- Regions and shipping methods

The dataset is downloaded automatically using KaggleHub.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming |
| Pandas | Data manipulation |
| NumPy | Numerical calculations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| KaggleHub | Dataset downloading |
| OpenPyXL | Excel file support |
| Google Colab | Development environment |

## 🔍 Project Workflow

### 1. Data Collection
- Download the Superstore dataset using KaggleHub.
- Load the dataset into Pandas.

### 2. Data Understanding
- Check dataset dimensions.
- Explore column names and data types.
- Identify missing values.
- Check duplicate records.
- Generate descriptive statistics.

### 3. Data Cleaning
- Remove duplicate records.
- Convert Order Date and Ship Date into datetime format.
- Convert numerical columns into appropriate data types.
- Create Year, Month, Month Name, and Year-Month features.

### 4. Key Performance Indicators (KPIs)
Calculate:
- Total Sales
- Total Profit
- Total Quantity
- Total Orders
- Total Customers
- Profit Margin

### 5. Sales and Profit Analysis
- Sales by category.
- Profit by category.
- Sub-category performance.
- Regional sales and profit analysis.

### 6. Time-Series Analysis
- Monthly sales trends.
- Monthly profit trends.
- Yearly sales and profit performance.

### 7. Product Analysis
- Top 10 products by sales.
- Lowest-performing products by profit.

### 8. Discount Analysis
- Explore the relationship between discounts and profitability.
- Identify the impact of discounts on profit.

### 9. Customer and Shipping Analysis
- Top 10 customers by sales.
- Customer sales and profit performance.
- Sales by shipping mode.

### 10. Automatic Business Insights
Generate insights about:
- Best-performing category.
- Most profitable category.
- Best-performing region.
- Most profitable sub-category.
- Best-selling product.
- Lowest-performing product.

### 11. Excel Report Generation
Export the cleaned dataset and analysis results into an Excel workbook named:

`Superstore_Analysis.xlsx`

## 📈 Visualizations

The project includes:
- Sales by Category
- Profit by Category
- Top 10 Sub-Categories by Profit
- Sales by Region
- Monthly Sales Trend
- Monthly Profit Trend
- Yearly Sales and Profit
- Top 10 Products by Sales
- Discount vs Profit
- Sales by Shipping Mode

## 💡 Business Insights and Recommendations

The analysis helps businesses:

- Focus on high-profit product categories.
- Identify products generating low or negative profits.
- Monitor excessive discounts.
- Improve regional sales planning.
- Understand customer purchasing behavior.
- Evaluate shipping performance.
- Make better data-driven business decisions.

## 📁 Project Structure

```text
Superstore-Data-Analysis/
│
├── Superstore_Data_Analysis_Colab.ipynb
│
├── Superstore_Analysis.xlsx
│
└── README.md
```

## ▶️ How to Run the Project

**Option 1: Google Colab**

1. Download the notebook from this repository.
2. Open [Google Colab](https://colab.research.google.com/).
3. Upload the `.ipynb` notebook.
4. Run all cells.
5. The dataset will be downloaded automatically through KaggleHub.
6. The Excel analysis report will be generated.

**Option 2: Local Jupyter Notebook**

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn kagglehub openpyxl jupyter
```

Clone the repository:

```bash
git clone https://github.com/shammaskattil24-byte/project_eda-1.git
```

Open Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook and run all cells.

## 📊 Final Outcome

This project demonstrates how Python can be used for data cleaning, exploratory data analysis, data visualization, business insight generation, and Excel report creation.

The final output is an Excel workbook containing cleaned data, KPIs, category analysis, regional analysis, product performance, customer analysis, and sales trends.

## 👨‍💻 Author

**Shammas Kattil**

GitHub: https://github.com/shammaskattil24-byte

---

⭐ If you find this project useful, don't forget to explore the repository!
