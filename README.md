# Sales_Finance_Report_for_AtliQ_Hardware



### Objective:
AtliQ, a hardware company selling products like PCs, mice, and printers, provides data for building comprehensive sales and financial reports. The data comprises over 1.5 million records from two customer segments: Brick & Mortar (e.g., Croma, Best Buy) and E-commerce (e.g., Amazon, Flipkart).

### Key Reports:

###  Sales Report :
- **Customer Performance Report**
- **Market Performance Report**
- **Top 10 Products**
- **Division Level Breakdown**
- **Top & Bottom 5 Products**
- **New Products - 2021**
- **Top 5 Countries**

### Financial Reports:
- **Profit & Loss (P&L) Yearly**
- **P&L Monthly**
- **P&L by Market**
- **Gross Margin (GM%) Quarterly**

### Steps Involved:
1. **ETL (Extract, Transform, Load)**: 
   - Loaded CSV files into Power Query.
   - Cleaned and prepared the data by removing duplicates, correcting errors, ensuring unique columns, and eliminating missing values.
   - Data was loaded into Power Pivot.

2. **Data Modeling**:
   - Established a star schema connecting all tables.
   - Created a `dim_date` table with separate columns for date, month, year, and fiscal year (Sept-Aug).
   
3. **Pivot Table and Power Pivot**:
   - Integrated the data model with Pivot Tables for efficient analysis.
   - Utilized Power Pivot for custom measures and calculations, leveraging Power Query for streamlined data transformation.

4. **DAX (Data Analysis Expression)**:
   - Created 10+ new measures (e.g., Net Sales, Gross Margin, GM%, COGS).
   - Added columns for quarterly calculations based on fiscal year using DAX functions like `CALCULATE`, `SUM`, `DIVIDE`, and `FORMAT`.

5. **Conditional Formatting**:
   - Applied conditional formatting to highlight key data and trends, improving the presentation and readability for decision-making.

### Key Insights:
- **Top Market**: India led with the highest net sales of $161.3 million, while Sweden had the lowest at $1.8 million.
- **Best-Selling Product**: AQ Master Wired X1 MS sold 4.2 million units, whereas AQ Home Allin1 Gen2 had the lowest sales at 8.8k units.
- **Festive Surge**: Significant sales and profit growth during October-December in India.
- **Top Customers**: Amazon, AtliQ Exclusive, and AtliQ e-store were the top contributors to net sales.
- **New Product Success**: 16 new products launched in 2021, with AQ Qwerty leading at 22 million units sold.

### Finance Knowledge:
A P&L statement provides a detailed snapshot of the company’s financial health over a period, reflecting metrics such as:
- **Net Sales**
- **Cost of Goods Sold (COGS)**
- **Gross Margin**
- **Gross Margin % (GM%)**

