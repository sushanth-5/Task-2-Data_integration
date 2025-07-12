# Task-2-Data_integration

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: VAYUGANDLA VENKATA SIVA SAI SUSHANTH

*INTERN ID*: CITS0D731

*DOMAIN*: POWER BI

*DURATION*: 8 WEEKS

*MENTOR*: NEELA SANTOSH KUMAR

# 🔗 Power BI Internship – Task 2: Data Integration from Multiple Sources

## 📌 Internship Task Description

**Objective:**  
Integrate data from multiple sources — Excel and a simulated SQL table — and build a Power BI report demonstrating unified reporting with visualizations.

**Task Statement:**  
> Combine data from at least two different sources (e.g., Excel and SQL Server) to create a unified report. Deliver a Power BI report (`.pbix`) demonstrating data integration and visualizations.

This task is the second of four in my Power BI internship, focusing on Power BI's **data modeling and ETL (Extract, Transform, Load)** capabilities.

---

## 📁 Datasets Used

### 🔹 1. Excel Source:
- **File Name:** `Financial Sample (1).xlsx`
- **Source:** Microsoft sample data
- **Content:** Sales transactions — Product, Region, Profit, Sales, Date, Units Sold, Segment, etc.

### 🔹 2. Simulated SQL Table:
- **File Name:** `ProductInfo.xlsx` *(manually created to simulate a database table)*
- **Columns Included:**
  - Product ID
  - Product Name
  - Category
  - Supplier Name
  - Manufacturing Cost
  - Warranty Period
  - Launch Date
  - Rating
  - Stock Status
  - Product Type

This second file mimics what would be present in a normalized product database.

---

## 🧰 Tools & Platforms Used

| Tool/Platform         | Purpose                                      |
|-----------------------|----------------------------------------------|
| **Power BI Desktop**  | Core report development & modeling           |
| **Excel**             | Acted as both the real and simulated sources |
| **Power Query Editor**| Merging, joining, and cleaning data          |
| **Merge Queries**     | For integrating the tables using a join      |

---

## ⚙️ Steps Performed

1. **Loaded Both Files into Power BI:**
   - Used "Get Data" → Excel → Selected both Excel files

2. **Merged Datasets:**
   - Joined `Product` column from `Financial Sample (1).xlsx` with `Product Name` in `ProductInfo.xlsx`

3. **Data Cleaning:**
   - Removed nulls, standardized product naming, ensured no case mismatches

4. **Created Relationships:**
   - Modeled the two tables with a 1-to-many relationship

5. **Built Visuals Using Integrated Data:**
   - Combined views of `Sales` vs. `Product Category`
   - Created a table showing `Stock Status`, `Rating`, and `Warranty` for each product
   - Bar chart of `Sales` vs. `Supplier Name`

---

## 📊 Visuals Created

- **Product Category Sales Breakdown**
- **Sales by Supplier**

Each visual proves the effectiveness of merging distinct data sources for richer analysis.

---

## 📈 Insights Gained

- The merged data enabled **additional dimensions** (like `Category` and `Supplier`) not present in the main sales file.
- I could evaluate which **supplier's products** were generating the most profit.
- Products with longer warranty periods often correlated with **higher profit margins**.
- Stock status helped simulate **inventory planning visuals**.

---

## 🧠 Skills Demonstrated

- Data modeling using `Merge Queries` in Power Query
- Handling simulated multi-source scenarios
- Designing reports from combined datasets
- Transforming tabular data for enhanced dashboard storytelling

## OUTPUT of the task 2
