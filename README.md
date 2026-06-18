# Power BI Assignment 1 – Data Transformation & Data Modeling

## Project Overview
This project focuses on data preparation, transformation, integration, and modeling using Power BI and Power Query Editor. The objective is to clean and transform E-commerce sales data, create meaningful business logic, and build a structured data model for analysis and reporting.

## Dataset Information

### 1. List of Orders
- Order ID
- Order Date
- Customer Name
- City
- State
- Category
- Amount
- Profit

### 2. Order Details
- Order ID
- Category
- Sub-Category
- Quantity
- Amount
- Profit

### 3. Sales Target
- Category
- Month of Order Date
- Target

## Tasks Performed

### Data Import & Transformation
- Imported all datasets into Power BI.
- Loaded data into Power Query Editor.
- Limited List of Orders to the first 500 rows.
- Converted Order Date to Date data type.
- Converted Amount and Target to Fixed Decimal Number.
- Formatted Customer Name using Proper Case.

### Column Creation
- Created a Location column by merging City and State.
- Created Profit Margin column using:
  
  Profit Margin = Profit / Amount

- Added Profit Status column:
  - Profit > 0 → Profit
  - Profit = 0 → Break-Even
  - Profit < 0 → Loss

### Data Integration
- Merged List of Orders and Order Details using Order ID.
- Created a consolidated table named Orders Data.

### Data Quality Management
- Identified and handled missing values.
- Reviewed duplicate records and applied suitable business logic.

### Data Analysis
- Sorted Orders Data by Order Date (Descending).
- Filtered records for state-level analysis.
- Performed aggregations:
  - Count of Order ID
  - Average Profit by Category
  - Total Amount by Sub-Category
  - Total Target by Month

### Data Modeling
- Created relationship between:
  - List of Orders ↔ Order Details (Order ID)
  - Order Details ↔ Sales Target (Category)
- Verified active relationships using Manage Relationships.

## Tools Used
- Power BI Desktop
- Power Query Editor

## Skills Demonstrated
- Data Preparation
- Data Cleaning
- Data Transformation
- Data Integration
- Data Aggregation
- Data Modeling
- Business Logic Implementation

## Project Outcome
Developed a clean and structured Power BI data model by transforming, integrating, and validating E-commerce sales data. The final model supports efficient analysis, reporting, and business decision-making.

## Author
Hishaam J
