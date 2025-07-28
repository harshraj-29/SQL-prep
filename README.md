# 5-Day SQL Mastery Plan for Technical Interviews

## Day 1: Foundations & Basic Queries
**Time Allocation:** 2 hours (60 min theory + 60 min practice)

### Theory (60 minutes)
- **SELECT Statements & Basic Syntax**
  - **SELECT Statement:** [https://www.w3schools.com/sql/sql_select.asp](https://www.w3schools.com/sql/sql_select.asp)
    - Basic SELECT syntax and column selection
    - Selecting all columns with *
    - Selecting specific columns
  - **Column Aliasing (AS):** [https://www.w3schools.com/sql/sql_alias.asp](https://www.w3schools.com/sql/sql_alias.asp)
    - Creating readable column names
    - Using AS keyword for aliases
    - Table aliases for shorter references
  - **DISTINCT Keyword:** [https://www.w3schools.com/sql/sql_distinct.asp](https://www.w3schools.com/sql/sql_distinct.asp)
    - Removing duplicate rows
    - DISTINCT with multiple columns
    - Performance considerations

- **Filtering & Conditions**
  - **WHERE Clause:** [https://www.w3schools.com/sql/sql_where.asp](https://www.w3schools.com/sql/sql_where.asp)
    - Basic filtering conditions
    - Comparison operators (=, !=, <>, <, >, <=, >=)
    - Combining conditions with AND, OR, NOT
  - **LIKE Operator:** [https://www.w3schools.com/sql/sql_like.asp](https://www.w3schools.com/sql/sql_like.asp)
    - Pattern matching with wildcards
    - % (any sequence of characters)
    - _ (single character)
    - Case sensitivity considerations
  - **IN Operator:** [https://www.w3schools.com/sql/sql_in.asp](https://www.w3schools.com/sql/sql_in.asp)
    - Matching multiple values
    - NOT IN for exclusion
    - Using subqueries with IN
  - **BETWEEN Operator:** [https://www.w3schools.com/sql/sql_between.asp](https://www.w3schools.com/sql/sql_between.asp)
    - Range queries for numbers and dates
    - NOT BETWEEN for exclusion
    - Inclusive range behavior

- **Sorting & Limiting Results**
  - **ORDER BY:** [https://www.w3schools.com/sql/sql_orderby.asp](https://www.w3schools.com/sql/sql_orderby.asp)
    - Single and multiple column sorting
    - ASC (ascending) and DESC (descending)
    - NULL handling in sorting
  - **TOP/LIMIT:** [https://www.w3schools.com/sql/sql_top.asp](https://www.w3schools.com/sql/sql_top.asp)
    - Limiting result sets
    - Database-specific syntax differences
    - OFFSET for pagination

- **NULL Handling**
  - **NULL Values:** [https://www.w3schools.com/sql/sql_null_values.asp](https://www.w3schools.com/sql/sql_null_values.asp)
    - IS NULL and IS NOT NULL
    - NULL behavior in comparisons
    - COALESCE for NULL replacement

### LeetCode Questions (12 questions)
**Easy (7 questions):**
1. **595. Big Countries** - [https://leetcode.com/problems/big-countries/](https://leetcode.com/problems/big-countries/)
2. **584. Find Customer Referee** - [https://leetcode.com/problems/find-customer-referee/](https://leetcode.com/problems/find-customer-referee/)
3. **1757. Recyclable and Low Fat Products** - [https://leetcode.com/problems/recyclable-and-low-fat-products/](https://leetcode.com/problems/recyclable-and-low-fat-products/)
4. **1683. Invalid Tweets** - [https://leetcode.com/problems/invalid-tweets/](https://leetcode.com/problems/invalid-tweets/)
5. **1873. Calculate Special Bonus** - [https://leetcode.com/problems/calculate-special-bonus/](https://leetcode.com/problems/calculate-special-bonus/)
6. **1068. Product Sales Analysis I** - [https://leetcode.com/problems/product-sales-analysis-i/](https://leetcode.com/problems/product-sales-analysis-i/)
7. **1148. Article Views I** - [https://leetcode.com/problems/article-views-i/](https://leetcode.com/problems/article-views-i/)

**Medium (4 questions):**
8. **1393. Capital Gain/Loss** - [https://leetcode.com/problems/capital-gainloss/](https://leetcode.com/problems/capital-gainloss/)
9. **1398. Customers Who Bought Products A and B but Not C** - [https://leetcode.com/problems/customers-who-bought-products-a-and-b-but-not-c/](https://leetcode.com/problems/customers-who-bought-products-a-and-b-but-not-c/)
10. **1378. Replace Employee ID With The Unique Identifier** - [https://leetcode.com/problems/replace-employee-id-with-the-unique-identifier/](https://leetcode.com/problems/replace-employee-id-with-the-unique-identifier/)  
11. **1421. NPV Queries** - [https://leetcode.com/problems/npv-queries/](https://leetcode.com/problems/npv-queries/)

**Hard (1 question):**
12. **262. Trips and Users** - [https://leetcode.com/problems/trips-and-users/](https://leetcode.com/problems/trips-and-users/)

---

## Day 2: Aggregations & Grouping
**Time Allocation:** 2 hours (60 min theory + 60 min practice)

### Theory (60 minutes)
- **Aggregate Functions**
  - **COUNT Function:** [https://www.w3schools.com/sql/sql_count.asp](https://www.w3schools.com/sql/sql_count.asp)
    - COUNT(*) vs COUNT(column_name)
    - Counting non-null values
    - COUNT with DISTINCT
  - **SUM Function:** [https://www.w3schools.com/sql/sql_sum.asp](https://www.w3schools.com/sql/sql_sum.asp)
    - Summing numeric columns
    - Handling NULL values in SUM
    - SUM with conditions
  - **AVG Function:** [https://www.w3schools.com/sql/sql_avg.asp](https://www.w3schools.com/sql/sql_avg.asp)
    - Calculating averages
    - NULL value exclusion in AVG
    - Rounding average results
  - **MIN and MAX Functions:** [https://www.w3schools.com/sql/sql_min_max.asp](https://www.w3schools.com/sql/sql_min_max.asp)
    - Finding minimum and maximum values
    - Working with dates and strings
    - Multiple column MIN/MAX

- **Grouping Data**
  - **GROUP BY Clause:** [https://www.w3schools.com/sql/sql_groupby.asp](https://www.w3schools.com/sql/sql_groupby.asp)
    - Grouping by single columns
    - Grouping by multiple columns
    - GROUP BY with aggregate functions
    - Common grouping patterns and use cases
  - **HAVING Clause:** [https://www.w3schools.com/sql/sql_having.asp](https://www.w3schools.com/sql/sql_having.asp)
    - Filtering grouped results
    - HAVING vs WHERE differences
    - Using aggregate functions in HAVING
    - Complex HAVING conditions

### LeetCode Questions (12 questions)
**Easy (6 questions):**
1. **586. Customer Placing the Largest Number of Orders** - [https://leetcode.com/problems/customer-placing-the-largest-number-of-orders/](https://leetcode.com/problems/customer-placing-the-largest-number-of-orders/)
2. **511. Game Play Analysis I** - [https://leetcode.com/problems/game-play-analysis-i/](https://leetcode.com/problems/game-play-analysis-i/)
3. **1741. Find Total Time Spent by Each Employee** - [https://leetcode.com/problems/find-total-time-spent-by-each-employee/](https://leetcode.com/problems/find-total-time-spent-by-each-employee/)
4. **1693. Daily Leads and Partners** - [https://leetcode.com/problems/daily-leads-and-partners/](https://leetcode.com/problems/daily-leads-and-partners/)
5. **1407. Top Travellers** - [https://leetcode.com/problems/top-travellers/](https://leetcode.com/problems/top-travellers/)
6. **1729. Find Followers Count** - [https://leetcode.com/problems/find-followers-count/](https://leetcode.com/problems/find-followers-count/)

**Medium (5 questions):**
7. **1045. Customers Who Bought All Products** - [https://leetcode.com/problems/customers-who-bought-all-products/](https://leetcode.com/problems/customers-who-bought-all-products/)
8. **550. Game Play Analysis IV** - [https://leetcode.com/problems/game-play-analysis-iv/](https://leetcode.com/problems/game-play-analysis-iv/)
9. **1070. Product Sales Analysis III** - [https://leetcode.com/problems/product-sales-analysis-iii/](https://leetcode.com/problems/product-sales-analysis-iii/)
10. **1193. Monthly Transactions I** - [https://leetcode.com/problems/monthly-transactions-i/](https://leetcode.com/problems/monthly-transactions-i/)
11. **1321. Restaurant Growth** - [https://leetcode.com/problems/restaurant-growth/](https://leetcode.com/problems/restaurant-growth/)

**Hard (1 question):**
12. **1097. Game Play Analysis V** - [https://leetcode.com/problems/game-play-analysis-v/](https://leetcode.com/problems/game-play-analysis-v/)

---

## Day 3: Joins & Relationships
**Time Allocation:** 2 hours (70 min theory + 50 min practice)

### Theory (70 minutes)
- **Join Fundamentals**
  - **SQL Joins Introduction:** [https://www.w3schools.com/sql/sql_join.asp](https://www.w3schools.com/sql/sql_join.asp)
    - Understanding table relationships
    - Primary and foreign keys
    - Join syntax basics
  - **INNER JOIN:** [https://www.w3schools.com/sql/sql_join_inner.asp](https://www.w3schools.com/sql/sql_join_inner.asp)
    - Matching records in both tables
    - Multiple table INNER JOINs
    - JOIN conditions and performance
  - **LEFT JOIN:** [https://www.w3schools.com/sql/sql_join_left.asp](https://www.w3schools.com/sql/sql_join_left.asp)
    - Including all records from left table
    - Handling NULL values from right table
    - Use cases for LEFT JOINs
  - **RIGHT JOIN:** [https://www.w3schools.com/sql/sql_join_right.asp](https://www.w3schools.com/sql/sql_join_right.asp)
    - Including all records from right table
    - When to use RIGHT vs LEFT JOIN
  - **FULL OUTER JOIN:** [https://www.w3schools.com/sql/sql_join_full.asp](https://www.w3schools.com/sql/sql_join_full.asp)
    - Including all records from both tables
    - Handling NULL values from both sides
  - **SELF JOIN:** [https://www.w3schools.com/sql/sql_join_self.asp](https://www.w3schools.com/sql/sql_join_self.asp)
    - Joining a table with itself
    - Using table aliases in self joins
    - Hierarchical data queries

- **Advanced Join Concepts**
  - **Multiple Join Conditions**
    - Using AND/OR in JOIN conditions
    - Composite key joins
  - **Join vs WHERE Performance**
    - When to use JOIN conditions vs WHERE filters
    - Query optimization considerations

### LeetCode Questions (12 questions)
**Easy (5 questions):**
1. **1378. Replace Employee ID With The Unique Identifier** - [https://leetcode.com/problems/replace-employee-id-with-the-unique-identifier/](https://leetcode.com/problems/replace-employee-id-with-the-unique-identifier/)
2. **1068. Product Sales Analysis I** - [https://leetcode.com/problems/product-sales-analysis-i/](https://leetcode.com/problems/product-sales-analysis-i/)
3. **1581. Customer Who Visited but Did Not Make Any Transactions** - [https://leetcode.com/problems/customer-who-visited-but-did-not-make-any-transactions/](https://leetcode.com/problems/customer-who-visited-but-did-not-make-any-transactions/)
4. **1661. Average Time of Process per Machine** - [https://leetcode.com/problems/average-time-of-process-per-machine/](https://leetcode.com/problems/average-time-of-process-per-machine/)
5. **197. Rising Temperature** - [https://leetcode.com/problems/rising-temperature/](https://leetcode.com/problems/rising-temperature/)

**Medium (6 questions):**
6. **180. Consecutive Numbers** - [https://leetcode.com/problems/consecutive-numbers/](https://leetcode.com/problems/consecutive-numbers/)
7. **1158. Market Analysis I** - [https://leetcode.com/problems/market-analysis-i/](https://leetcode.com/problems/market-analysis-i/)
8. **1164. Product Price at a Given Date** - [https://leetcode.com/problems/product-price-at-a-given-date/](https://leetcode.com/problems/product-price-at-a-given-date/)
9. **1174. Immediate Food Delivery II** - [https://leetcode.com/problems/immediate-food-delivery-ii/](https://leetcode.com/problems/immediate-food-delivery-ii/)
10. **1205. Monthly Transactions II** - [https://leetcode.com/problems/monthly-transactions-ii/](https://leetcode.com/problems/monthly-transactions-ii/)
11. **1270. All People Report to the Given Manager** - [https://leetcode.com/problems/all-people-report-to-the-given-manager/](https://leetcode.com/problems/all-people-report-to-the-given-manager/)

**Hard (1 question):**
12. **569. Median Employee Salary** - [https://leetcode.com/problems/median-employee-salary/](https://leetcode.com/problems/median-employee-salary/)

---

## Day 4: Window Functions & Advanced Analytics
**Time Allocation:** 2 hours (75 min theory + 45 min practice)

### Theory (75 minutes)
- **Window Functions Fundamentals**
  - **Window Functions Overview:** [https://www.w3schools.com/sql/sql_window_functions.asp](https://www.w3schools.com/sql/sql_window_functions.asp)
    - Understanding window functions vs aggregate functions
    - OVER clause syntax and usage
    - Performance considerations

- **Ranking Functions**
  - **ROW_NUMBER():** [https://www.w3schools.com/sql/func_sqlserver_row_number.asp](https://www.w3schools.com/sql/func_sqlserver_row_number.asp)
    - Assigning unique sequential numbers
    - Use cases for pagination and deduplication
  - **RANK() and DENSE_RANK():**
    - Handling tied values differently
    - When to use RANK vs DENSE_RANK
    - Ranking with multiple criteria
  - **NTILE():**
    - Dividing data into equal buckets
    - Quartiles and percentile calculations

- **Analytical Functions**
  - **LAG() and LEAD():**
    - Accessing previous and next row values
    - Calculating differences between rows
    - Handling NULL values and default parameters
  - **FIRST_VALUE() and LAST_VALUE():**
    - Getting first and last values in partitions
    - Frame specification importance
    - Common pitfalls with LAST_VALUE

- **Window Frame Specifications**
  - **PARTITION BY:**
    - Dividing data into logical groups
    - Multiple column partitioning
  - **ORDER BY in Window Functions:**
    - Defining row order within partitions
    - Impact on frame boundaries
  - **ROWS vs RANGE:**
    - Physical vs logical boundaries
    - UNBOUNDED PRECEDING/FOLLOWING
    - CURRENT ROW specifications
  - **Frame Boundaries:**
    - Moving averages and running totals
    - Custom frame definitions

### LeetCode Questions (12 questions)
**Medium (9 questions):**
1. **178. Rank Scores** - [https://leetcode.com/problems/rank-scores/](https://leetcode.com/problems/rank-scores/)
2. **184. Department Highest Salary** - [https://leetcode.com/problems/department-highest-salary/](https://leetcode.com/problems/department-highest-salary/)
3. **534. Game Play Analysis III** - [https://leetcode.com/problems/game-play-analysis-iii/](https://leetcode.com/problems/game-play-analysis-iii/)
4. **1077. Project Employees III** - [https://leetcode.com/problems/project-employees-iii/](https://leetcode.com/problems/project-employees-iii/)
5. **1107. New Users Daily Count** - [https://leetcode.com/problems/new-users-daily-count/](https://leetcode.com/problems/new-users-daily-count/)
6. **1149. Article Views II** - [https://leetcode.com/problems/article-views-ii/](https://leetcode.com/problems/article-views-ii/)
7. **1194. Tournament Winners** - [https://leetcode.com/problems/tournament-winners/](https://leetcode.com/problems/tournament-winners/)
8. **1225. Report Contiguous Dates** - [https://leetcode.com/problems/report-contiguous-dates/](https://leetcode.com/problems/report-contiguous-dates/)
9. **1285. Find the Start and End Number of Continuous Ranges** - [https://leetcode.com/problems/find-the-start-and-end-number-of-continuous-ranges/](https://leetcode.com/problems/find-the-start-and-end-number-of-continuous-ranges/)

**Hard (3 questions):**
10. **185. Department Top Three Salaries** - [https://leetcode.com/problems/department-top-three-salaries/](https://leetcode.com/problems/department-top-three-salaries/)
11. **615. Average Salary: Departments VS Company** - [https://leetcode.com/problems/average-salary-departments-vs-company/](https://leetcode.com/problems/average-salary-departments-vs-company/)
12. **1412. Find the Quiet Students in All Exams** - [https://leetcode.com/problems/find-the-quiet-students-in-all-exams/](https://leetcode.com/problems/find-the-quiet-students-in-all-exams/)

---

## Day 5: Complex Queries & Interview Patterns
**Time Allocation:** 2 hours (70 min theory + 50 min practice)

### Theory (70 minutes)
- **Subqueries**
  - **Subqueries:** [https://www.w3schools.com/sql/sql_subqueries.asp](https://www.w3schools.com/sql/sql_subqueries.asp)
    - Single-row vs multi-row subqueries
    - Scalar subqueries in SELECT
    - Subqueries in WHERE clause
  - **EXISTS Operator:** [https://www.w3schools.com/sql/sql_exists.asp](https://www.w3schools.com/sql/sql_exists.asp)
    - EXISTS vs IN performance
    - NOT EXISTS for exclusion queries
    - Correlated subqueries with EXISTS

- **Common Table Expressions (CTEs)**
  - **WITH Clause:**
    - Creating temporary named result sets
    - Multiple CTEs in single query
    - CTE vs subquery performance
  - **Recursive CTEs:**
    - Hierarchical data processing
    - Tree traversal patterns
    - Recursive termination conditions

- **Conditional Logic**
  - **CASE Statement:** [https://www.w3schools.com/sql/sql_case.asp](https://www.w3schools.com/sql/sql_case.asp)
    - Simple CASE expressions
    - Searched CASE expressions
    - CASE in SELECT, WHERE, and ORDER BY
    - Nested CASE statements

- **Set Operations**
  - **UNION:** [https://www.w3schools.com/sql/sql_union.asp](https://www.w3schools.com/sql/sql_union.asp)
    - UNION vs UNION ALL
    - Column compatibility requirements
    - Performance considerations
  - **INTERSECT and EXCEPT:**
    - Finding common records
    - Finding differences between tables

- **String Functions**
  - **String Functions:** [https://www.w3schools.com/sql/sql_ref_sqlserver.asp](https://www.w3schools.com/sql/sql_ref_sqlserver.asp)
    - CONCAT, SUBSTRING, LENGTH/LEN
    - UPPER, LOWER, TRIM
    - REPLACE, CHARINDEX/POSITION
    - String pattern matching

- **Date/Time Functions**
  - **Date Functions:** [https://www.w3schools.com/sql/sql_dates.asp](https://www.w3schools.com/sql/sql_dates.asp)
    - DATE, DATEPART, DATEDIFF
    - DATEADD for date arithmetic
    - Current date/time functions
    - Date formatting and conversion

### LeetCode Questions (12 questions)
**Medium (8 questions):**
1. **177. Nth Highest Salary** - [https://leetcode.com/problems/nth-highest-salary/](https://leetcode.com/problems/nth-highest-salary/)
2. **1045. Customers Who Bought All Products** - [https://leetcode.com/problems/customers-who-bought-all-products/](https://leetcode.com/problems/customers-who-bought-all-products/)
3. **1098. Unpopular Books** - [https://leetcode.com/problems/unpopular-books/](https://leetcode.com/problems/unpopular-books/)
4. **1173. Immediate Food Delivery I** - [https://leetcode.com/problems/immediate-food-delivery-i/](https://leetcode.com/problems/immediate-food-delivery-i/)
5. **1212. Team Scores in Football Tournament** - [https://leetcode.com/problems/team-scores-in-football-tournament/](https://leetcode.com/problems/team-scores-in-football-tournament/)
6. **1251. Average Selling Price** - [https://leetcode.com/problems/average-selling-price/](https://leetcode.com/problems/average-selling-price/)
7. **1294. Weather Type in Each Country** - [https://leetcode.com/problems/weather-type-in-each-country/](https://leetcode.com/problems/weather-type-in-each-country/)
8. **1369. Get the Second Most Recent Activity** - [https://leetcode.com/problems/get-the-second-most-recent-activity/](https://leetcode.com/problems/get-the-second-most-recent-activity/)

**Hard (4 questions):**
9. **262. Trips and Users** - [https://leetcode.com/problems/trips-and-users/](https://leetcode.com/problems/trips-and-users/)
10. **601. Human Traffic of Stadium** - [https://leetcode.com/problems/human-traffic-of-stadium/](https://leetcode.com/problems/human-traffic-of-stadium/)
11. **1596. The Most Frequently Ordered Products for Each Customer** - [https://leetcode.com/problems/the-most-frequently-ordered-products-for-each-customer/](https://leetcode.com/problems/the-most-frequently-ordered-products-for-each-customer/)
12. **1892. Page Recommendations II** - [https://leetcode.com/problems/page-recommendations-ii/](https://leetcode.com/problems/page-recommendations-ii/)

## Daily Practice Structure
1. **Start with theory** (60-75 minutes) - Deep dive into concepts with W3Schools links
2. **Begin with easy questions** to build confidence (20-25 minutes)
3. **Progress to medium questions** for core competency (25-30 minutes)
4. **Tackle hard questions** for interview excellence (10-15 minutes)
5. **Review and understand** all solutions thoroughly
## Key Success Tips
- Practice writing queries from scratch without IDE help
- Understand execution plans and query optimization
- Master common interview patterns (ranking, running totals, finding duplicates)
- Focus on edge cases and NULL handling
- Practice explaining your approach verbally
- Time yourself - aim for 10-15 minutes per medium question

## Interview-Specific Focus Areas
- **Data cleaning** and transformation queries
- **Business metrics** calculations
- **User behavior** analysis patterns
- **Financial** calculations and reporting
- **Performance optimization** techniques

## W3Schools Complete SQL Reference
- **Complete SQL Reference:** [https://www.w3schools.com/sql/default.asp](https://www.w3schools.com/sql/default.asp)
- **SQL Functions Reference:** [https://www.w3schools.com/sql/sql_ref_sqlserver.asp](https://www.w3schools.com/sql/sql_ref_sqlserver.asp)
- **SQL Quiz for Practice:** [https://www.w3schools.com/sql/sql_quiz.asp](https://www.w3schools.com/sql/sql_quiz.asp)
