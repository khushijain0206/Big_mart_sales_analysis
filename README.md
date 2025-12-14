# Big_mart_sales_analysis
End-to-end data analysis project using Python (Pandas, NumPy) and Power BI. The project focuses on data cleaning, feature engineering, exploratory data analysis (EDA), and interactive dashboard creation to uncover sales trends across products and outlets.

# Tech Stack
- **Python:** Pandas, NumPy
- **Visualization:** Power BI
- **Environment:** Jupyter Notebook
- **Version Control:** Git & GitHub
- ---

## Dataset
- Source: Kaggle – Big Mart Sales Dataset  
- File used: `Train.csv`  
- Contains product, outlet, and sales information for retail analysis.

---

## Project Workflow

### 1. Data Extraction & Loading
- Loaded raw CSV data into Jupyter Notebook using Pandas.

### 2. Data Cleaning & Transformation
- Handled missing values in Item_Weight, Item_Visibility, and Outlet_Size.
- Standardized categorical values (Item_Fat_Content).
- Removed invalid and inconsistent entries.
- Created derived features such as:
  - Outlet_Age
  - Price_per_unit_weight
  - Visibility_Ratio

### 3. Exploratory Data Analysis (EDA)
- Analyzed sales distribution across:
  - Item categories
  - Outlet types and sizes
  - Pricing (MRP) ranges
- Identified top-performing products and outlets.
- Used statistical summaries and visualizations to uncover patterns.

### 4. Data Export
- Exported cleaned and transformed dataset for Power BI analysis.

### 5. Power BI Dashboard
- Built interactive dashboards with:
  - KPIs (Total Sales, Avg Sales per Outlet, Avg MRP)
  - Sales by Item Type and Outlet Type
  - Pricing vs Sales analysis
  - Product & Outlet Performance Analysis
- Added slicers for dynamic filtering and better insights.

---

