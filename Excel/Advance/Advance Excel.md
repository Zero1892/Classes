1. **PivotTables:**

PivotTables are powerful tools for summarizing and analyzing data in Excel.

- **Creating a PivotTable:**

  1. Select your data range.
  2. Go to the "Insert" tab and click on "PivotTable."
  3. Choose where you want to place the PivotTable and define the fields.
- **PivotTable Options:**

  1. Use the Field List to arrange data.
  2. Drag fields to Rows, Columns, Values, or Filters.
  3. You can apply functions like Sum, Count, Average to Values.

### 2. **Formulas and Functions:**

- **Array Formulas:**
  Array formulas perform multiple calculations on one or more items in an array.

  - Example: Use Ctrl + Shift + Enter for array formulas.
  - `{=SUM(A1:A5*B1:B5)}`
- **Advanced Functions:**

  - **INDEX and MATCH:**
    - `=INDEX(ReturnRange, MATCH(LookupValue, LookupRange, 0))`
  - **VLOOKUP and HLOOKUP:**
    - `=VLOOKUP(lookup_value, table_array, col_index_num, [range_lookup])`

### 3. **Data Validation:**

- Use Data Validation to control what data can be entered into a cell.
  - Specify a list, range, or formula to limit data input.
  - Found in the "Data" tab.

### 4. **Conditional Formatting:**

- Apply formatting based on certain criteria.
  - Highlight cells, add data bars, color scales, or icon sets.
  - Found in the "Home" tab.

### 5. **Power Query:**

- Power Query allows you to import, transform, and combine data from various sources.
- Found in the "Data" tab.

### 6. **Power Pivot:**

- Power Pivot is an Excel add-in that enables you to analyze large datasets.
- It's great for working with multiple tables and creating relationships.

### 7. **Advanced Charting:**

- Create combo charts, waterfall charts, and other advanced chart types.
- Add trendlines, error bars, and annotations.

### 8. **Macros and VBA:**

- Automate repetitive tasks using Macros.
- Write VBA (Visual Basic for Applications) code to create custom functions and automate complex tasks.

### 9. **Dynamic Arrays (Excel 365):**

- Take advantage of the new dynamic array functions like `FILTER`, `SORT`, and `UNIQUE`.

### 10. **Data Analysis Tools:**

- Use the built-in Data Analysis ToolPak for statistical analysis.
- Found in the "Data" tab.

### 11. **Excel Shortcuts:**

- Learn keyboard shortcuts to speed up your work.

### 12. **Solver:**

- Solver is an Excel add-in that helps you find the optimal value in a cell by changing other cells.

### 13. **Excel Tables:**

- Convert your data into Excel Tables for better data management.

### 14. **Protecting and Securing Data:**

- Password protect sheets or workbooks.
- Set permissions and restrict access.

### 15. **Scenario Manager:**

- Manage and analyze multiple scenarios with different input values.

### 16. **Excel Dashboards:**

- Create interactive and visually appealing dashboards.

### 17. **Collaboration:**

- Use Excel's collaboration features, such as sharing workbooks and tracking changes.

### Practice Table 1: Sales Data

| Product   | Region | Sales ($) | Quantity Sold |
| --------- | ------ | --------- | ------------- |
| Product A | North  | 5000      | 100           |
| Product B | South  | 8000      | 120           |
| Product C | East   | 6500      | 90            |
| Product A | West   | 7000      | 110           |
| Product B | North  | 5500      | 80            |
| Product C | South  | 9000      | 130           |

#### Tasks:

1. Create a PivotTable to summarize total sales by product and region.
2. Use VLOOKUP to find the sales for "Product A" in the "West" region.
3. Apply conditional formatting to highlight cells with sales over $7000.
4. Calculate the average quantity sold for each product.

### Practice Table 2: Expense Tracking

| Date       | Category       | Amount ($) |
| ---------- | -------------- | ---------- |
| 2023-01-01 | Utilities      | 150        |
| 2023-01-05 | Groceries      | 200        |
| 2023-01-10 | Rent           | 1200       |
| 2023-01-15 | Dining Out     | 100        |
| 2023-01-20 | Entertainment  | 50         |
| 2023-01-25 | Transportation | 75         |

#### Tasks:

1. Create a stacked bar chart to visualize expenses by category.
2. Use the SUMIFS function to calculate total expenses for "Groceries" in January.
3. Implement data validation for the "Category" column using a predefined list.
4. Create a summary table showing the total expenses for each category.

### Project: Budget Planning

Create a budget planning table to track income and expenses for a month.

| Category       | Planned Amount ($) | Actual Amount ($) |
| -------------- | -------------------| - |
| Income         |                    |   |
| Salary         |                    |   |
| Investments    |                    |   |
| Expenses       |                    |   |
| Rent           |                    |   |
| Utilities      |                    |   |
| Groceries      |                    |   |
| Transportation |                    |   |
| Entertainment  |                    |   |
| Miscellaneous  |                    |   |
| Savings        |                    |   |

#### Tasks:

1. Use data validation to create drop-down lists for the "Category" column.
2. Set up formulas to calculate the total planned and actual amounts for income and expenses.
3. Create a bar chart to visualize the budget distribution.
4. Implement conditional formatting to highlight budget items where the actual amount exceeds the planned amount.

### Project: Sales Analysis

Create a sales analysis table to evaluate the performance of different products over multiple months.

| Month | Product A | Product B | Product C |
| ----- | --------- | --------- | --------- |
| Jan   | 5000      | 8000      | 6500      |
| Feb   | 6000      | 7500      | 7000      |
| Mar   | 5500      | 9000      | 6800      |
| Apr   | 7000      | 8200      | 7200      |
| May   | 7500      | 7800      | 6900      |

#### Tasks:

1. Calculate the total sales for each product across all months.
2. Use conditional formatting to highlight the month with the highest sales for each product.
3. Create a line chart to visualize the sales trends for each product.
4. Calculate the average monthly sales for each product.

### Advanced Project: Financial Portfolio Tracker

Build a financial portfolio tracker to monitor the performance of different investments.

| Investment | Purchase Date | Purchase Price ($) | Current Value ($) | Quantity |
| ---------------- | ------------- | ---------------------------------------- | -------- | --- |
| Stock A          | 2022-01-01    | 50                                       | 60       | 100 |
| ETF B            | 2022-03-15    | 120                                      | 140      | 50  |
| Cryptocurrency C | 2022-05-20    | 2000                                     | 2500     | 2   |

#### Tasks:

1. Calculate the percentage change in value for each investment.
2. Use conditional formatting to highlight investments that have gained over 10%.
3. Create a pie chart to visualize the distribution of the portfolio by investment.
4. Implement data validation for the "Investment" column using a predefined list.

### Advanced Project: Employee Performance Tracker

Develop an employee performance tracker to evaluate key performance indicators (KPIs).

| Employee   | Sales ($) | Customer Satisfaction (%) | Projects Completed | Absences |
| ---------- | --------- | ------------------------- | ------------------ | -------- |
| Employee A | 8000      | 95                        | 5                  | 2        |
| Employee B | 7000      | 90                        | 4                  | 1        |
| Employee C | 9000      | 96                        | 6                  | 0        |

#### Tasks:

1. Calculate the average sales, customer satisfaction, and projects completed.
2. Use conditional formatting to highlight employees with exceptional performance (e.g., sales over $8000 or satisfaction over 95%).
3. Create a radar chart to visualize the overall performance of each employee.
4. Implement data validation for the "Employee" column using a predefined list.

### Advanced Project: Data Cleaning and Analysis

Work on a project involving data cleaning and in-depth analysis.

#### Dataset: Customer Data

| Customer ID | First Name | Last Name | Email                 | Phone    | Total Purchases ($) |
| ----------- | ---------- | --------- | --------------------- | -------- | ------------------- |
| 001         | John       | Doe       | john.doe@email.com    | 555-1234 | 5000                |
| 002         | Jane       | Smith     | jane.smith@email.com  | 555-5678 | 8000                |
| 003         | Bob        | Johnson   | bob.johnson@email.com | 555-8765 | 6500                |
| ...         | ...        | ...       | ...                   | ...      | ...                 |

#### Tasks:

1. Clean the data: Remove duplicates, handle missing values, and format phone numbers.
2. Analyze customer demographics: Calculate the average age based on birthdates (if available).
3. Segment customers: Create customer segments based on their total purchases (e.g., high spenders, regular customers).
4. Perform a correlation analysis: Determine if there's a correlation between total purchases and customer satisfaction (assume an additional dataset).

### Advanced Project: Financial Modeling

Build a financial model to analyze and forecast business performance.

#### Dataset: Monthly Financial Data

| Month | Revenue ($) | Expenses ($) | Profit ($) |
| ----- | ---------------------------- | ---------- | ---- |
| Jan   | 10000                        | 8000       | 2000 |
| Feb   | 12000                        | 9000       | 3000 |
| Mar   | 11000                        | 8500       | 2500 |
| ...   | ...                          | ...        | ...  |

#### Tasks:

1. Create a dynamic financial statement: Use formulas to calculate net profit, profit margin, and other key financial metrics.
2. Build a scenario analysis: Evaluate the impact of different revenue and expense scenarios on profit.
3. Create a cash flow projection: Use Excel functions to forecast cash flow based on historical data.
4. Visualize financial trends: Develop line charts and trendlines to highlight patterns in revenue, expenses, and profit over time.

### Advanced Project: Interactive Dashboard

Build an interactive dashboard that provides a comprehensive view of a business's key performance indicators.

#### Components:

1. **Summary Metrics:**

   - Display total revenue, expenses, and profit.
   - Use sparklines to show trends in key metrics.
2. **Monthly Performance:**

   - Create a dynamic chart that allows users to select a specific month and view detailed performance metrics.
3. **Customer Segment Analysis:**

   - Integrate customer segmentation analysis.
   - Use slicers or dropdown lists for users to explore different customer segments.
4. **Scenario Analysis:**

   - Include a section for scenario analysis with sliders or input cells to adjust key assumptions.
5. **Financial Statements:**

   - Embed dynamic financial statements that update based on user inputs.

Building an interactive dashboard combines various advanced Excel skills, including data visualization, dynamic charts, and scenario analysis.

### Advanced Project: Project Management Tracker

Create a project management tracker to monitor and analyze the progress of different projects.

#### Dataset: Project Data

| Project ID | Project Name       | Start Date | End Date   | Budget ($) | Actual Cost ($) | Status |             
| ---------- | ------------------ | ---------- | ---------- | ------------------------------ | ------ | ----------- |
| P001       | Marketing Campaign | 2022-03-01 | 2022-05-01 | 20000                          | 18000  | Completed   |
| P002       | Product Launch     | 2022-06-01 | 2022-09-01 | 50000                          | 48000  | In Progress |
| P003       | Website Redesign   | 2022-04-15 | 2022-08-15 | 25000                          | 22000  | Delayed     |

#### Tasks:

1. Calculate the project duration for each project.
2. Use conditional formatting to highlight projects that are behind schedule or over budget.
3. Create a Gantt chart to visualize project timelines.
4. Implement data validation for the "Status" column using a predefined list.

### Advanced Project: Sales Forecasting

Develop a sales forecasting model using historical sales data.

#### Dataset: Historical Sales Data

| Date       | Sales ($) |
| ---------- | --------- |
| 2022-01-01 | 5000      |
| 2022-02-01 | 5500      |
| 2022-03-01 | 6000      |
| ...        | ...       |

#### Tasks:

1. Use moving averages or exponential smoothing to create a sales forecast.
2. Visualize the historical sales data along with the forecast using a line chart.
3. Implement a sensitivity analysis to assess the impact of changing assumptions on the forecast.
4. Utilize data validation to allow users to input different forecast scenarios.

### Advanced Project: Supply Chain Optimization

Build a supply chain optimization model to minimize costs and improve efficiency.

#### Dataset: Supply Chain Data

| Product   | Supplier   | Lead Time (days) | Cost per Unit ($) | Order Quantity |
| --------- | ---------- | ---------------- | ----------------- | -------------- |
| Product A | Supplier 1 | 10               | 8                 | 200            |
| Product B | Supplier 2 | 15               | 12                | 150            |
| Product C | Supplier 3 | 8                | 10                | 180            |

#### Tasks:

1. Calculate the total cost of ordering and holding inventory for each product.
2. Use Solver to find the optimal order quantity for each product.
3. Create a sensitivity analysis to explore how changes in lead time and cost per unit impact total costs.
4. Build a dashboard to visualize the optimized supply chain model.

### Advanced Project: Human Resources Analytics

Develop an HR analytics dashboard to analyze employee data and trends.

#### Dataset: Employee Data

| Employee ID | Name        | Department | Position          | Salary ($) | Years of Service |
| ----------- | ----------- | ---------- | ----------------- | ---------- | ---------------- |
| E001        | John Doe    | Sales      | Sales Manager     | 80000      | 5                |
| E002        | Jane Smith  | Marketing  | Marketing Lead    | 75000      | 3                |
| E003        | Bob Johnson | Finance    | Financial Analyst | 70000      | 4                |

#### Tasks:

1. Calculate the average salary and years of service for each department.
2. Use data validation to create dropdown lists for the "Department" and "Position" columns.
3. Visualize employee distribution across departments using a pie chart.
4. Implement conditional formatting to highlight employees with significant years of service or high salaries.

### Advanced Project: Real Estate Investment Analysis

Build a real estate investment analysis model to assess the profitability of potential property investments.

#### Dataset: Property Data

| Property ID | Property Type | Purchase Price ($) | Monthly Rent ($) | Operating Expenses ($) | Vacancy Rate (%) |   
| ----------- | ------------- | --------------------------------------- | ---------------------- | ---------------- | - |
| P001        | Apartment     | 500000                                  | 2500                   | 800              | 5 |
| P002        | Commercial    | 800000                                  | 5000                   | 1200             | 8 |
| P003        | Residential   | 350000                                  | 2000                   | 600              | 3 |

#### Tasks:

1. Calculate the net operating income (NOI) for each property.
2. Use data validation to allow users to input different assumptions (e.g., vacancy rate, operating expenses).
3. Implement conditional formatting to highlight properties with high profitability.
4. Create a dynamic chart to visualize the potential return on investment for each property.

### Advanced Project: Customer Segmentation and Lifetime Value

Perform advanced customer analysis by segmenting customers and calculating their lifetime value.

#### Dataset: Customer Transactions

| Customer ID | Date       | Purchase Amount ($) |
| ----------- | ---------- | ------------------- |
| C001        | 2022-01-01 | 1000                |
| C002        | 2022-01-05 | 800                 |
| C003        | 2022-02-10 | 1200                |
| ...         | ...        | ...                 |

#### Tasks:

1. Segment customers based on their transaction history (e.g., high spenders, frequent buyers).
2. Calculate the customer lifetime value (CLV) for each segment.
3. Visualize customer segments using a bar chart or pie chart.
4. Use PivotTables to analyze trends in customer behavior over time.

These advanced projects offer a deeper dive into specific domains, such as HR analytics, real estate investment analysis, and customer segmentation. As you work on these projects, you'll gain not only advanced Excel skills but also a broader understanding of how data analysis can be applied to various domains. Customize these projects to fit your interests and explore additional features and techniques to further enhance your Excel proficiency.

### Advanced Project: Social Media Analytics

Create a social media analytics dashboard to analyze engagement and performance metrics.

#### Dataset: Social Media Data

| Post ID | Date       | Likes | Comments | Shares | Click-Through Rate (%) |
| ------- | ---------- | ----- | -------- | ------ | ---------------------- |
| P001    | 2022-01-01 | 500   | 50       | 100    | 5                      |
| P002    | 2022-01-05 | 700   | 80       | 120    | 7                      |
| P003    | 2022-02-10 | 600   | 60       | 90     | 4                      |

#### Tasks:

1. Calculate the average engagement metrics (likes, comments, shares) per post.
2. Create a line chart to visualize the trend in click-through rates over time.
3. Implement data validation for the "Date" column to ensure consistent formatting.
4. Use conditional formatting to highlight posts with exceptional engagement.

### Advanced Project: Health and Fitness Tracker

Build a health and fitness tracker to monitor personal wellness and set goals.

#### Dataset: Health Data

| Date       | Weight (kg) | Steps | Calories Burned |
| ---------- | ----------- | ----- | --------------- |
| 2022-01-01 | 70          | 10000 | 500             |
| 2022-01-05 | 69          | 12000 | 600             |
| 2022-02-10 | 71          | 8000  | 450             |

#### Tasks:

1. Calculate the average weight, steps, and calories burned over a specified period.
2. Use data validation to ensure accurate input for weight and other numeric values.
3. Create a line chart to visualize weight changes over time.
4. Implement conditional formatting to highlight days where step goals were exceeded.

### Advanced Project: Inventory Management System

Develop an inventory management system to track product stock levels and reorder points.

#### Dataset: Inventory Data

| Product ID | Product Name | Current Stock | Reorder Point | Unit Price ($) |
| ---------- | ------------ | ------------- | ------------- | -------------- |
| P001       | Product A    | 150           | 100           | 10             |
| P002       | Product B    | 200           | 150           | 15             |
| P003       | Product C    | 100           | 80            | 20             |

#### Tasks:

1. Calculate the reorder quantity based on the difference between current stock and reorder point.
2. Use data validation for the "Current Stock" column to ensure non-negative values.
3. Implement conditional formatting to highlight products that are below the reorder point.
4. Create a summary table showing total inventory value and average unit price.

### Advanced Project: Event Planning and Budgeting

Create an event planning and budgeting model to organize and manage various aspects of an event.

#### Dataset: Event Data

| Task          | Description                        | Assigned To | Estimated Cost ($) | Actual Cost ($) | Status |             
| ------------- | ---------------------------------- | ----------- | -------------------------------------- | ------ | ----------- |
| Venue Booking | Secure a venue for the event       |             | 5000                                   |        | In Progress |
| Catering      | Arrange catering services          |             | 3000                                   |        | Not Started |
| Decorations   | Plan and execute event decorations |             | 2000                                   |        | Not Started |
| Entertainment | Book performers or entertainment   |             | 4000                                   |        | Completed   |

#### Tasks:

1. Calculate the total estimated and actual costs for the event.
2. Use data validation for the "Status" column to ensure consistent inputs.
3. Create a Gantt chart to visualize the timeline and progress of each task.
4. Implement conditional formatting to highlight tasks with actual costs exceeding estimated costs.

### Advanced Project: Travel Expense Tracker

Build a travel expense tracker to manage and analyze expenses incurred during business trips.

#### Dataset: Travel Expense Data

| Date       | Category      | Amount ($) |
| ---------- | ------------- | ---------- |
| 2022-01-01 | Flights       | 800        |
| 2022-01-05 | Accommodation | 1200       |
| 2022-02-10 | Meals         | 300        |

#### Tasks:

1. Create a PivotTable to summarize total expenses by category.
2. Use data validation to restrict input choices for the "Category" column.
3. Implement a dynamic chart to visualize the distribution of travel expenses.
4. Calculate the average daily expense for each trip.

### Advanced Project: Cybersecurity Incident Tracker

Develop a cybersecurity incident tracker to log and analyze security incidents.

#### Dataset: Incident Data

| Incident ID | Date       | Type            | Severity | Status        |
| ----------- | ---------- | --------------- | -------- | ------------- |
| I001        | 2022-01-01 | Phishing Attack | High     | Resolved      |
| I002        | 2022-01-05 | Data Breach     | Critical | In Progress   |
| I003        | 2022-02-10 | Malware Attack  | Medium   | Investigating |

#### Tasks:

1. Calculate the total number of incidents and their severity distribution.
2. Use data validation for the "Type" and "Severity" columns.
3. Create a dynamic chart to visualize incident trends over time.
4. Implement conditional formatting to highlight critical or unresolved incidents.

### Advanced Project: Personal Finance Dashboard

Build a comprehensive personal finance dashboard to track income, expenses, and investments.

#### Components:

1. **Income Tracker:**

   - Display sources of income, with a breakdown of amounts.
2. **Expense Analysis:**

   - Visualize monthly expenses using a dynamic chart.
3. **Investment Portfolio:**

   - Track the performance of different investments.
4. **Net Worth Overview:**

   - Calculate and display net worth over time.
5. **Budget vs. Actuals:**

   - Compare planned vs. actual expenses.
6. ### Advanced Project: Project Risk Management

   Develop a project risk management model to identify, assess, and mitigate risks associated with various project tasks.

#### Dataset: Risk Data

| Task          | Description                              | Assigned To | Probability (%) | Impact | Mitigation Plan                 |
| ------------- | ---------------------------------------- | ----------- | --------------- | ------ | ------------------------------- |
| Venue Booking | Risk of venue unavailability             |             | 20              | High   | Negotiate backup venue          |
| Catering      | Potential delays in catering services    |             | 15              | Medium | Identify alternative caterers   |
| Decorations   | Supply chain disruptions for decorations |             | 10              | Low    | Maintain a backup supplier      |
| Entertainment | Performer cancellation                   |             | 25              | High   | Contract with backup performers |

#### Tasks:

1. Calculate the overall risk score for each task (Probability * Impact).
2. Use data validation to ensure consistent input for the "Probability" and "Impact" columns.
3. Implement conditional formatting to highlight high-risk tasks.
4. Create a risk mitigation dashboard with visual indicators for each task.

### Advanced Project: Web Analytics Dashboard

   Build a web analytics dashboard to analyze website traffic, user behavior, and conversion rates.

#### Dataset: Web Analytics Data

| Date       | Page Views | Unique Visitors | Conversion Rate (%) |
| ---------- | ---------- | --------------- | ------------------- |
| 2022-01-01 | 5000       | 2000            | 3.5                 |
| 2022-01-05 | 6000       | 2500            | 4.0                 |
| 2022-02-10 | 5500       | 2300            | 3.8                 |

#### Tasks:

1. Calculate average page views, unique visitors, and conversion rates.
2. Use data validation for the "Date" column to ensure consistent formatting.
3. Create a dynamic chart to visualize trends in website traffic and conversion rates.
4. Implement conditional formatting to highlight days with exceptional conversion rates.

### Advanced Project: Employee Training Tracker

   Develop an employee training tracker to monitor training programs, participation, and completion rates.

#### Dataset: Training Data

| Employee ID | Name        | Department | Training Program       | Start Date | End Date   | Status      |
| ----------- | ----------- | ---------- | ---------------------- | ---------- | ---------- | ----------- |
| E001        | John Doe    | Sales      | Sales Techniques       | 2022-01-01 | 2022-01-15 | Completed   |
| E002        | Jane Smith  | Marketing  | Social Media Marketing | 2022-02-10 | 2022-02-28 | In Progress |
| E003        | Bob Johnson | Finance    | Financial Analysis     | 2022-03-15 | 2022-04-01 | Not Started |

#### Tasks:

1. Calculate the completion rate for each training program.
2. Use data validation for the "Status" column to ensure consistent inputs.
3. Create a summary table showing the number of employees who have completed each program.
4. Implement conditional formatting to highlight overdue or incomplete training programs.

# **1. Use of Formulas Sum, Average, If, Count, Counta, Countif & Sumif**

| **Roll No** | **Student Name** | **Hindi** | **English** | **Math** | **Physics** | **Chemistry** | **Total** | **Average** | **Grade** |
| ----------------- | ---------------------- | --------------- | ----------------- | -------------- | ----------------- | ------------------- | --------------- | ----------------- | --------------- |
| 1                 | RAM                    | 20              | 10                | 14             | 18                | 15                  | 77              | 15\.4             | A               |
| 2                 | ASHOK                  | 21              | 12                | 14             | 12                | 18                  | ?               | ?                 | ?               |
| 3                 | MANOJ                  | 33              | 15                | 7              | 14                | 17                  | ?               | ?                 | ?               |
| 4                 | RAJESH                 | 15              | 14                | 8              | 16                | 20                  | ?               | ?                 | ?               |
| 5                 | RANJANA                | 14              | 17                | 10             | 13                | 18                  | ?               | ?                 | ?               |
| 6                 | POOJA                  | 16              | 8                 | 20             | 17                | 15                  | ?               | ?                 | ?               |
| 7                 | MAHESH                 | 18              | 19                | 3              | 10                | 14                  | ?               | ?                 | ?               |
| 8                 | ASHUTOSH               | 19              | 20                | 7              | 14                | 18                  | ?               | ?                 | ?               |
| 9                 | ANIL                   | 22              | 13                | 8              | 12                | 19                  | ?               | ?                 | ?               |
| 10                | PREM                   | 26              | 12                | 10             | 11                | 27                  | ?               | ?                 | ?               |

**Q.1 Find the Total Number & Average in all Subjects in Each Student .**

**Q.2 Find Grade Using If Function - If Average Greater  >15 then "A" Grade otherwise "B" Grade**

**Q.3 How Many Student "A" and "B" Grade**   (Use of Countif)

**Q.4 Student Ashok and Manoj Total Number and Average**   Use of Sumif

**Q.5 Count how many Students**   Use of Counta

**Q.6 How Many Student Hindi & English Subject Number Grater Then > 20 and <15**   Use of Countif

**Use of Formulas - Product, If, Counta, Countif, Sumif**

| **SRNO** | **ITEMS** | **QTY** | **RATE** | **AMOUNT** | **GRADE** |
| -------------- | --------------- | ------------- | -------------- | ---------------- | --------------- |
| 1              | AC              | 20            | 40000          | 800000           | Expensive       |
| 2              | FRIDGE          | 30            | 20000          | ?                |                 |
| 3              | COOLER          | 15            | 10000          | ?                |                 |
| 4              | WASHING MACHINE | 14            | 15000          | ?                |                 |
| 5              | TV              | 18            | 20000          | ?                |                 |
| 6              | FAN             | 17            | 2000           | ?                |                 |
| 7              | COMPUTER        | 10            | 25000          | ?                |                 |
| 8              | KEYBOARD        | 5             | 250            | ?                |                 |
| 9              | MOUSE           | 25            | 100            | ?                |                 |
| 10             | PRINTER         | 30            | 12000          | ?                |                 |
|                |                 |               |                |                  |                 |

**Q.1 Using of Product Fomula for Calculate Amount = Qty\*Rate  Q.2 How Many Items in a List**
**Q.3 How Many Items qty Greate Then > 20 and Less Then <20  **

**Q.4 Calculate Item Computer Qty, Rate and Amount using Sumif Formula**

**Q.5 If Items Amount is Greater > 500000, Then Items "Expensive" otherwise "Lets Buy it".**

**Use of Formulas - Sum, NestedIf, Counta, Countif, Sumif, Vlookup**

| **SUBJECT** | **1ST** | **2ND** | **3RD** | **TOTAL** | **AVERAGE** | **GRADE** |
| ----------------- | ------------- | ------------- | ------------- | --------------- | ----------------- | --------------- |
| HINDI             | 20            | 15            | 20            | 55              | 18\.33333333      | B               |
| ENGLISH           | 30            | 12            | 15            | ?               | ?                 | ?               |
| MATH              | 15            | 14            | 14            | ?               | ?                 | ?               |
| PHYSICS           | 12            | 17            | 17            | ?               | ?                 | ?               |
| CHEMISTRY         | 14            | 18            | 18            | ?               | ?                 | ?               |
| HISTORY           | 16            | 25            | 20            | ?               | ?                 | ?               |
| GEO               | 18            | 21            | 22            | ?               | ?                 | ?               |
| BIO               | 17            | 23            | 13            | ?               | ?                 | ?               |
| BOTANY            | 20            | 25            | 25            | ?               | ?                 | ?               |

**Q.1 HOW MANY SUBJECT ?**   Use of Counta

**Q.2 HOW MANY SUBJECT 1 PAPER GREATER THAN 20 ?**   Use of Countif

**Q.3 SUBJECT HINDI, MATH & ENGLISH TOTAL NO. & GRADE**   Vlookup

**Q.4 IF AVE. GREATHER THAN 20 THEN "A", IF AVE. GREATEHR THAN 15 AVE. "B" OTHERWISE "C"**

**Q.5 SUBJECT PHYSICS, MATHS & ENGLISH TOTAL /AVERAGE**   Vlookup

** -4  (Salary Sheet)**

**Use of Formulas - Sum, NestedIf, Counta, Countif, Sumif, Vlookup**

| **NAME** | **DEPARTMENT** | **POST** | **BASIC** | **DA 2.5%** | **HRA 3.5%** | **PF 1.5%** | **TOTAL** | **GRADE** |
| -------------- | -------------------- | -------------- | --------------- | ----------------- | ------------------ | ----------------- | --------------- | --------------- |
| RAM            | COMPUTER             | MANAGER        | 5000            | 125               | 175                | 50                | 5250            | D               |
| SHYAM          | COMPUTER             | SUPERVISOR     | 8000            | ?                 | ?                  | ?                 | ?               | ?               |
| MANOJ          | COMPUTER             | PION           | 3000            | ?                 | ?                  | ?                 | ?               | ?               |
| POOJA          | ELECTRICAL           | GUARD          | 6000            | ?                 | ?                  | ?                 | ?               | ?               |
| RAHUL          | ELECTRICAL           | CASHER         | 8000            | ?                 | ?                  | ?                 | ?               | ?               |
| RAKESH         | ELECTRICAL           | ACCOUNTANT     | 9000            | ?                 | ?                  | ?                 | ?               | ?               |
| ASHISH         | FINANCE              | MANAGER        | 10000           | ?                 | ?                  | ?                 | ?               | ?               |
| MANISH         | FINANCE              | GUARD          | 5000            | ?                 | ?                  | ?                 | ?               | ?               |

**Q.1 HOW MANY EMPLOYEE IN COMPUTER, FINANCE, ELECTRICAL DEPARTMENT**   Use of Countif

**Q.2 HOW MANY BASIC SALARY IN COMPUTER DFPARTMENT ONLY?   Use of Sumif**

**Q.3 MANOJ, ASHISH POST & GRADE**

Use of Vlookup

**Q.4 IF TOTAL SALALRY IS GREATER THEN 20000 THEN "A", IF TOTAL SALARY GREATER THEN 10000 THEN "B",  OTHERWISE "C"**

**Q.5 HOW MANY EMPLOYEE IS MANAGER & GUARD?**   Use of Countif

**   (Sales Report)**

**Use of Formulas - Sum, If, Counta, Countif, Sumif, Vlookup, Lookup**

| **SALESMAN** | **JAN** | **FEB** | **MAR** | **APR** | **MAY** | **JUNE** | **SALES** | **TARGET** | **RESULT** |
| ------------------ | ------------- | ------------- | ------------- | ------------- | ------------- | -------------- | --------------- | ---------------- | ---------------- |
| RAMESH             | 2000          | 1500          | 300           | 1400          | 1000          | 1400           | 7600            | 10000            | NOT ACHIVED      |
| RAKESH             | 5000          | 1200          | 500           | 1200          | 1200          | 2800           | ?               | 12000            | ?                |
| RAHUL              | 3000          | 800           | 1200          | 3000          | 1500          | 3500           | ?               | 18000            | ?                |
| POOJA              | 1000          | 900           | 1800          | 5000          | 1400          | 1200           | ?               | 10000            | ?                |
| MANOJ              | 500           | 1000          | 2300          | 8000          | 1700          | 1400           | ?               | 12000            | ?                |
| ASHOK              | 800           | 500           | 2400          | 1900          | 1800          | 1800           | ?               | 10000            | ?                |
| AJEET              | 1200          | 1400          | 1500          | 700           | 2500          | 7000           | ?               | 12000            | ?                |
| ALOK               | 1500          | 1800          | 1800          | 1800          | 300           | 1500           | ?               | 10000            | ?                |
| AMRIT              | 1800          | 2500          | 1700          | 1500          | 2800          | 1800           | ?               | 12000            | ?                |
| SURENDRA           | 200           | 3000          | 1900          | 1200          | 1500          | 3000           | ?               | 10000            | ?                |
| SHASHI             | 1600          | 1200          | 2000          | 800           | 1700          | 800            | ?               | 10000            | ?                |

**Q.1 How many salesman? Salesman Ajeet Targest & Result?**

**Q.2 If Sales Greater Than Target Then Target Achived otherwise Not Achived**

**Q.3 Rahul Pooja & Ashok Targest & result?**

**Q.4 How Many Salesman Achived Target.**

**Q.5 Which Sales Man Jan Sales 2000, & Feb Sales is 2500?**

* Use of Counta and Vlookup
* Use of If Function
* Use of Vlookup
* Use of Countif
* Use of Lookup Function

** -6**

**Use of Formulas -  Counta, Countif, Sumif, Hlookup, Conditional Formatting **

| **Items** | **Date** | **Cost** |
| --------------- | -------------- | -------------- |
| BRAKES          | 01-01-2016     | 800\.00        |
| TYRES           | 12-05-2016     | 2000\.00       |
| BRAKES          | 18-05-2016     | 500\.00        |
| SERVICE         | 20-05-2016     | 800\.00        |
| SERVICE         | 10-02-2016     | 1000\.00       |
| WINDOW          | 08-05-2016     | 1000\.00       |
| TYRES           | 10-05-2016     | 1200\.00       |
| TYRES           | 25-05-2016     | 1500\.00       |
| CLUTCH          | 10-07-2016     | 1800\.00       |
| TYRES           | 10-01-2016     | 2000\.00       |
| CLUTCH          | 15-06-2016     | 1500\.00       |

| CLUTCH | 12-01-2016 | 1000\.00 |
| ------ | ---------- | -------- |
| WINDOW | 01-01-2016 | 1200\.00 |
| WINDOW | 10-05-2016 | 1500\.00 |
| WINDOW | 10-05-2016 | 1800\.00 |
| BRAKES | 10-05-2016 | 1000\.00 |
| BRAKES | 14-08-2016 | 1200\.00 |
| TYRES  | 15-08-2016 | 1500\.00 |
| WINDOW | 20-08-2016 | 1800\.00 |

**Q.1 HOW MANY ITEMS ?**

**Q.2 HOW MANY BRAKE, WINDOW & TYRES HAVE BEEN BOUGHTS? Q.3 HOW MANY ITEMS COST IS >1000 & BELOW > = 1000?**

**Q.4 HIGHLIGHT TYRES ITESM & 500 BETWEEN 2000 COST. Q.5 ITEMS COLOUMN IS 15, 18 & 20 ITEMS NAME?**

**Q.6 Total Cost of Window and Brakes Items?**

Use of Counta Use of Countif Use of Countif Use of Conditional F

* Use of Hlookup
* Use of Sumif

** -7  (Calculate Date of Birth)**

**Use of Formulas -  Counta, Countif, Sumif, if & Datedif**

| **NAME** |  | **DATE OF BIRTH** | **DAY** | **MONTH** | **YEAR** |
| -------------- | :- | ----------------------- | ------------- | --------------- | -------------- |
| RAMESH         |  | 15-05-1980              | 10            | 11              | 40             |
| RAKESH         |  | 20-08-1981              | ?             | ?               | ?              |
| RAHUL          |  | 15-10-2003              | ?             | ?               | ?              |
| POOJA          |  | 25-05-1990              | ?             | ?               | ?              |
| MANOJ          |  | 24-08-1992              | ?             | ?               | ?              |
| ASHOK          |  | 23-08-1998              | ?             | ?               | ?              |
| AJEET          |  | 12-05-1980              | ?             | ?               | ?              |
| ALOK           |  | 18-03-2005              | ?             | ?               | ?              |
| AMRIT          |  | 15-08-2007              | ?             | ?               | ?              |
| SURENDRA       |  | 25-05-2010              | ?             | ?               | ?              |
| SHASHI         |  | 25-08-1993              | ?             | ?               | ?              |

Use of

**Q.1 HOW MANY STUDENT?**  Counta

**Q.2 STUDENT SURENDRA IS HOW MANY YEAR OLD?**   Sumif

Use of **Q.3 HOW MANY STUDENT AGE GREATER THEN 20 YEARS?**  Countif

**Q.4 IF STUDENT AGE IS GREATHER THEN 20 THEN STUDENT ADULT / CHILD?**

Use of **Q.5 HOW MANY STUDENT AGE IS >= 25 YEARS?**  Countif 

** -8**

**Use of Formulas -  Sum, Average, Counta, Countif, Sumif, & If  ![ref3][ref3]**

| **Student Name** | **Subject** | **Result**  |                   |                 |                      |                 |
| ---------------------- | ----------------- | ----------------- | :---------------- | :-------------- | :------------------- | :-------------- |
| **Name**         | **Maths**   | **English** | **Physics** | **TOTAL** | **PERCENTAGE** | **GRADE** |
| Alan                   | 80                | 75                | 85                | 240             | 80                   | EXCELLENT       |
| Bob                    | 50                | 30                | 40                | 120             | ?                    | ?               |
| Carol                  | 60                | 70                | oor               | 130             | ?                    | ?               |
| David                  | 90                | 85                | 95                | 270             | ?                    | ?               |
| Eric                   | 20                | 30                | Absent            | 50              | ?                    | ?               |
| Fred                   | 40                | 60                | 80                | 180             | ?                    | ?               |
| Gail                   | 10                | 90                | 80                | 180             | ?                    | ?               |
| Harry                  | 80                | 70                | 60                | 210             | ?                    | ?               |
| Ian                    | 30                | 10                | 20                | 60              | ?                    | ?               |
| Janice                 | 10                | 20                | 30                | 60              | ?                    | ?               |

**Q.1 How Many Student?**   Use Formula Counta

**Q.2 How Many Student Percentage Greather Then > 50**  Use Formula Countif

**Q.3 Student Bob and Eric Total Number?**   Use Formula Sumif

**Q.4 If Percentage Greater Then >70 Then "Excellent", If Percentage Greater Then >50,"Good", Otherwise "Bed" Q.5 How Many Student Good and Bed in a list**   Use Formula Countif

** -9**

**Use of Formulas -  LOOKUP  LOOKUP FUNCTION SYNTAX   LOOKUP(LOOKUP\_value,lookup\_vector,[result\_vector]) **

| **Empoyee ID** | **Last Name** | **First Name** |
| -------------------- | ------------------- | -------------------- |
| 110608               | Doe                 | John                 |
| 253072               | Cline               | Andy                 |
| 352711               | Smith               | John                 |
| 391006               | Pan                 | Peter                |
| 392128               | Favre               | Bret                 |
| 549457               | Elway               | John                 |
| 580622               | Manning             | Eli                  |
| 602693               | Vick                | Micheal              |
| 611810               | Woods               | Tiger                |
| 612235               | Jordan              | Micheal              |
| 795574               | Stark               | Tony                 |
| 830385               | Williams            | Prince               |

| **Empoyee ID** | **Pay** | **First N.** | **Last N.** |
| -------------------- | ------------- | :----------------: | :---------------: |
| 602693               | $     84,289  |      Micheal      |       Vick       |
| 611810               | $  1,37,670   |         ?         |         ?         |
| 549457               | $  1,90,024   |         ?         |         ?         |
| 612235               | $  1,22,604   |         ?         |         ?         |
| 580622               | $  1,11,709   |         ?         |         ?         |
| 830385               | $     85,931  |         ?         |         ?         |
| 253072               | $  1,68,114   |         ?         |         ?         |
| 391006               | $     89,627  |         ?         |         ?         |
| 990678               | $  1,49,946   |         ?         |         ?         |
| 795574               | $  1,45,893   |         ?         |         ?         |
| 392128               | $     64,757  |         ?         |         ?         |
| 352711               | $     71,478  |         ?         |         ?         |

 **Use of Formulas -  Counta, Countif, Sumif, & Vlookup**

USE OF VLOOKUP

| **Employee ID** | **Full Name** | **SSN** | **Department** | **Start Date** | **Earnings** |
| --------------------- | ------------------- | ------------- | -------------------- | -------------------- | ------------------ |
| EMP001                | ?                   | ?             | ?                    | ?                    | ?                  |
| EMP002                | ?                   | ?             | ?                    | ?                    | ?                  |
| EMP003                | ?                   | ?             | ?                    | ?                    | ?                  |

| **Employee ID** | **Full Name** | **SSN** | **Department** | **Start Date** |  | **Earnings** |
| --------------------- | ------------------- | ------------- | -------------------- | -------------------- | :- | ------------------ |
| EMP001                | Faith K. Macias     | 845-04-3962   | Marketing            | 27-01-2008           |  | $73,500.00         |
| EMP002                | Lucian Q. Franklin  | 345-28-4935   | IT/IS                | 01-03-2008           |  | $80,000.00         |
| EMP003                | Blaze V. Bridges    | 503-53-8350   | Marketing            | 16-04-2008           |  | $95,000.00         |
| EMP004                | Denton Q. Dale      | 858-39-7967   | Marketing            | 03-05-2008           |  | $1,05,000.00       |
| EMP005                | Blossom K. Fox      | 245-18-5890   | Engineering          | 11-07-2008           |  | $90,000.00         |
| EMP006                | Kerry V. David      | 873-45-8675   | Finance              | 17-07-2008           |  | $60,000.00         |
| EMP007                | Melanie X. Baker    | 190-08-3679   | Finance              | 05-10-2008           |  | $87,000.00         |
| EMP008                | Adele M. Fulton     | 352-36-9553   | Engineering          | 28-10-2008           |  | $1,04,000.00       |
| EMP009                | Justina O. Jensen   | 645-74-0451   | Marketing            | 05-11-2008           |  | $3,80,050.00       |
| EMP010                | Yoshi J. England    | 558-53-1475   | Marketing            | 09-12-2008           |  | $93,000.00         |
| EMP011                | Brooke Y. Mccarty   | 129-42-6148   | IT/IS                | 12-02-2009           |  | $1,80,000.00       |
| EMP012                | Kay G. Colon        | 796-50-4767   | Marketing            | 19-03-2009           |  | $1,00,000.00       |
| EMP013                | Callie I. Forbes    | 266-48-1339   | Human Resources      | 13-04-2009           |  | $1,36,000.00       |
| EMP014                | Zachery O. Mann     | 663-00-3285   | Marketing            | 28-04-2009           |  | $68,000.00         |

**Q.1 How Many Employee in a List ?**

**Q.2 How Many Employee work in Finance and Marketing Department?  Q.3 Employee Blossom K. Fox Department and Earnings?**

**Q.4 Employee Blossom K. SSN No.?**

**Q.5 How Many Amount Earnings Marketing Department?**

Use of Formula Counta Use of Formula Countif Use of Vlookup

Use of Vlookup

Use of Sumif

** -11**

**Use of Formulas -  Match and Vlookup With Match  **

| **CLASSIC FAVORITES**        | **TALL** | **GRANDE** | **VENTI** |
| ---------------------------------- | -------------- | ---------------- | --------------- |
| Caffe Latte  $2.95   $3.75   $4.15 |                |                  |                 |
| Cappuccino  $2.95   $3.65   $4.15  |                |                  |                 |

| Caramel Macchiato     | $3.75 | $3.95 | $4.25 |
| --------------------- | ------------- | ----- | - |
| Caffe Mocha           | $3.25 | $3.95 | $4.40 |  |
| White Chocolate Mocha | $3.45 | $4.15 | $4.55 |  |
| Caffe Americano       | $2.00 | $2.40 | $2.75 |  |
| Cinnamon Dolce Latte  | $3.95 | $4.75 | $5.15 |  |
| Steamer               | $2.25 | $2.50 | $2.75 |  |
| Drip Coffee           | $1.75 | $1.95 | $2.05 |  |

**Question: What is the column number for the size Grande,Tall, Venti? Use of Match Formula**

Grande  3  Use of Match Function **VENTI**  ?  Use of Match Function **TALL**  ?  Use of Match Function

**Question: What is the price of a Caffe Mocha, size Grande,Tall, Venti? Use of Vlookup with Match Formula**

Caffe Mocha  Grande  $3.95  Caffe Mocha  TALL  ?

Caffe Mocha  VENTI  ?

** -12**

**Use of Formulas -  Counta and Vlookup**

| **Product Name** | **Jan**           | **Feb**           | **Mar**           | **Apr**           | **May** | **Jun** | **Jul** | **Aug** | **Total Sales** |
| ---------------------- | ----------------------- | ----------------------- | ----------------------- | ----------------------- | ------------- | ------------- | ------------- | ------------- | --------------------- |
| Apples                 | $2,773        | $17,462 | $5,954        | $1,348  | $28,158       | $28,799 | $25,415       | $17,227 | $1,27,136     |               |               |               |                       |
| Grapefruit             | $12,908       | $3,083  | $24,492       | $5,825  | $1,080        | $2,188  | $11,087       | $15,544 | ?             |               |               |               |                       |
| Lemons                 | $6,554        | $14,262 | $8,377        | $24,982 | $12,184       | $6,430  | $21,159       | $18,597 | ?             |               |               |               |                       |
| Lime                   | $28,913       | $1,437  | $20,019       | $13,026 | $26,952       | $27,076 | $7,040        | $10,884 | ?             |               |               |               |                       |
| Oranges                | $4,768        | $7,622  | $28,918       | $27,141 | $3,578        | $10,092 | $15,207       | $12,771 | ?             |               |               |               |                       |
| Peaches                | $13,390       | $3,611  | $6,226        | $27,567 | $29,962       | $2,967  | $5,740        | $2,137  | ?             |               |               |               |                       |
| Pears                  | $17,585       | $28,508 | $9,614        | $17,110 | $12,143       | $7,365  | $24,185       | $1,643  | ?             |               |               |               |                       |
| Pineapples             | $22,579       | $16,301 | $6,469        | $22,050 | $8,740        | $18,806 | $3,334        | $3,597  | ?             |               |               |               |                       |

Q.1 How Many Fruits?

Q.2 Fruits Lemons and Pineapples sales in Mar and Jul ?  


** -13**

**Create Pivot Table Using Data**

| **Last Name** |  | **Sales** | **Country** | **Quarter** |
| ------------------- | :- | --------------- | ----------------- | ----------------- |
| Smith               |  | $16,753.00      | UK                | Qtr 3             |
| Johnson             |  | $14,808.00      | USA               | Qtr 4             |
| Williams            |  | $10,644.00      | UK                | Qtr 2             |
| Jones               |  | $1,390.00       | USA               | Qtr 3             |
| Brown               |  | $4,865.00       | USA               | Qtr 4             |
| Williams            |  | $12,438.00      | UK                | Qtr 1             |
| Johnson             |  | $9,339.00       | UK                | Qtr 2             |
| Smith               |  | $18,919.00      | USA               | Qtr 3             |
| Jones               |  | $9,213.00       | USA               | Qtr 4             |
| Jones               |  | $7,433.00       | UK                | Qtr 1             |
| Brown               |  | $3,255.00       | USA               | Qtr 2             |
| Williams            |  | $14,867.00      | USA               | Qtr 3             |
| Williams            |  | $19,302.00      | UK                | Qtr 4             |
| Smith               |  | $9,698.00       | USA               | Qtr 1             |

** -14**

 **Use of Formulas -  Countif, Countifs and Sumifs  ![ref5][ref5]![ref5][ref5]**

| **Season** | **Year** |  | **Type** |  | **State** |  | **Sales $** |
| ---------------- | -------------- | :- | -------------- | :- | --------------- | :- | ----------------- |
| Fall             | 1998           |  | Amber Ale      |  | California      |  | $5,54,536         |
| Fall             | 1998           |  | Hefeweizen     |  | California      |  | $5,40,643         |
| Fall             | 1998           |  | Pale Ale       |  | California      |  | $5,77,548         |
| Fall             | 1998           |  | Pilsner        |  | California      |  | $4,55,905         |
| Fall             | 1998           |  | Porter         |  | California      |  | $4,90,871         |
| Fall             | 1998           |  | Stout          |  | California      |  | $4,46,383         |
| Fall             | 1998           |  | Amber Ale      |  | Oregon          |  | $4,57,726         |
| Fall             | 1998           |  | Hefeweizen     |  | Oregon          |  | $3,47,696         |
| Fall             | 1998           |  | Pale Ale       |  | Oregon          |  | $3,84,541         |
| Fall             | 1998           |  | Pilsner        |  | Oregon          |  | $3,86,420         |
| Fall             | 1998           |  | Porter         |  | Oregon          |  | $3,70,970         |
| Fall             | 1998           |  | Stout          |  | Oregon          |  | $4,30,754         |
| Fall             | 1998           |  | Amber Ale      |  | Washington      |  | $5,00,847         |
| Fall             | 1998           |  | Hefeweizen     |  | Washington      |  | $5,07,070         |
| Fall             | 1998           |  | Pale Ale       |  | Washington      |  | $4,82,346         |
| Fall             | 1998           |  | Pilsner        |  | Washington      |  | $6,08,713         |
| Fall             | 1998           |  | Porter         |  | Washington      |  | $1,50,000         |
| Fall             | 1998           |  | Stout          |  | Washington      |  | $5,00,649         |
| Spring           | 1998           |  | Amber Ale      |  | California      |  | $5,45,780         |

  

| Spring | 1998 | Hefeweizen | California | $4,40,644 |
| ------ | ---- | ---------- | ---------- | --------- |
| Spring | 1998 | Pale Ale   | California | $5,80,359 |
| Spring | 1998 | Pilsner    | California | $5,36,225 |
| Spring | 1998 | Porter     | California | $4,14,908 |
| Spring | 1998 | Stout      | California | $3,77,997 |
| Spring | 1998 | Amber Ale  | Oregon     | $3,31,289 |
| Spring | 1998 | Hefeweizen | Oregon     | $3,84,572 |
| Spring | 1998 | Pale Ale   | Oregon     | $3,65,813 |
| Spring | 1998 | Pilsner    | Oregon     | $3,96,338 |
| Spring | 1998 | Porter     | Oregon     | $4,53,761 |
| Spring | 1998 | Stout      | Oregon     | $3,56,538 |
| Spring | 1998 | Amber Ale  | Washington | $6,06,332 |
| Spring | 1998 | Hefeweizen | Washington | $5,35,218 |
| Spring | 1998 | Pale Ale   | Washington | $4,93,364 |
| Spring | 1998 | Pilsner    | Washington | $5,59,100 |
| Spring | 1998 | Porter     | Washington | $2,20,350 |
| Spring | 1998 | Stout      | Washington | $4,76,975 |

Using Formula

**Q.1 How Many Spring and Fall Season?**   Countif

Using Formula

**Q.2 How Many Fall Season in California and Washington?**   Countifs

**Q.3 Total Sales if Spring Season in Washngton and California?**   using Formula Sumifs

Using Formula

**Q.4 How Many Spring Season in Washington only?**   Countifs

**Q.5 Create Pivot Table Using Data?**

** -15**

**Create Pivot Table Using Data Separate Fruit and Vegetables  **

| **Order ID** | **Product** | **Category** | **Amount** | **Date** | **Country** |
| ------------------ | ----------------- | ------------------ | ---------------- | -------------- | ----------------- |
| 1                  | Carrots           | Vegetables         | $4,270           | 06-01-2016     | United States     |
| 2                  | Broccoli          | Vegetables         | $8,239           | 07-01-2016     | United Kingdom    |
| 3                  | Banana            | Fruit              | $617             | 08-01-2016     | United States     |
| 4                  | Banana            | Fruit              | $8,384           | 10-01-2016     | Canada            |
| 5                  | Beans             | Vegetables         | $2,626           | 10-01-2016     | Germany           |
| 6                  | Orange            | Fruit              | $3,610           | 11-01-2016     | United States     |
| 7                  | Broccoli          | Vegetables         | $9,062           | 11-01-2016     | Australia         |
| 8                  | Banana            | Fruit              | $6,906           | 16-01-2016     | New Zealand       |
| 9                  | Apple             | Fruit              | $2,417           | 16-01-2016     | France            |
| 10                 | Apple             | Fruit              | $7,431           | 16-01-2016     | Canada            |
| 11                 | Banana            | Fruit              | $8,250           | 16-01-2016     | Germany           |
| 12                 | Broccoli          | Vegetables         | $7,012           | 18-01-2016     | United States     |
| 13                 | Carrots           | Vegetables         | $1,903           | 20-01-2016     | Germany           |
| 14                 | Broccoli          | Vegetables         | $2,824           | 22-01-2016     | Canada            |

  

| 15 | Apple    | Fruit      | $6,946 | 24-01-2016 | France         |
| -- | -------- | ---------- | ------ | ---------- | -------------- |
| 16 | Banana   | Fruit      | $2,320 | 27-01-2016 | United Kingdom |
| 17 | Banana   | Fruit      | $2,116 | 28-01-2016 | United States  |
| 18 | Banana   | Fruit      | $1,135 | 30-01-2016 | United Kingdom |
| 19 | Broccoli | Vegetables | $3,595 | 30-01-2016 | United Kingdom |
| 20 | Apple    | Fruit      | $1,161 | 02-02-2016 | United States  |
| 21 | Orange   | Fruit      | $2,256 | 04-02-2016 | France         |
| 22 | Banana   | Fruit      | $1,004 | 11-02-2016 | New Zealand    |
| 23 | Banana   | Fruit      | $3,642 | 14-02-2016 | Canada         |
| 24 | Banana   | Fruit      | $4,582 | 17-02-2016 | United States  |
| 25 | Beans    | Vegetables | $3,559 | 17-02-2016 | United Kingdom |
| 26 | Carrots  | Vegetables | $5,154 | 17-02-2016 | Australia      |
| 27 | Mango    | Fruit      | $7,388 | 18-02-2016 | France         |
| 28 | Beans    | Vegetables | $7,163 | 18-02-2016 | United States  |
| 29 | Beans    | Vegetables | $5,101 | 20-02-2016 | Germany        |
| 30 | Apple    | Fruit      | $7,602 | 21-02-2016 | France         |

**Q.1 How Many Fruits and Vegetables Items in a List?**   Use of Formula Countif

**Q.2 Total Apple and Banana Amount?**   Use of Formula Sumif

**Q.3 How Many Product in a list?**  Use of Counta

**Q.4 How Many Apple and Banana Use in Canada & United Ki** **ngdom?**   Use of Countifs

**Q.5 Apple and Banana Sales in United**

**States ?**   Use of Sumifs

** -16**

 **Use of Formulas -  Countif, Countifs and Sumifs and Vlookup  ![ref6][ref6]![ref6][ref6]**

| **Name** | **Gender** | **Country** | **Score** |
| -------------- | ---------------- | ----------------- | --------------- |
| Richard        | Male             | United States     | 74              |
| Jennifer       | Female           | United Kingdom    | 92              |
| James          | Male             | United States     | 65              |
| Lisa           | Female           | Canada            | 82              |
| Sharon         | Female           | Australia         | 50              |
| Elizabeth      | Female           | Canada            | 91              |
| Carol          | Female           | United States     | 96              |
| Mark           | Male             | United States     | 58              |
| John           | Male             | Canada            | 67              |
| Susan          | Female           | United Kingdom    | 54              |
| David          | Male             | United States     | 83              |

Use of Formula **Q.1 How Many Male and Female Candidate in a List?**   Countif

Use of Formula **Q.2 How Many Male Employee in United States?**   Countifs

**Q.3 Lisa and John Which Country Belong?**   Use of Vlookup 

  

Use if Formula **Q.4 United States Male and Female Candidate Scores?**    Sumifs

**Q.5 How Many Male Candidate Belong Country United State Total Score?  **

  

** -17**

 **Use of Formulas - Vlookup ![ref3][ref3]**

| **ID** | **Brand** | **Product** |
| ------------ | --------------- | ----------------- |
| 101          | Dell            | Computer          |
| 102          | Logitech        | Keyboard          |
| 103          | Logitech        | Mouse             |
| 104          | HP              | Printer           |

| **ID** | **Brand** | **Product** |
| ------------ | --------------- | ----------------- |
| 104          | HP              | Printer           |
| 103          | ?               | ?                 |
| 104          | ?               | ?                 |
| 101          | ?               | ?                 |
| 102          | ?               | ?                 |
| 103          | ?               | ?                 |
| 101          | ?               | ?                 |
| 104          | ?               | ?                 |
| 101          | ?               | ?                 |
| 102          | ?               | ?                 |

**Use of Vlookup Function ?**

** -18**

**Use of Formulas - Hlookup  **

| **ID**      | 101      | 102      | 103      | 104     |
| ----------------- | -------- | -------- | -------- | ------- |
| **Brand**   | Dell     | Logitech | Logitech | HP      |
| **Product** | Computer | Keyboard | Mouse    | Printer |

| **ID** | **Product** |  | **Brand** |
| ------------ | ----------------- | :- | --------------- |
| 104          | Printer           |  | **HP**    |
| 103          | ?                 |  | **?**     |
| 104          | ?                 |  | **?**     |
| 101          | ?                 |  | **?**     |
| 102          | ?                 |  | **?**     |
| 103          | ?                 |  | **?**     |
| 101          | ?                 |  | **?**     |
| 104          | ?                 |  | **?**     |
| 101          | ?                 |  | **?**     |
| 102          | ?                 |  | **?**     |

  

** -19**

 **Use of Formulas - Index with Match  ![ref7][ref7]![ref7][ref7]**

| **Region** | **Jan** | **Feb** | **Mar** |
| ---------------- | ------------- | ------------- | ------------- |
| North            | 5,535         | 5,414         | 9,027         |
| South            | 5,013         | 5,107         | 11,667        |
| East             | 6,597         | 3,858         | 1,507         |
| West             | 3,195         | 3,654         | 7,225         |

| **East** | **Mar** | **1,507** |
| -------------- | ------------- | --------------- |
| West           | Feb           | ?               |
| South          | Jan           | ?               |
| North          | Mar           | ?               |

INDEX(A4:D8,MATCH(A10,A4:A8,0),MATCH(B10,A4:D4,0))

** -21**

 **Use of Formulas - Index + Match  **

| **Emp Name** | **Salary** | **Department** | **Emp ID** |
| ------------------ | ---------------- | -------------------- | ---------------- |
| Raju               | 92,671           | Sales                | Prd001           |
| Ramesh             | 84,120           | Operations           | Prd002           |
| Ramila             | 50,793           | Marketing            | Prd003           |
| Rajeshwari         | 77,833           | HR                   | Prd004           |
| Karan              | 58,914           | Finance              | Prd005           |
| Rohith             | 51,096           | IT                   | Prd006           |
| Jacob              | 83,735           | Marketing            | Prd007           |
| Fleming            | 74,418           | IT                   | Prd008           |
| Navya              | 51,366           | Sales                | Prd009           |
| Kavya              | 54,600           | Finance              | Prd010           |
| Santosh            | 93,509           | Operations           | Prd011           |
| Shankar            | 80,105           | Finance              | Prd012           |
| Rajesh             | 60,802           | Marketing            | Prd013           |
| Mahesh             | 76,260           | Sales                | Prd014           |
| Hemaraj            | 88,965           | IT                   | Prd015           |
| Nagaraj            | 63,288           | Operations           | Prd016           |
| Johson             | 45,742           | Sales                | Prd017           |
| David              | 88,354           | Marketing            | Prd018           |
| Anderson           | 76,641           | Marketing            | Prd019           |
| Peter              | 61,678           | Sales                | Prd020           |

| **Emp ID** |  | **Salary** |
| ---------------- | :- | ---------------- |
| Prd001           |  | 92,671           |
| Prd002           |  | ?                |
| Prd003           |  | ?                |
| Prd004           |  | ?                |
| Prd005           |  | ?                |
| Prd006           |  | ?                |
| Prd007           |  | ?                |
| Prd008           |  | ?                |
| Prd009           |  | ?                |
| Prd010           |  | ?                |
| Prd011           |  | ?                |
| Prd012           |  | ?                |
| Prd013           |  | ?                |
| Prd014           |  | ?                |
| Prd015           |  | ?                |
| Prd016           |  | ?                |
| Prd017           |  | ?                |
| Prd018           |  | ?                |
| Prd019           |  | ?                |
| Prd020           |  | ?                |

  

** -22**

**Use of Formulas - Lookup**

  17

| **Emp Name** | **Salary** | **Department** | **Emp ID** |
| ------------------ | ---------------- | -------------------- | ---------------- |
| Raju               | 92,671           | Sales                | Prd001           |
| Ramesh             | 84,120           | Operations           | Prd002           |
| Ramila             | 50,793           | Marketing            | Prd003           |
| Rajeshwari         | 77,833           | HR                   | Prd004           |
| Karan              | 58,914           | Finance              | Prd005           |
| Rohith             | 51,096           | IT                   | Prd006           |
| Jacob              | 83,735           | Marketing            | Prd007           |
| Fleming            | 74,418           | IT                   | Prd008           |
| Navya              | 51,366           | Sales                | Prd009           |
| Kavya              | 54,600           | Finance              | Prd010           |
| Santosh            | 93,509           | Operations           | Prd011           |
| Shankar            | 80,105           | Finance              | Prd012           |
| Rajesh             | 60,802           | Marketing            | Prd013           |
| Mahesh             | 76,260           | Sales                | Prd014           |
| Hemaraj            | 88,965           | IT                   | Prd015           |
| Nagaraj            | 63,288           | Operations           | Prd016           |
| Johson             | 45,742           | Sales                | Prd017           |
| David              | 88,354           | Marketing            | Prd018           |
| Anderson           | 76,641           | Marketing            | Prd019           |
| Peter              | 61,678           | Sales                | Prd020           |

Q.1 How Many Employee in Work HR, IT, Marketing Department ?  Q.2 Employee Santosh Salary?

Q.3 IT & Marketing Department Total Salary?



| **Emp ID** | **Salary** |
| ---------------- | ---------------- |
| Prd001           | 92,671           |
| Prd002           | ?                |
| Prd003           | ?                |
| Prd004           | ?                |
| Prd005           | ?                |
| Prd006           | ?                |
| Prd007           | ?                |
| Prd008           | ?                |
| Prd009           | ?                |
| Prd010           | ?                |
| Prd011           | ?                |
| Prd012           | ?                |
| Prd013           | ?                |
| Prd014           | ?                |
| Prd015           | ?                |
| Prd016           | ?                |
| Prd017           | ?                |
| Prd018           | ?                |
| Prd019           | ?                |
| Prd020           | ?                |

Use of Countif  Use of Sumif

Use of Sumif

** -23**

**Use of Formulas - AND **

| **NAME**   | **PHYSICS** | **CHEMISTRY** | **MATHS** | **BIOLOGY** | **PASSED THE EXAM ?** |
| ---------------- | ----------------- | ------------------- | --------------- | ----------------- | --------------------------- |
| **NITIN**  | PASS              | PASS                | FAIL            | PASS              | **FALSE**             |
| **FEROZ**  | PASS              | PASS                | PASS            | PASS              | **?**                 |
| **ANITHA** | PASS              | FAIL                | PASS            | PASS              | **?**                 |
| **MADAN**  | PASS              | PASS                | PASS            | PASS              | **?**                 |
| **HARRY**  | PASS              | FAIL                | PASS            | PASS              | **?**                 |
| **SUMITH** | FAIL              | PASS                | PASS            | PASS              | **?**                 |
| **HARSH**  | PASS              | PASS                | PASS            | FAIL              | **?**                 |

  

| **TRIVEDI** | PASS | PASS | FAIL | PASS | **?** |
| ----------------- | ---- | ---- | ---- | ---- | ----------- |
| **ASHISH**  | PASS | PASS | PASS | PASS | **?** |

**IN THIS EXAMPLE, IF STUDENT PASSES ALL THE SUBJECT, THEN HE HAS PASSED THE EXAM**

** -24**

**Use of Formulas - Averageif **

| **Product Name** |  | **Units sold** |
| ---------------------- | :- | -------------------- |
| A                      |  | 250\.00              |
| D                      |  | 110\.00              |
| E                      |  | 300\.00              |
| B                      |  | 50\.00               |
| C                      |  | 45\.00               |
| D                      |  | 23\.00               |
| F                      |  | 25\.00               |
| A                      |  | 90\.00               |
| D                      |  | 450\.00              |
| C                      |  | 23\.00               |
| A                      |  | 250\.00              |
| B                      |  | 25\.00               |

| **Student** |  | **Semester** |  | **Score** |
| ----------------- | :- | ------------------ | :- | --------------- |
| John              |  | second             |  | 90              |
| gary              |  | Third              |  | 77              |
| Richa             |  | second             |  | 80              |
| Hari              |  | second             |  | 65              |
| Tom               |  | Third              |  | 45              |
| Will              |  | Third              |  | 55              |

| Average semester score |              |
| ---------------------- | :----------- |
| **Second**       | 78\.33333333 |
| **Third**        | ?            |

| **Average of B** | 37\.5 |
| ---------------------- | ----- |
| **Average of D** | ?     |

| **Zone** | **City** | **Sales** |
| -------------- | -------------- | --------------- |
| South          | Chennai        | 25000           |
| East           | Patna          | 12000           |
| North          | Delhi          | 4200            |
| North          | Kanpur         | 5600            |
| West           | Gandhinagar    | 15000           |
| East           | Hubli          | 7000            |
| South          | Manglore       | 5200            |
| North          | Chandigarh     | 6000            |
| West           | Pune           | 8500            |
| south          | Hyderabad      | 12000           |
| North          | Meerut         | 4300            |
| West           | Nagpur         | 1200            |

| **Product Name** | **Units sold** |
| ---------------------- | -------------------- |
| A                      | 250\.00              |
| D                      | 110\.00              |
| E                      | 300\.00              |
| B                      | 50\.00               |
| C                      | 45\.00               |
| D                      | 23\.00               |
| F                      | 25\.00               |
| A                      | 90\.00               |
| D                      | 450\.00              |
| C                      | 23\.00               |
| A                      | 250\.00              |
| B                      | 25\.00               |

| **Average of West zone** |
| ------------------------------ |
| 8233\.33                       |

| **Avg of Units Sold above 250** | 375 |
| ------------------------------------- | --- |
| **Avg of Units Sold below 100** | ?   |

  

** -26**

**Use of If and Vlookup -Compare List 1 to List 2**

|  | **List 1** | **List 2** |  | **Result** |
| :- | ---------------- | ---------------- | :- | ---------------- |
|  | Raj              | Ankita           |  | Not Matching     |
|  | Rohit            | Rohit            |  | Matching         |
|  | Kajal            | Abhay            |  | Not Matching     |
|  | Rohan            | Rohan            |  | Matching         |
|  | Akshay           | Puneet           |  | Not Matching     |

|  | **List 1** | **List 2** |  | **Result**    |
| :- | ---------------- | ---------------- | :- | ------------------- |
|  | 343749           | 160466           |  | 160466              |
|  | 183257           | 183258           |  | Value not in List 1 |
|  | 160466           | 249447           |  | 249447              |
|  | 249447           | 343749           |  | 343749              |
|  | 532765           | 356160           |  | Value not in List 1 |
|  | 356163           | 379391           |  | 379391              |
|  | 455292           | 455292           |  | 455292              |
|  | 379391           | 532765           |  | 532765              |

**IF(A9=B9,"Matching","Not Matching")**

**VLOOKUP(F12,E5:E12,1,0)**

| **Color List-1** |
| ---------------------- |
| Red                    |
| Yellow                 |
| Green                  |
| Blue                   |
| Orange                 |
| White                  |

| **Result** |
| ---------------- |
| Red              |
| Yellow           |
| Green            |
| #N/A             |
| Orange           |
| #N/A             |

| **Color List-2** |
| ---------------------- |
| Red                    |
| Yellow                 |
| Grey                   |
| Green                  |
| Orange                 |
| Black                  |

**VLOOKUP(A17,E17:E22,1,FALSE)**

** -27**

**Use of Concatenate**

| **Emp ID** | **First Name** | **Last Name** | **Full Name**   |
| :--------------: | -------------------- | ------------------- | --------------------- |
|       D21       | Vishal               | Mohan               | Vishal Mohan          |
|       D22       | John                 | Mathew              | John Mathew           |
|       D23       | Jamemah              | Powel               | Jamemah Powel         |
|       D24       | Arundhati            | Swaminathan         | Arundhati Swaminathan |
|       D25       | Peter                | Potter              | Peter Potter          |
|       D26       | Roger                | Williams            | Roger Williams        |

- **CONCATENATE(B5," ",C5) **

| **Emp ID** | **First Name** | **Last Name** | **Full Name** |
| :--------------: | -------------------- | ------------------- | ------------------- |
|       D21       | Vishal               | Mohan               | Vishal Mohan        |
|       D22       | John                 | Mathew              | John Mathew         |

  

![ref4][ref4] D23   Jamemah   Powel   Jamemah Powel

- **B16&" "&C16**

** -28**

**Use of Counta, Countif, Countifs, Vlookup and Index with Match**

| **Employee Database** |                  |                |                       |               |
| --------------------------- | :--------------- | :------------- | :-------------------- | :------------ |
| **Date**              | **Emp Id** | **Name** | **Designation** | **KRA** |
| 01-11-2018                  | 1101             | ARUN           | MIS-OPERATION         | SALES         |
| 01-11-2018                  | 1102             | ASHOK          | OPERATION             | PHP           |
| 03-11-2018                  | 1103             | BISWAS         | SOFTWARE ENG          | JAVA          |
| 03-11-2018                  | 1104             | DINESH         | SME                   | MAILS         |
| 03-11-2018                  | 1105             | ESHWAR         | PROGRAMMER            | C++           |
| 06-11-2018                  | 1106             | FAHAD          | PROGRAMMER            | DOT NET       |
| 06-11-2018                  | 1107             | GANGA          | SOFTWARE ASSOCIATE    | TESTING       |
| 08-11-2018                  | 1108             | HEMA           | NETWORK ENG           | SERVER        |
| 08-11-2018                  | 1109             | FARZANA        | SALES EXECUTIVE       | SALES         |
| 08-11-2018                  | 1110             | AYESH          | SALES EXECUTIVE       | AMAZON        |
| 09-11-2018                  | 1111             | PRAVEEN        | SALES EXECUTIVE       | AMAZON        |
| 09-11-2018                  | 1109             | FARZANA        | SALES EXECUTIVE       | AMAZON        |
| 10-11-2018                  | 1112             | VISHAL         | SALES EXECUTIVE       | GROFFERS      |
| 10-11-2018                  | 1113             | VISHNU         | SALES EXECUTIVE       | PAYTM         |
| 10-11-2018                  | 1114             | KRISHNA        | SALES EXECUTIVE       | PAYTM         |
| 10-11-2018                  | 1115             | ABHISHEK       | SALES EXECUTIVE       | MYNTRA        |
| 11-11-2018                  | 1109             | FARZANA        | SALES EXECUTIVE       | AMAZON        |
| 11-11-2018                  | 1116             | FARZANA BANU   | SALES EXECUTIVE       | MYNTRA        |
| 11-11-2018                  | 1116             | FARZANA BANU   | SALES EXECUTIVE       | MYNTRA        |
| 11-11-2018                  | 1116             | FARZANA BANU   | SALES EXECUTIVE       | MYNTRA        |
| 01-नव्䵚र-18            | 1010             | VAMSEE KRISHNA | BRAND MANAGER         | MARKETING     |

**Q.1 How Many Employee?**   Use of Counta **QExe.2cHoutiwveM? any Employee in Sales**  Use of Countif

**Q.3 How Many Employee Sales Executive in Amazone and Myntra?**  Use of Countifs

**Q.4 Employee Dinesh and Vishal Post and KRA?**   use of Vlookup

**Q.5 Employee Abhishek and Hema Emp**

**id?**   Use of Index with Match  

  

** -29**

**Use of Vlookup One Sheet to Another Sheet**

**Sheet 1- Data**

| `<p>`**Emp** `</p><p>`**Id** `</p>` | **First Name** | **Last Name** | **Department** | **Location** |
| ----------------------------------------------------- | -------------------- | ------------------- | -------------------- | ------------------ |
| 101                                                   | Donald               | Patrick             | Finance              | Banglore           |
| 102                                                   | Samuel               | Samson              | Marketing            | Hyderabad          |
| 103                                                   | Ian                  | Jacob               | Finance              | Hyderabad          |
| 104                                                   | David                | Johnson             | Marketing            | Pune               |
| 105                                                   | Ian                  | Smith               | Marketing            | Banglore           |
| 106                                                   | Henry                | Madrid              | IT                   | Pune               |
| 107                                                   | Ronica               | Brave               | Finance              | Hyderabad          |
| 108                                                   | Christine            | Salvi               | Marketing            | Banglore           |
| 109                                                   | Andrew               | Baisley             | IT                   | Hyderabad          |
| 110                                                   | Erica                | Irons               | IT                   | Pune               |

**Sheet 2- Use of Vlookup**

| **Emp Id** | **First Name** | **Last Name** | **Department** | **Location** |
| :--------------: | -------------------- | ------------------- | -------------------- | ------------------ |
|       101       | Donald               | Patrick             | Finance              | Banglore           |
|       103       | ?                    | ?                   | ?                    | ?                  |
|       102       | ?                    | ?                   | ?                    | ?                  |
|       105       | ?                    | ?                   | ?                    | ?                  |
|       108       | ?                    | ?                   | ?                    | ?                  |
|       106       | ?                    | ?                   | ?                    | ?                  |
|       107       | ?                    | ?                   | ?                    | ?                  |
|       104       | ?                    | ?                   | ?                    | ?                  |
|       109       | ?                    | ?                   | ?                    | ?                  |
|       110       | ?                    | ?                   | ?                    | ?                  |

** -30**

**Get Pivot Table**

Pivo t Table Result Month   (All) 

| **Date of Sale** | **Month** | **Sales Amt** |
| ---------------------- | --------------- | ------------------- |
| 19-01-2018             | January         | 2,01,440            |
| 16-01-2018             | January         | 3,52,519            |
| 22-01-2018             | January         | 1,72,406            |

| **Date of Sale** | **Sum of Sales Amt** |
| ---------------------- | -------------------------- |
| 12-01-2018             | 2,40,000                   |

  

| 12-01-2018 | January  | 2,40,000 |
| ---------- | -------- | -------- |
| 05-02-2018 | February | 15,205   |
| 02-02-2018 | February | 24,327   |
| 13-02-2018 | February | 50,549   |
| 15-02-2018 | February | 15,106   |
| 15-02-2018 | February | 19,901   |
| 09-02-2018 | February | 15,205   |
| 22-02-2018 | February | 3,00,000 |
| 26-02-2018 | February | 1,50,000 |
| 26-02-2018 | February | 3,30,553 |
| 26-02-2018 | February | 1,63,282 |
| 27-02-2018 | February | 5,64,030 |
| 28-02-2018 | February | 5,03,599 |
| 28-02-2018 | February | 15,218   |
| 28-02-2018 | February | 2,01,440 |

| 16-01-2018            | 3,52,519            |
| --------------------- | ------------------- |
| 19-01-2018            | 2,01,440            |
| 22-01-2018            | 1,72,406            |
| 02-02-2018            | 24,327              |
| 05-02-2018            | 15,205              |
| 09-02-2018            | 15,205              |
| 13-02-2018            | 50,549              |
| 15-02-2018            | 35,007              |
| 22-02-2018            | 3,00,000            |
| 26-02-2018            | 6,43,835            |
| 27-02-2018            | 5,64,030            |
| 28-02-2018            | 7,20,256            |
| **Grand Total** | **33,34,777** |

** -31**

**USE OF HLOOKUP  **

| **Months** | January | February | March | April | May | June |
| ---------------- | ------- | -------- | ----- | ----- | --- | ---- |
| **Sale**   | 240     | 180      | 310   | 445   | 650 | 700  |

| **Months** | April |
| ---------------- | ----- |
| **Sale**   | ?     |

| **Name**    | Roger | Mat | Jim | Cole | Ricky | Mary |
| ----------------- | ----- | --- | --- | ---- | ----- | ---- |
| **Science** | 36    | 45  | 52  | 66   | 75    | 40   |
| **English** | 82    | 71  | 56  | 32   | 81    | 66   |
| **Maths**   | 32    | 45  | 52  | 51   | 71    | 74   |

| **Marks in English** | ? |
| -------------------------- | - |

| **Name**    | Roger | Mat | Jim | Cole | Ricky | Mary |
| ----------------- | ----- | --- | --- | ---- | ----- | ---- |
| **Science** | 36    | 45  | 52  | 66   | 75    | 40   |
| **English** | 82    | 71  | 56  | 32   | 81    | 66   |
| **Maths**   | 32    | 45  | 52  | 51   | 71    | 74   |

| **Marks in Maths** | ? |
| ------------------------ | - |

| **EMP**    | FIS6067 | FIS5228 | FIS6799 | FIS1149 | FIS5834 |
| ---------------- | ------- | ------- | ------- | ------- | ------- |
| **SALES1** | 66      | 43      | 36      | 82      | 89      |
| **SALES2** | 51      | 83      | 41      | 125     | 79      |

  

| **SALES3** | 35  | 97 | 92 | 41 | 39 |
| ---------------- | --- | -- | -- | -- | -- |
| **SALES4** | 84  | 76 | 35 | 48 | 37 |
| **SALES5** | 110 | 77 | 90 | 37 | 34 |

| **EMP**     | FIS1149 |
| ----------------- | ------- |
| **Sales 4** | ?       |

| **Temperarture (In Celsius)** | 21        | 33    | 39     | 42   | 50        |
| :---------------------------------: | --------- | ----- | ------ | ---- | --------- |
|          **Cities**          | New Delhi | Patna | Mumbai | Pune | Bangalore |

| **Temperature** | 40 |
| --------------------- | -- |
| **City**        | ?  |

| **Employee** | Albert | Aaron | Albama | Abeey | Carol | Cathy |
| ------------------ | ------ | ----- | ------ | ----- | ----- | ----- |
| **Sales**    | 200    | 125   | 320    | 250   | 300   | 421   |

| **Employee** | Cat |
| ------------------ | --- |
| **Sales**    | ?   |

** -32**

**USE OF NESTEDIF**

| **Name**   | **Total Numbers Earned** | **Grade earned** |
| ---------------- | :----------------------------: | ---------------------- |
| John Wilkins     |               92               | A+                     |
| Steve Harrington |               88               | A                      |
| Edward Clark     |               94               | A+                     |
| Jimmy Chemberlin |               84               | B+                     |
| Alex Wilkins     |               95               | A+                     |
| Patty Scott      |               78               | B                      |
| Andrew Williams  |               59               | D                      |
| Emilia johnson   |               43               | F                      |
| Anthony Rogers   |               90               | A+                     |

Condition List

| 90-100    | A+ |
| --------- | -- |
| 85 - < 90 | A  |
| 80 - < 85 | B+ |
| 75 - < 80 | B  |
| 70 - < 75 | C+ |
| 65 - < 70 | C  |
| 60 - < 65 | D+ |
| 50 - < 60 | D  |
| < 50      | F  |

** -33**

**Merge Table 1,2 & 3 Using Vlookup **

| **Table 1** |                    |
| ----------------- | :----------------- |
| **Emp ID**  | **Emp Name** |
| Prd001            | Raju               |
| Prd002            | Ramesh             |
| Prd003            | Ramila             |

| **Table 2** |                |
| ----------------- | :------------- |
| **Emp ID**  | **Dept** |
| Prd001            | Sales          |
| Prd002            | Operations     |
| Prd003            | Marketing      |

| **Table 3** |                  |
| ----------------- | :--------------- |
| **Emp ID**  | **Salary** |
| Prd001            | 92,671           |
| Prd002            | 84,120           |
| Prd003            | 50,793           |

  

| Prd004 | Rajeshwari |
| ------ | ---------- |
| Prd005 | Karan      |
| Prd006 | Rohith     |
| Prd007 | Jacob      |
| Prd008 | Fleming    |
| Prd009 | Navya      |
| Prd010 | Kavya      |
| Prd011 | Santosh    |
| Prd012 | Shankar    |
| Prd013 | Rajesh     |
| Prd014 | Mahesh     |
| Prd015 | Hemaraj    |
| Prd016 | Nagaraj    |
| Prd017 | Johson     |
| Prd018 | David      |
| Prd019 | Anderson   |
| Prd020 | Peter      |

| Prd013 | Marketing  |
| ------ | ---------- |
| Prd014 | Sales      |
| Prd015 | IT         |
| Prd016 | Operations |
| Prd017 | Sales      |
| Prd020 | Sales      |
| Prd004 | HR         |
| Prd005 | Finance    |
| Prd006 | IT         |
| Prd018 | Marketing  |
| Prd019 | Marketing  |
| Prd007 | Marketing  |
| Prd008 | IT         |
| Prd009 | Sales      |
| Prd010 | Finance    |
| Prd011 | Operations |
| Prd012 | Finance    |

| Prd004 | 77,833 |
| ------ | ------ |
| Prd005 | 58,914 |
| Prd006 | 51,096 |
| Prd015 | 88,965 |
| Prd016 | 63,288 |
| Prd017 | 45,742 |
| Prd018 | 88,354 |
| Prd019 | 76,641 |
| Prd020 | 61,678 |
| Prd007 | 83,735 |
| Prd008 | 74,418 |
| Prd009 | 51,366 |
| Prd010 | 54,600 |
| Prd011 | 93,509 |
| Prd012 | 80,105 |
| Prd013 | 60,802 |
| Prd014 | 76,260 |
  

** -34**

**Use of Sumif**

|  | **Owner** |  | **Product Class** |  | **Quantity  Sold** |
| :- | --------------- | :- | ----------------------- | :- | ------------------------ |
|  | Ben             |  | A1                      |  | 4615                     |
|  | Jeff            |  | A4                      |  | 2345                     |
|  | Ben             |  | C3                      |  | 11282                    |
|  | Jeff            |  | C14                     |  | 4159                     |
|  | Jenny           |  | A12                     |  | 7802                     |
|  | Ben             |  | B3                      |  | 8486                     |
|  | Jeff            |  | B7                      |  | 3384                     |
|  | Jenny           |  | B11                     |  | 3422                     |

| **Total Quantity Sold             By Ben** | 24383 |
| ------------------------------------------------ | ----- |

| **Total Quantity Sold             By Ben  & Jenny** | 35607 |
| --------------------------------------------------------- | ----- |

`SUMIF(A2:A9,"Ben",C2:C9)+SUMIF(A2:A9,"Jenny",C2:C9)`

|  | **Owner** |  | **Product Class** |  | **Quantity  Sold** |
| :- | --------------- | :- | ----------------------- | :- | ------------------------ |
|  | Ben             |  | A1                      |  | 4615                     |
|  | Jeff            |  | A4                      |  | 2345                     |
|  | Ben             |  | C3                      |  | 11282                    |
|  | Jeff            |  | C14                     |  | 4159                     |
|  | Jenny           |  | A12                     |  | 7802                     |
|  | Ben             |  | B3                      |  | 8486                     |
|  | Jeff            |  | B7                      |  | 3384                     |
|  | Jenny           |  | B11                     |  | 3422                     |



** -36**

USE OF VLOOKUP

| **Emp** | **First Name** | **Dept** | **Region** | **Salary** | **INCENTIVE** | **Bonus** | **TA** |
| ------------- | -------------------- | -------------- | ---------------- | ---------------- | ------------------- | --------------- | ------------ |
| 1             | Raja                 | Sales          | north            | 15625            |                     |                 |              |
| 2             | Suman                | Sales          | east             | 12500            |                     |                 |              |
| 3             | Beena                | Mktg           | north            | 8750             |                     |                 |              |
| 4             | Seema                | R&D            | north            | 15000            |                     |                 |              |
| 5             | Julie                | R&D            | north            | 8875             |                     |                 |              |
| 6             | Neena                | R&D            | north            | 8875             |                     |                 |              |
| 7             | Pankaj               | Sales          | north            | 10625            |                     |                 |              |
| 8             | Andre                | Mktg           | east             | 11250            |                     |                 |              |
| 9             | Sujay                | Finance        | west             | 10625            |                     |                 |              |
| 10            | Shilpa               | Admin          | north            | 15000            |                     |                 |              |
| 11            | Meera                | Finance        | east             | 13750            |                     |                 |              |
| 12            | Sheetal              | Director       | south            | 35000            |                     |                 |              |
| 13            | K. Sita              | Personal       | north            | 10625            |                     |                 |              |
| 14            | Priya                | Personal       | north            | 10625            |                     |                 |              |
| 15            | Aalok                | Admin          | east             | 11250            |                     |                 |              |
| 16            | Aakash               | Admin          | west             | 11250            |                     |                 |              |
| 17            | Parvati              | Mktg           | north            | 7500             |                     |                 |              |

| Dept     | INCENTIVE | Bonus |
| -------- | --------- | ----- |
| Sales    | 100       | 900   |
| Mktg     | 200       | 800   |
| R&D      | 300       | 700   |
| Finance  | 400       | 600   |
| Admin    | 500       | 500   |
| Director | 600       | 400   |
| Personal | 700       | 300   |
| CCD      | 800       | 200   |

| **Region** | **TA** |
| ---------------- | ------------ |
| north            | 100          |
| east             | 200          |
| west             | 300          |
| south            | 400          |

Q.1 How many Emloyee in Sales and Mktg Department.

Q.2 How Many salary in Sales Department.

Q.3 How many Employee Department Sales, North Region Salary.

Q.4 How many Employee Department Sales and Region north.

Q.5 If Salary Greater Then 15000, "A", if salary Greater Then 10000, "B" otherwise "C".

** -37**

***USE OF VLOOKUP** *

***WITH CONDITION TRUE/FALSE*  CONDITION  **

| **Empcode** | **First Name** | **Dept** | **Salary** | **Incentive** | **Grade** |
| ----------------- | -------------------- | -------------- | ---------------- | ------------------- | --------------- |
| 1                 | Raja                 | Sales          | 15,625           | 20%                 | D               |
| 2                 | Suman                | Sales          | 12,500           | ?                   | ?               |
| 3                 | Beena                | Mktg           | 8,750            | ?                   | ?               |
| 4                 | Seema                | R&D            | 15,000           | ?                   | ?               |
| 5                 | Julie                | R&D            | 8,875            | ?                   | ?               |
| 6                 | Neena                | R&D            | 8,875            | ?                   | ?               |

| **salary slab** | **incentive** | **grade** |
| :-------------------- | ------------------- | --------------- |
| 1                     | 5%                  | A               |
| 5001                  | 10%                 | B               |
| 10001                 | 15%                 | C               |
| 15001                 | 20%                 | D               |
| 20001                 | 25%                 | E               |
| 25001                 | 30%                 | F               |

  

  33

| 7  | Pankaj        | Sales    | 10,625 | ? | ? |
| -- | ------------- | -------- | ------ | - | - |
| 8  | Andre         | Mktg     | 11,250 | ? | ? |
| 9  | Sujay         | Finance  | 10,625 | ? | ? |
| 10 | Shilpa        | Admin    | 15,000 | ? | ? |
| 11 | Meera         | Finance  | 13,750 | ? | ? |
| 12 | Sheetal       | Director | 35,000 | ? | ? |
| 13 | K. Sita       | Personal | 10,625 | ? | ? |
| 14 | Priya         | Personal | 10,625 | ? | ? |
| 15 | Aalok         | Admin    | 11,250 | ? | ? |
| 16 | Aakash        | Admin    | 11,250 | ? | ? |
| 17 | Parvati       | Mktg     | 7,500  | ? | ? |
| 18 | Farhan        | Mktg     | 4,250  | ? | ? |
| 19 | Satinder Kaur | Mktg     | 5,625  | ? | ? |
| 20 | Suchita       | Mktg     | 5,625  | ? | ? |
| 21 | Shazia        | Mktg     | 5,625  | ? | ? |
| 22 | Pooja         | Sales    | 10,625 | ? | ? |
| 23 | Jasbinder     | R&D      | 5,625  | ? | ? |
| 24 | Bharat        | Sales    | 13,750 | ? | ? |
| 25 | Rishi         | Sales    | 9,375  | ? | ? |
| 26 | Mala          | R&D      | 7,500  | ? | ? |
| 27 | Hajra         | Admin    | 6,875  | ? | ? |
| 28 | Aalam         | Personal | 10,125 | ? | ? |
| 29 | Giriraj       | R&D      | 11,250 | ? | ? |
| 30 | Ankur         | CCD      | 11,250 | ? | ? |
| 31 | Tapan         | CCD      | 5,000  | ? | ? |
| 32 | Zarina        | CCD      | 6,250  | ? | ? |
| 33 | Arun          | Mktg     | 6,625  | ? | ? |
| 34 | Pooja         | Personal | 8,375  | ? | ? |
| 35 | Shilpa        | Finance  | 17,500 | ? | ? |
| 36 | Chitra        | Finance  | 17,500 | ? | ? |
| 37 | Sheetal       | Finance  | 17,500 | ? | ? |
| 38 | Richa         | Sales    | 7,500  | ? | ? |
| 39 | Kirtikar      | Admin    | 5,625  | ? | ? |
| 40 | Pooja         | R&D      | 9,500  | ? | ? |

30001  35%  G  35001  40%  H

** -38**

**USE OF DATEDIF FORMULAS CALCULATE DOB**

|  | FirstDate       |  | SecondDate |  | Interval   | Difference |
| :- | --------------- | :- | ---------- | :- | ---------- | ---------- |
|  | 01-जनवरI-60 |  | 10-मई-70 |  | days       | 3782       |
|  | 01-जनवरI-60 |  | 10-मई-70 |  | months     | 124        |
|  | 01-जनवरI-60 |  | 10-मई-70 |  | years      | 10         |
|  | 01-जनवरI-60 |  | 10-मई-70 |  | yeardays   | 130        |
|  | 01-जनवरI-60 |  | 10-मई-70 |  | yearmonths | 4          |

`=DATEDIF(C4,D4,"d")  =DATEDIF(C5,D5,"m")  =DATEDIF(C6,D6,"y")  =DATEDIF(C7,D7,"yd")` 

  

|                 |            |           |   |
| :-------------- | :--------- | :-------- | :- |
| 01-जनवरI-60 | 10-मई-70 | monthdays | 9 |

=DATEDIF(C8,D8,"ym") =DATEDIF(C9,D9,"md")

**What Does It Do?**

| This function calculates the difference between two dates. It can show the result in weeks, months or years.                                                                                                                                                                                                                                                                                                                                                                                                                      |  |
| :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :- |
| **Syntax**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |  |
| `<p>`=DATEDIF(FirstDate,SecondDate,"Interval") `</p><p>`FirstDate : This is the earliest of the two dates. `</p><p>`SecondDate : This is the most recent of the two dates. `</p><p>`"Interval" : This indicates what you want to calculate. `</p><p>`These are the available intervals. `</p><p>`"d"  Days between the two dates. `</p><p>`"m"  Months between the two dates. `</p><p>`"y"  Years between the two dates. `</p><p>`"yd"  Days between the dates, as if the dates were in the same year. `</p>` |  |
| "ym"  Months between the dates, as if the dates were in the same year.                                                                                                                                                                                                                                                                                                                                                                                                                                                            |  |
| "md"  Days between the two dates, as if the dates were in the same month and year.                                                                                                                                                                                                                                                                                                                                                                                                                                                |  |
| **Formatting**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |  |
| No special formatting is needed.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |  |

| Birth date : | 01-जनवरI-60 |
| ------------ | --------------- |

| Years lived :    | 61 |
| ---------------- | -- |
| and the months : | 3  |
| and the days :   | 24 |

=DATEDIF(C8,TODAY(),"y")

=DATEDIF(C8,TODAY(),"ym")  =DATEDIF(C8,TODAY(),"md")

You can put this all together in one calculation, which creates a text version. Age is 61 Years, 3 Months and 24 Days

="Age is "&DATEDIF(C8,TODAY(),"y")&" Years, "&DATEDIF(C8,TODAY(),"ym")&" Months and "&DATEDIF(C8,TODAY(),"md")&" Days"

** -44**

**USE OF FIND & LARGE FORMULA**

| Text          | Letter To Find | Position Of Letter |
| ------------- | -------------- | ------------------ |
| Hello         | e              | 2                  |
| Hello         | H              | 1                  |
| Hello         | o              | 5                  |
| Alan Williams | a              | 3                  |

`=FIND(D4,C4)  =FIND(D5,C5)  =FIND(D6,C6)  =FIND(D7,C7)` 

  

`Alan Williams  a  11  =FIND(D8,C8,6) Alan Williams  T  #VALUE!  =FIND(D9,C9)`

| Highest Value     | 800 |
| ----------------- | --- |
| 2nd Highest Value | 250 |
| 3rd Highest Value | 120 |
| 4th Highest Value | 120 |
| 5th Highest Value | 100 |

Values 120 800 100 120 250

=LARGE(C4:C8,1)  =LARGE(C4:C8,2)  =LARGE(C4:C8,3)  =LARGE(C4:C8,4)  =LARGE(C4:C8,5)

**What Does It Do ?**

| This function examines a list of values and picks the value at a user specified position    |  |  |
| ------------------------------------------------------------------------------------------- | :- | :- |
| in the list.                                                                                |  |  |
| **Syntax**                                                                            |  |  |
| =LARGE(ListOfNumbersToExamine,PositionToPickFrom)                                           |  |  |
| **Formatting**                                                                        |  |  |
| No special formatting is needed.                                                            |  |  |
| **Example**                                                                           |  |  |
| The following table was used to calculate the top 3 sales figures between Jan, Feb and Mar. |  |  |

| Sales | Jan      | Feb     | Mar      |
| ----- | -------- | ------- | -------- |
| North | £5,000  | £6,000 | £4,500  |
| South | £5,800  | £7,000 | £3,000  |
| East  | £3,500  | £2,000 | £10,000 |
| West  | £12,000 | £4,000 | £6,000  |

| Highest Value     | £12,000 |
| ----------------- | -------- |
| 2nd Highest Value | £10,000 |
| 3rd Highest Value | £7,000  |

=LARGE(D24:F27,1)  =LARGE(D24:F27,2)  =LARGE(D24:F27,3)

**Note**  Another way to find the Highest and Lowest values would have been to use

the =MAX() and =MIN() functions.

| Highest | £12,000 |
| ------- | -------- |
| Lowest  | £2,000  |

=MAX(D24:F27)  =MIN(D24:F27) 

  

** -45**

**USE OF LEFT, FIND, LEN,LOWER, NETWORKDAYS**

**USE OF LEFT**

| `<p>`Number Of `</p><p>`Text  Characters Required  Left String `</p>` |
| --------------------------------------------------------------------------- |
| Alan Jones  1  A                                                            |
| Alan Jones  2  Al                                                           |
| Alan Jones  3  Ala                                                          |
| Cardiff  6  Cardif                                                          |
| ABC123  4  ABC1                                                             |

LEFT(A5,B5)

| Full Name      | First Name |
| -------------- | ---------- |
| Alan Jones     | Alan       |
| Bob Smith      | Bob        |
| Carol Williams | Carol      |

=LEFT(A12,FIND(" ",A12)-1)

|  | Text           | Length |
| :- | -------------- | ------ |
|  | Alan Jones     | 10     |
|  | Bob Smith      | ?      |
|  | Carol Williams | ?      |
|  | Cardiff        | ?      |
|  | ABC123         | ?      |

=LEN(A18)

|  | Upper Case Text |  | Lower Case |
| :- | --------------- | :- | ---------- |
|  | ALAN JONES      |  | alan jones |
|  | BOB SMITH       |  | ?          |
|  | CAROL WILLIAMS  |  | ?          |
|  | CARDIFF         |  | ?          |
|  | ABC123          |  | ?          |

=LOWER(A27)

**USE OF NETWORKDAYS**

| Start Date                                | End Date        | Work Days |
| ----------------------------------------- | --------------- | --------- |
| 01-म?रきच-98                           | 07-म?रきच-98 | 5         |
| 25-अल-98                                | 30-जJल?ई-98  | 69        |
| `<p>`24-/िसर `</p><p>`-98 `</p>` | 05-जनवरI-99 | 9         |

`=NETWORKDAYS(A36,B36)` 

  

** -46**

**USE OF POWER, PRODUCT, PROPER, REPT USE OF POWER**

| Number  Power  Result |
| --------------------- |
| 3  2  9               |
| 3  4  ?               |
| 5  2  ?               |
| 5  4  ?               |

=POWER(A5,B5)

**USE OF PRODUCT**

Numbers  Product

2  3  6  =PRODUCT(A12,B12) 5  10  ?

3  7  ?

6300

|  | Original Text  | Proper     |
| :- | -------------- | ---------- |
|  | alan jones     | Alan Jones |
|  | bob smith      | ?          |
|  | caRol wILLIAMS | ?          |
|  | cardiff        | ?          |
|  | ABC123         | ?          |

**USE OF PROPER**

=PROPER(A19)

**USE OF REPT**

|  | Text To  Number Of  Repeated Repeat  Repeats  Text |
| :- | :------------------------------------------------- |
|  | A  3  AAA                                          |
|  | AB  3  ?                                           |
|  | -  10  ?                                           |
|  |                                                    |

=REPT(A27,B27)

** -48 **

| **SALESMAN** | **JAN** | **FEB** | **MAR** | **APR** | **MAY** | **JUNE** | **SALES** | **TARGET** | **RESULT** | **comission** |
| ------------------ | ------------- | ------------- | ------------- | ------------- | ------------- | -------------- | --------------- | ---------------- | ---------------- | ------------------- |
| RAMESH             | 2000          | 1500          | 300           | 1400          | 1000          | 1400           | 7600            | 10000            | NOT ACHIVED      | 380                 |
| RAKESH             | 5000          | 1200          | 500           | 1200          | 1200          | 2800           | 11900           | 12000            | NOT ACHIVED      | 595                 |
| RAHUL              | 3000          | 800           | 1200          | 3000          | 1500          | 3500           | 13000           | 18000            | NOT ACHIVED      | 650                 |
| POOJA              | 1000          | 900           | 1800          | 5000          | 1400          | 1200           | 11300           | 10000            | ACHIEVED         | 1130                |
| MANOJ              | 500           | 1000          | 2300          | 8000          | 1700          | 1400           | 14900           | 12000            | ACHIEVED         | 1490                |

  

| ASHOK    | 800  | 500  | 2400 | 1900 | 1800 | 1800 | 9200  | 10000 | NOT ACHIVED | 460  |
| -------- | ---- | ---- | ---- | ---- | ---- | ---- | ----- | ----- | ----------- | ---- |
| AJEET    | 1200 | 1400 | 1500 | 700  | 2500 | 7000 | 14300 | 12000 | ACHIEVED    | 1430 |
| ALOK     | 1500 | 1800 | 1800 | 1800 | 300  | 1500 | 8700  | 10000 | NOT ACHIVED | 435  |
| AMRIT    | 1800 | 2500 | 1700 | 1500 | 2800 | 1800 | 12100 | 12000 | ACHIEVED    | 1210 |
| SURENDRA | 200  | 3000 | 1900 | 1200 | 1500 | 3000 | 10800 | 10000 | ACHIEVED    | 1080 |
| SHASHI   | 1600 | 1200 | 2000 | 800  | 1700 | 800  | 8100  | 10000 | NOT ACHIVED | 405  |

USE OF COUNTA  AND

Q.1 How many salesman? Salesman Ajeet Targest & Result?  VLOOKUP

Q.3 Rahul Pooja & Ashok Targest & result?  USE OF VLOOKUP

Q.4 How Many Salesman Achived Target.  USE OF COUNTIF

Q.5 Which Sales Man Jan Sales 2000, & Feb Sales is 2500?  USE OF LOOKUP

USE OF

Q.6 How Many sales Man sales Jan Months Sales >2000 & March Sales <=1500 ?  COUNTIFS

USE OF

CONDITIONL Q.7 Jan to Target Highlights 2000 between 5000, Font Red & Background Yeloow?  F

UEE OF IF Q.8 If sales Greter then Target then Comission 10% otherwise 5% ?  FUNCTION

** -49**

| **SALESMAN** | **JAN** | **FEB** | **MAR** | **APR** | **MAY** | **JUNE** | **SALES** | **TARGET** | **RESULT** |
| ------------------ | ------------- | ------------- | ------------- | ------------- | ------------- | -------------- | --------------- | ---------------- | ---------------- |
| RAMESH             | 2000          | 1500          | 300           | 1400          | 1000          | 1400           | 7600            | 10000            | NOT ACHIVED      |
| RAKESH             | 5000          | 1200          | 500           | 1200          | 1200          | 2800           | 11900           | 12000            | NOT ACHIVED      |
| RAHUL              | 3000          | 800           | 1200          | 3000          | 1500          | 3500           | 13000           | 18000            | NOT ACHIVED      |
| POOJA              | 1000          | 900           | 1800          | 5000          | 1400          | 1200           | 11300           | 10000            | ACHIEVED         |
| MANOJ              | 500           | 1000          | 2300          | 8000          | 1700          | 1400           | 14900           | 12000            | ACHIEVED         |
| ASHOK              | 800           | 500           | 2400          | 1900          | 1800          | 1800           | 9200            | 10000            | NOT ACHIVED      |
| AJEET              | 1200          | 1400          | 1500          | 700           | 2500          | 7000           | 14300           | 12000            | ACHIEVED         |
| ALOK               | 1500          | 1800          | 1800          | 1800          | 300           | 1500           | 8700            | 10000            | NOT ACHIVED      |
| AMRIT              | 1800          | 2500          | 1700          | 1500          | 2800          | 1800           | 12100           | 12000            | ACHIEVED         |
| SURENDRA           | 200           | 3000          | 1900          | 1200          | 1500          | 3000           | 10800           | 10000            | ACHIEVED         |
| SHASHI             | 1600          | 1200          | 2000          | 800           | 1700          | 800            | 8100            | 10000            | NOT ACHIVED      |

  43

Q.1 How many salesman? Salesman Ajeet Targest & Result? Q.3 Rahul Pooja & Ashok Targest & result?

Q.4 How Many Salesman Achived Target.

Q.5 Which Sales Man Jan Sales 2000, & Feb Sales is 2500?

Q.6 How Many sales Man sales Jan Months Sales >2000 & March Sales <=1500 ?

Q.7 Jan to Target Highlights 2000 between 5000, Font Red & Background Yeloow?

USE OF COUNTA AND VLOOKUP USE OF VLOOKUP

* USE OF COUNTIF
* USE OF LOOKUP

USE OF COUNTIF

USE OF CONDITIONAL FORMATTING

** -50**

**USE OF DATEDIF**

| NAME     | DATE OF BIRTH | DAY | MONTH | YEAR |
| -------- | ------------- | --- | ----- | ---- |
| RAMESH   | 15-05-1980    | 10  | 3     | 40   |
| RAKESH   | 20-08-1981    | ?   | ?     | ?    |
| RAHUL    | 15-10-2003    | ?   | ?     | ?    |
| POOJA    | 25-05-1990    | ?   | ?     | ?    |
| MANOJ    | 24-08-1992    | ?   | ?     | ?    |
| ASHOK    | 23-08-1998    | ?   | ?     | ?    |
| AJEET    | 12-05-1980    | ?   | ?     | ?    |
| ALOK     | 18-03-2005    | ?   | ?     | ?    |
| AMRIT    | 15-08-2007    | ?   | ?     | ?    |
| SURENDRA | 25-05-2010    | ?   | ?     | ?    |
| SHASHI   | 25-08-1993    | ?   | ?     | ?    |

Q.1 HOW MANY STUDENT?

Q.2 STUDENT SURENDRA IS HOW MANY YEAR OLD?

Q.3 HOW MANY STUDENT AGE GREATER THEN 20 YEARS?

Q.4 IF STUDENT AGE IS GREATHER THEN 20 THEN STUDENT ADULT / CHIL D?

Q.5 HOW MANY STUDENT AGE IS >= 25 YEARS?
