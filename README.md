Task 3 — SQL for Data Analysis
Key Findings
* Queried a five-table relational schema (Products, ProductSubcat, ProductCat, Sales-2017, Returns) to report revenue contribution, return volumes and product performance
* Built 17 analytical SQL queries, one reusable view and two performance indexes
* Identified top-revenue products, category-level sales contribution and month-wise return patterns
Objective
Use SQL queries to extract, analyse and generate business insights from an ecommerce database.
Dataset Used
* Ecommerce Sales Dataset — five related tables covering Products, Categories, Sub-Categories, Sales and Returns
Tools Used
* MySQL
* SQL
* CSV Datasets
Work Performed
* Imported and structured the ecommerce dataset into a relational database
* Wrote 17 analytical SQL queries using SELECT, WHERE, ORDER BY, GROUP BY, HAVING and LIMIT
* Applied aggregate functions including SUM(), AVG(), COUNT() and ROUND()
* Implemented INNER JOIN operations combining up to four tables in a single query
* Built a nested subquery inside a HAVING clause to isolate products performing above the overall average revenue
* Created a reusable view (view_Product) exposing product, subcategory, category, quantity and revenue
* Created two indexes on ProductKey to improve join performance on the Returns and Sales tables
* Used MONTH() date functions for monthly sales and return trend analysis
Key Analysis Performed
* Sales and revenue contribution by category and sub-category
* Top 3 and top 10 products by total revenue
* Products performing above the overall average revenue
* Return quantity analysis by product and category
* Average sales per sub-category
* Month-wise sales and return trends for 2017
Files Included
* SQL Script File (.sql)
* Ecommerce Dataset Files (.csv)
* Query Output Screenshots
* Project Documentation
Outcome
Developed SQL-based analytical solutions across a five-table schema to quantify category revenue contribution, isolate above-average performers using nested subqueries, and expose reusable reporting logic through views.
