<h1 align="center">Retail Sales Analysis Project</h1>

<p align="center">
  <img src="https://github.com/Abdoo50/Retail-Sales-Analysis/blob/main/Dashboard.png">
</p>

### Project Overview

The goal of this project is to analyze retail sales data, identify key insights, and provide data-driven recommendations for improving sales performance and profitability.

---

### Steps Involved in the Project

1. **Data Cleansing using Power Query**
2. **Data Modeling**
3. **Dashboard Creation using Power BI**
4. **Interpretation and Presentation**

---

### 1. Data Cleansing using Power Query

Data cleansing is a crucial step to ensure that the data is accurate, consistent, and ready for analysis.

**Steps:**

- **Import Data:**
  - Load the raw data into Power Query.
  
- **Remove Duplicates:**
  - Identify and remove duplicate records to avoid skewed results.
  
- **Handle Missing Values:**
  - Fill in or remove missing values based on the context and significance.
  
- **Standardize Formats:**
  - Ensure consistent data formats (e.g., dates, currency).

- **Transform Data:**
  - Apply necessary transformations such as splitting columns, merging datasets, and calculating new metrics.

**Tools:**
- Microsoft Excel with Power Query
- Power BI for advanced transformations

---

### 2. Data Modeling

Data modeling involves structuring the cleaned data into a format suitable for analysis. 

**Steps:**

- **Create Fact and Dimension Tables:**
  - Fact Table: Contains transactional data (e.g., Orders).
  - Dimension Tables: Contain descriptive attributes related to the fact data (e.g., Date, Customer, Product).

- **Define Relationships:**
  - Establish relationships between fact and dimension tables to enable accurate data analysis.

**Example Tables:**
- **Fact Table: Orders**
  - Fields: Order ID, Order Date, Product ID, Customer ID, Quantity, Sales, Discount, Profit.

- **Dimension Tables:**
  - Date Table: Enables temporal analysis.
  - Customer Table: Facilitates customer segmentation.
  - Product Table: Allows product-level analysis.
  - Returns Table: Tracks returned orders for return rate analysis.

**Tools:**
- SQL Server
- Power BI Data Modeling

---

### 3. Dashboard Creation using Power BI

A dashboard is created to visualize the insights derived from the data.

**Steps:**

- **Import Data Model:**
  - Load the data model into Power BI.
  
- **Create Visualizations:**
  - Develop visual representations such as bar charts, line graphs, and pie charts to showcase key metrics and trends.

- **Design Dashboard:**
  - Arrange visualizations in a user-friendly layout for easy interpretation.
  - Include filters and slicers to enable interactive analysis.

**Key Metrics:**
- Total Sales
- Profit
- Sales Trends
- Regional Performance
- Product Category Breakdown

**Tools:**
- Power BI

---

### 4. Interpretation and Presentation

The final step involves interpreting the analysis and presenting the insights in a comprehensive manner.

**Steps:**

- **Analyze Insights:**
  - Identify key findings such as top-performing products, high-growth markets, and profitability variations.

- **Prepare Recommendations:**
  - Provide actionable recommendations based on the analysis to improve sales and profitability.

- **Create Presentation:**
  - Develop a presentation to communicate the findings and recommendations to stakeholders.

**Example Insights:**
- **Sales Performance by Country:**
  - The United States leads in total sales followed by Australia and France.
  - Emerging markets like China and India show significant growth potential.

- **Product Category Analysis:**
  - Technology products dominate total sales.
  - Office supplies have a higher profit ratio compared to technology.

- **Strategic Recommendations:**
  - Expand operations in high-growth markets.
  - Investigate underperforming categories to identify improvement areas.

**Tools:**
- Microsoft PowerPoint for creating the presentation.

---

### Conclusion

By following these steps, the Retail Sales Analysis project aims to provide a comprehensive understanding of sales performance and guide strategic decisions for future growth. The final presentation includes all key insights and actionable recommendations based on data analysis.
