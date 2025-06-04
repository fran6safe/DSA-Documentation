# 🌱 What I Learned from the DSA Incubator Program

Participating in the **DSA Incubator** has been a powerful growth experience, especially in combining **data analysis**, **problem-solving**, and **technical tools**. Below is a detailed breakdown of the skills, tools, and knowledge I've gained:

---

## 🧰 Data Sources & Tools Used

### **Data Sources**
- **CSV Files**: Provided structured, downloadable datasets used for practice in cleaning and transformation.
- **Excel Spreadsheets**: Used for inputting raw data, performing calculations, creating dashboards, and conducting preliminary analysis.
- **SQL Server Databases**: Served as the primary relational database platform for querying and transforming data at scale.
- **Sample Business Cases**: Scenario-based datasets to simulate real-world business decision-making.

### **Tools & Technologies**
- **SQL Server** – Main tool for writing, testing, and executing SQL queries to explore, clean, and manipulate data.
- **Microsoft Excel**  – Used for visual analysis, dashboards, and advanced calculations.
- **Google Sheets** – Lightweight spreadsheet alternative for collaboration.
- **Canva / PowerPoint** – Tools for creating engaging and insightful data presentations.
- **Slack / WhatsApp / Email** – Platforms used for communication, solution sharing, and peer feedback.
- **GitHub** – Used to showcase finished projects, share SQL queries, and practice version control.

---

## 💻 Technical & Analytical Skills

### **SQL for Data Exploration and Manipulation**
- Crafted and optimized queries to extract actionable insights.
- Techniques included:
  - Joins: `INNER JOIN`, `LEFT JOIN`, `FULL OUTER JOIN`
  - Filtering: `WHERE`, `IN`, `NOT IN`, `LIKE`, `BETWEEN`
  - Aggregation: `COUNT`, `SUM`, `AVG`, `MIN`, `MAX`, `GROUP BY`, `HAVING`
  - Window functions: `ROW_NUMBER()`, `RANK()`, `DENSE_RANK()`, `OVER(PARTITION BY...)`
  - Subqueries and Common Table Expressions (CTEs)
- Example query:
```sql
SELECT
    CustomerID,
    COUNT(OrderID) AS TotalOrders,
    SUM(TotalAmount) AS TotalRevenue
FROM Orders
WHERE OrderDate BETWEEN '2024-01-01' AND '2024-03-31'
GROUP BY CustomerID
HAVING SUM(TotalAmount) > 1000
ORDER BY TotalRevenue DESC;
```
### **Microsoft Excel for Data Analysis** [(download here)](https://www.microsoft.com/en-us/microsoft-365/excel)

- Built responsive reports using:
  - Lookup formulas: `VLOOKUP`, `XLOOKUP`, `INDEX-MATCH`
  - Conditional logic: `IF`, `IFS`, `AND`, `OR`, `IFERROR`
  - Aggregations: `SUMIFS`, `COUNTIFS`, `AVERAGEIFS`
  - Text transformations: `LEFT`, `RIGHT`, `MID`, `TEXT`, `TRIM`
  - Named Ranges and Data Validation for controlled inputs
  - PivotTables for multidimensional analysis
  - Charts: column, pie, line, and combo charts

---

### **Exploratory Data Analysis (EDA)**

- Conducted descriptive statistics:
  - `COUNT`, `MEAN`, `MEDIAN`, `MODE`, `STDEV`
- Cleaned and validated datasets by identifying:
  - Nulls and missing values
  - Outliers and duplicates
  - Inconsistent text formatting and types
- Visual tools for EDA included:
  - Excel PivotCharts
  - Frequency tables
  - Bar and line graphs for trend analysis
- Example EDA Query:
```sql
SELECT
    Category,
    AVG(Sales) AS AvgSales,
    MIN(Sales) AS MinSales,
    MAX(Sales) AS MaxSales,
    COUNT(*) AS TransactionCount
FROM SalesData
GROUP BY Category
ORDER BY AvgSales DESC;
```

---

Thanks for reading!  
📢 Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/fran7safe) to see my professional journey, skills, and projects, or explore my SQL projects and dashboards on [GitHub](#).



