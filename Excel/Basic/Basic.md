### Result

| Enrollment No | Name    | Hindi | English | Math | SST | Science | Total | Percentage | Pass/Fail | Scholarship | Rank |
|---------------|---------|-------|---------|------|-----|---------|-------|------------|-----------|-------------|------|
| 2352787283    | Anshu   | 85    | 90      | 78   | 82  | 88      | 423   | 84.60      | Pass      | Yes         | 2    |
| 9876543210    | John    | 92    | 88      | 76   | 85  | 79      | 420   | 84.00      | Pass      | No          | 4    |
| 3456789012    | Emily   | 78    | 95      | 82   | 88  | 85      | 428   | 85.60      | Pass      | Yes         | 1    |
| 1122334455    | Michael | 88    | 85      | 90   | 79  | 91      | 433   | 86.60      | Pass      | Yes         | 3    |
| 9988776655    | Sarah   | 75    | 91      | 85   | 92  | 83      | 426   | 85.20      | Pass      | No          | 5    |
| 6677889900    | David   | 89    | 93      | 79   | 86  | 87      | 434   | 86.80      | Pass      | Yes         | 2    |
| 5544332211    | Emma    | 80    | 87      | 94   | 81  | 94      | 436   | 87.20      | Pass      | Yes         | 1    |
| 1122334455    | James   | 94    | 84      | 88   | 87  | 88      | 441   | 88.20      | Pass      | Yes         | 3    |
| 9988776655    | Lily    | 87    | 92      | 76   | 89  | 76      | 420   | 84.00      | Pass      | No          | 4    |
| 6677889900    | Ethan   | 91    | 89      | 83   | 90  | 79      | 432   | 86.40      | Pass      | Yes         | 2    |
| 5544332211    | Olivia  | 82    | 96      | 81   | 91  | 81      | 431   | 86.20      | Pass      | Yes         | 1    |
| 1122334455    | Daniel  | 85    | 87      | 92   | 88  | 82      | 434   | 86.80      | Pass      | Yes         | 3    |
| 9988776655    | Ava     | 79    | 94      | 87   | 93  | 87      | 440   | 88.00      | Pass      | Yes         | 3    |
| 6677889900    | Benjamin| 90    | 82      | 95   | 94  | 89      | 450   | 90.00      | Pass      | Yes         | 1    |
| 5544332211    | Mia     | 93    | 86      | 89   | 95  | 90      | 453   | 90.60      | Pass      | Yes         | 1    |

1. **Total Marks:**
   - Formula: `Total Marks = Subject1 + Subject2 + Subject3 + ...`

2. **Percentage:**
   - Formula: `Percentage = (Total Marks / Total Possible Marks) * 100`

3. **Pass/Fail:**
   - Formula (Assuming passing criteria is 40%): `Pass/Fail = IF(Percentage >= 40, "Pass", "Fail")`

4. **Rank (Assuming descending order):**
   - Formula: `Rank = RANK(Percentage, Descending Order)`

5. **Scholarship (Assuming top 3 students):**
   - Formula: `Scholarship = IF(Rank <= 3, "Yes", "No")`

| Enrollment No | Name  | Hindi | English | Math | SST | Science | Total | Percentage | Pass/Fail | Rank | Scholarship |
|---------------|-------|-------|---------|------|-----|---------|-------|------------|-----------|------|-------------|
| 2352787283    | Anshu | 85    | 90      | 78   | 82  | 88      | =SUM(B2:F2) | =(G2 / 500) * 100 | =IF(H2 >= 40, "Pass", "Fail") | =RANK(E2, $E$2:$E$16, 0) | =IF(I2 <= 3, "Yes", "No") |

In this example:
- Total is calculated using the SUM function for the marks in columns B to F.
- Percentage is calculated by dividing the Total by the total possible marks (500 in this case) and then multiplying by 100.
- Pass/Fail is determined based on whether the Percentage is greater than or equal to 40.
- Rank is calculated using the RANK function in descending order.
- Scholarship is given to the top 3 students based on their rank.

### Attendence Sheet

| Serial No. | Student Name      | Enrolment No. | Date       | Status (Present/Absent) |
|------------|-------------------|----------------|------------|--------------------------|
| 1          | John Doe          | 123456789      | 01-01-2024 |                          |
| 2          | Jane Smith        | 987654321      | 01-01-2024 |                          |
| 3          | Bob Johnson       | 567890123      | 01-01-2024 |                          |
| 4          | Alice Williams    | 234567890      | 01-01-2024 |                          |
| 5          | Charlie Brown     | 345678901      | 01-01-2024 |                          |
| 6          | Emily Davis       | 789012345      | 01-01-2024 |                          |
| 7          | Michael Johnson   | 456789012      | 01-01-2024 |                          |
| 8          | Olivia Taylor     | 901234567      | 01-01-2024 |                          |
| 9          | David Smith       | 112233445      | 01-01-2024 |                          |
| 10         | Sophia Miller     | 556677889      | 01-01-2024 |                          |
| ...        | ...               | ...            | ...        |                          |

### Questions:
1. **Basic Attendance Check:**
   - Q: On 01-01-2024, was John Doe present or absent in class?
   
2. **Percentage Attendance:**
   - Q: Calculate the attendance percentage for Jane Smith based on the total number of classes held and the number of classes attended.

3. **Total Absences:**
   - Q: How many classes did Bob Johnson miss in the month of January 2024?

4. **Dynamic Date Calculation:**
   - Q: Using a formula, determine the attendance status of Alice Williams on 15-02-2024.

5. **Late Entry Consideration:**
   - Q: If Charlie Brown arrives 15 minutes late to each class, should it be considered as a full presence or partial presence?

### Formulas:
- PRESENT = IFCOUNT(RANGE,"P")
- ABSENT = IFCOUNT(RANGE,"A")
- LATE = IFCOUNT(RANGE,"L")

### Salary Slip Sheet

| S.No | Post          | Basic | HRA  | CCA  | DA   | OD   | OI   | PF   |
|------|---------------|-------|------|------|------|------|------|------|
| 1    | Doctor        | 35000 | 10500| 7000 | 3500 | 0    | 2100 | 3500 |
| 2    | Engineer       | 25000 | 7500 | 5000 | 2500 | 0    | 1500 | 2500 |
| 3    | Teacher        | 18000 | 5400 | 3600 | 1800 | 0    | 1080 | 1800 |
| 4    | Manager        | 26000 | 7800 | 5200 | 2600 | 0    | 1560 | 2600 |
| 5    | Scientist      | 34000 | 10200| 6800 | 3400 | 0    | 2040 | 3400 |
| 6    | A/C Manager    | 15000 | 4500 | 3000 | 1500 | 0    | 900  | 1500 |
| 7    | AC             | 8008  | 2402 | 1601 | 800  | 0    | 480  | 800  |
| 8    | Police Officer | 102008| 30602| 20401| 10200| 0    | 6120 | 10200|
| 9    | Supervisor As  | 8000  | 2400 | 1600 | 800  | 0    | 480  | 800  |
| 10   | Hardware       | 3000  | 900  | 600  | 300  | 0    | 180  | 300  |



### Questions and Explanations:

- HRA (HOUSE RENT ALLOWANCE) = if(basic>18000,Basic*"30%",basic*"20%")
- C.C.A CITY CONVINCE ALLOWANCE) = if(basic>18000,Basic*"20%",basic*"15%")
- D.A (DEARNESS ALLOWANCE) = if(basic>18000,Basic*"12%",basic*"10%")
- OI (OTHER INCLUDES) = FIXED ACCORDINGLY
- OD (OTHER DEDUCTION) = FIXED ACCORDINGLY
- PF (PROVIDENT FUND)
  
### Information
- HRA (House Rent Allowance): 
  ```
  HRA = if(Basic > 18000, Basic * 0.30, Basic * 0.20)
  ```
- CCA (City Conveyance Allowance): 
  ```
  CCA = if(Basic > 18000, Basic * 0.20, Basic * 0.15)
  ```
- DA (Dearness Allowance): 
  ```
  DA = if(Basic > 18000, Basic * 0.12, Basic * 0.10)
  ```
- OI (Other Includes): Fixed, so no calculation needed.

- OD (Other Deduction): Fixed, so no calculation needed.

- PF (Provident Fund): Fixed value specified in the table.

### Car Showroom Sheet

| S.No | Vehicle | Factory Price | Tax (4%) | Transport Cash | Cost Price | Showroom Price | Profit (9%) | Road Tax (2%) | Insurance (3%) | Sale Price | Down Payment | Balance | Interest | Year | Total Amount |
|------|---------|---------------|----------|-----------------|------------|----------------|-------------|---------------|------------------|------------|--------------|---------|----------|------|--------------|
| 1    | Car A   | 25000         | 1000     | 500             | 26500      | 28500          | 2565        | 570           | 855              | 30425      | 10000        | 20425   | 1634.00  | 1    | 22059.00     |
| 2    | Bike B  | 12000         | 480      | 300             | 12780      | 13780          | 1240        | 275           | 413              | 14688      | 5000         | 9688    | 775.04   | 2    | 10937.04     |
| 3    | Car C   | 30000         | 1200     | 700             | 31700      | 34400          | 3096        | 688           | 1032             | 38640      | 12000        | 26640   | 2131.20  | 3    | 29465.20     |
| 4    | Bike D  | 8000          | 320      | 200             | 8520       | 9220           | 829         | 184           | 276              | 10305      | 4000         | 6305    | 504.40   | 4    | 7649.40      |
| 5    | Car E   | 35000         | 1400     | 800             | 37200      | 40500          | 3645        | 810           | 1215             | 45420      | 15000        | 30420   | 2433.60  | 5    | 32853.60     |
| 6    | Bike F  | 5000          | 200      | 100             | 5300       | 5700           | 513         | 114           | 171              | 6384       | 2000         | 4384    | 350.72   | 6    | 5734.72      |
| 7    | Car G   | 45000         | 1800     | 1000            | 47800      | 52100          | 4689        | 1042          | 1563             | 61704      | 20000        | 41704   | 3336.32  | 7    | 45040.32     |
| 8    | Bike H  | 7000          | 280      | 150             | 7430       | 8000           | 720         | 160           | 240              | 9520       | 3000         | 6520    | 521.60   | 8    | 7177.60      |
| 9    | Car I   | 28000         | 1120     | 600             | 29800      | 32400          | 2916        | 648           | 972              | 38316      | 13000        | 25316   | 2025.28  | 9    | 27341.28     |
| 10   | Bike J  | 6000          | 240      | 120             | 6360       | 6840           | 615         | 136           | 204              | 8055       | 2500         | 5555    | 444.40   | 10   | 6000.40      |
| ...  | ...     | ...           | ...      | ...             | ...        | ...            | ...         | ...           | ...              | ...        | ...          | ...     | ...      | ...  | ...          |

- Tax 4% Factory Price*4%.
- Transport cash = 500/10=50
- Cash Price = factory Price + Taxt Transport+Cash
- Showroom Tax 6% = Cost Price * 6%
- Profit 9% = (Cost Price t showroom Tex) * 9%
- Showroom Price = Cost Price + showroom Tax + Profit
- Road Tax 2% = showroom Price *3%
- Sale Price = Showroom + Road Tax + Insurance
- Down Rayment = 25000
- Balance = Sale Price - Down Payment
- Interest = Balance 9%
- Year = 2
- Total Amt = Balance + Interest
- Month = 12*2
- Installement = total Amt/month

### Items Stock Sheet

| Items | Stock | P.Price | S.Price | Sale | Rstock | A.Price | Sale Value | Profit |
|-------|-------|---------|---------|------|--------|---------|------------|--------|
| Item1 | 100   | $5      | $8      | 20   | 80     | $5.25   | $160       | $60    |
| Item2 | 50    | $10     | $15     | 10   | 40     | $10.25  | $150       | $40    |
| Item3 | 75    | $3      | $6      | 25   | 50     | $3.30   | $150       | $75    |
| Item4 | 120   | $2      | $4      | 30   | 90     | $2.11   | $120       | $60    |
| Item5 | 200   | $8      | $12     | 50   | 150    | $8.40   | $600       | $300   |
| Item6 | 30    | $15     | $25     | 5    | 25     | $15.00  | $125       | $10    |
| Item7 | 80    | $6      | $10     | 15   | 65     | $6.00   | $150       | $30    |
| Item8 | 40    | $12     | $18     | 10   | 30     | $12.40  | $180       | $60    |
| Item9 | 60    | $4      | $7      | 20   | 40     | $4.20   | $140       | $60    |
| Item10| 90    | $9      | $14     | 25   | 65     | $8.77   | $350       | $115   |

### Meaning
- P.Price = Purchase Price
- S.Price = Sale Price
- Sale = Yourself
### Formulas:
- R.Stock = Stock - Sale
- A.Price = P.Price * Sale
- Sale Value = S.Price * Sale
- Profit = Sale Value - A.Price


### Table 1: Basic Operations

| A       | B        | C          | D     | E           |
| ------- | -------- | ---------- | ----- | ----------- |
| Item    | Quantity | Unit Price | Total |             |
| Laptop  | 2        | $800       |       |             |
| Printer | 1        | $150       |       |             |
| Monitor | 3        | $200       |       |             |
| TOTAL   |          |            |       | =SUM(D2:D4) |

**Questions:**

1. What formula should be entered in cell D2 to calculate the total cost of the laptops?
2. How can you copy the formula from D2 to calculate the total cost for the printer and monitor?

### Table 2: Budget Tracker

| A              | B                 | C           |
| -------------- | ----------------- | ----------- |
| Category       | Budget            | Expense     |
| Groceries      | $300       | $250 |             |
| Entertainment  | $150       | $120 |             |
| Transportation | $100      | $80   |             |
| TOTAL          | =SUM(B2:B4)       | =SUM(C2:C4) |

**Questions:**

1. How do you use the SUM function to calculate the total budget in cell B5?
2. What formula would you use in cell C5 to calculate the total expenses?

### Table 3: Gradebook

| Student | Quiz 1      | Quiz 2      | Quiz 3      | Total       | Average         |
| ------- | ----------- | ----------- | ----------- | ----------- | --------------- |
| John    | 85          | 90          | 88          |             |                 |
| Jane    | 92          | 87          | 94          |             |                 |
| Bob     | 78          | 80          | 75          |             |                 |
| TOTAL   | =SUM(B2:B4) | =SUM(C2:C4) | =SUM(D2:D4) | =SUM(E2:E4) | =AVERAGE(E2:E4) |

**Questions:**

1. How can you use the SUM function to find the total score for Quiz 1 (cell B5)?
2. What formula would you use in cell F2 to calculate the average score for Quiz 1?

### Table 4: Sales Data Analysis

| Month    | Product A         | Product B   | Total Sales |
| -------- | ----------------- | ----------- | ----------- |
| January  | $500       | $700 | =SUM(B2:C2) |             |
| February | $600       | $800 | =SUM(B3:C3) |             |
| March    | $750       | $900 | =SUM(B4:C4) |             |
| TOTAL    | =SUM(B2:B4)       | =SUM(C2:C4) | =SUM(D2:D4) |

**Questions:**

1. How can you calculate the total sales for Product A in cell B5?
2. What formula should be entered in cell D2 to find the total sales for January?

### Table 5: Project Timeline

| Task          | Start Date | End Date   | Duration    |
| ------------- | ---------- | ---------- | ----------- |
| Research      | 2023-01-15 | 2023-01-30 | =B3-B2      |
| Planning      | 2023-02-01 | 2023-02-15 | =B4-B3      |
| Execution     | 2023-02-20 | 2023-03-15 | =B5-B4      |
| Evaluation    | 2023-03-20 | 2023-04-05 | =B6-B5      |
| TOTAL PROJECT |            |            | =SUM(D2:D5) |

**Questions:**

1. How can you calculate the duration of the Research task in cell D2?
2. What formula would you use in cell D6 to find the total duration of the project?

### Table 6: Inventory Management

| Product | Initial Stock | Purchases   | Sales       | Remaining Stock |
| ------- | ------------- | ----------- | ----------- | --------------- |
| Item 1  | 100           | 50          | 30          | =B2+C2-D2       |
| Item 2  | 150           | 20          | 40          | =B3+C3-D3       |
| Item 3  | 200           | 30          | 25          | =B4+C4-D4       |
| TOTAL   | =SUM(B2:B4)   | =SUM(C2:C4) | =SUM(D2:D4) | =SUM(E2:E4)     |

**Questions:**

1. How can you use a formula to calculate the remaining stock for Item 1 in cell E2?
2. What function would you use in cell B5 to find the total initial stock?

### Table 7: Payroll Calculation

| Employee | Hours Worked | Hourly Rate                        | Overtime Hours   | Overtime Rate | Total Earnings |
| -------- | ------------ | ---------------------------------- | ---------------- | ------------- | -------------- |
| John     | 40           | $20         | 5              | $30 | =B2*C2 + D2*E2 |               |                |
| Jane     | 45           | $25         | 8              | $35 | =B3*C3 + D3*E3 |               |                |
| Bob      | 35           | $18         | 0              | $0  | =B4*C4 + D4*E4 |               |                |
| TOTAL    | =SUM(B2:B4)  | =SUM(C2:C4)                        | =SUM(D2:D4)      | =SUM(E2:E4)   | =SUM(F2:F4)    |

**Questions:**

1. How can you calculate John's total earnings using a formula in cell F2?
2. What function would you use in cell F5 to find the total earnings for all employees?

### Table 8: Expense Tracker

| Category       | January        | February    | March       | Total       |
| -------------- | -------------- | ----------- | ----------- | ----------- |
| Utilities      | $100    | $120 | $90         | =SUM(B2:D2) |             |
| Groceries      | $200    | $180 | $150        | =SUM(B3:D3) |             |
| Dining Out     | $50     | $70  | $60         | =SUM(B4:D4) |             |
| TOTAL EXPENSES | =SUM(B2:B4)    | =SUM(C2:C4) | =SUM(D2:D4) | =SUM(B5:D5) |

**Questions:**

1. How do you use the SUM function to find the total expenses for Utilities in cell E2?
2. What formula would you use in cell E5 to calculate the grand total of all expenses?

### Table 9: Loan Amortization

| Payment # | Principal       | Interest    | Total Payment | Remaining Loan |
| --------- | --------------- | ----------- | ------------- | -------------- |
| 1         | $500      | $50 | $550        | =C2+D2        |                |
| 2         | $520      | $45 | $565        | =C3+D3        |                |
| 3         | $540      | $40 | $580        | =C4+D4        |                |
| TOTAL     | =SUM(B2:B4)     | =SUM(C2:C4) | =SUM(D2:D4)   | =SUM(E2:E4)    |

**Questions:**

1. How can you use a formula to calculate the total payment for the first month in cell E2?
2. What function would you use in cell E5 to find the remaining loan after the third payment?

### Table 10: Project Task Tracking

| Task       | Start Date | End Date   | Status      |
| ---------- | ---------- | ---------- | ----------- |
| Research   | 2023-01-15 | 2023-01-30 | In Progress |
| Planning   | 2023-02-01 | 2023-02-15 | Completed   |
| Execution  | 2023-02-20 | 2023-03-15 | Not Started |
| Evaluation | 2023-03-20 | 2023-04-05 | Pending     |

**Questions:**

1. How would you use conditional formatting to highlight tasks that are "Completed" in the Status column?
2. What formula would you use to calculate the number of days remaining for the "Execution" task to start?

### Table 11: Product Sales Growth

| Month    | Product A Sales        | Product B Sales | Growth Rate |
| -------- | ---------------------- | --------------- | ----------- |
| January  | $500            | $700 |                 |             |
| February | $600            | $800 | =((B2-B1)/B1)   |             |
| March    | $750            | $900 | =((B3-B2)/B2)   |             |

**Questions:**

1. How can you use a formula to calculate the growth rate for Product A in February?
2. What formula would you use to find the average growth rate for both products?


Certainly, let's continue with a couple more examples:

### Table 12: Data Sorting and Filtering

| Employee | Department | Salary  | Years of Service |
| -------- | ---------- | ------- | ---------------- |
| John     | Marketing  | $60,000 | 3                |
| Jane     | IT         | $75,000 | 5                |
| Bob      | Finance    | $65,000 | 2                |
| Alice    | Marketing  | $70,000 | 4                |

**Questions:**

1. How would you use Excel's sorting functionality to arrange the employees in alphabetical order?
2. What steps would you take to filter the table to only show employees from the Marketing department?

### Table 13: Project Budgeting

| Expense   | Estimated Cost           | Actual Cost | Variance    |
| --------- | ------------------------ | ----------- | ----------- |
| Supplies  | $500            | $450   | =B2-C2      |             |
| Travel    | $1,000          | $1,200 | =B3-C3      |             |
| Equipment | $2,000          | $1,800 | =B4-C4      |             |
| TOTAL     | =SUM(B2:B4)              | =SUM(C2:C4) | =SUM(D2:D4) |

**Questions:**

1. How can you use a formula to calculate the variance for the Supplies expense?
2. What function would you use to find the total estimated cost for all expenses?

These examples focus on data manipulation techniques, including sorting, filtering, and budgeting. They provide practical scenarios that involve common tasks in spreadsheet software, helping learners develop a well-rounded skill set in using Excel for various purposes. Feel free to modify these examples or create new ones based on the specific objectives of your computer basic course.

### Table 14: Grade Conversion

| Student | Raw Score | Grade |
| ------- | --------- | ----- |
| John    | 85        |       |
| Jane    | 92        |       |
| Bob     | 78        |       |

**Questions:**

1. How would you use the IF function to assign letter grades based on the raw scores?
2. What formula would you use to calculate the average raw score for all students?

### Table 15: Event RSVP Tracker

| Attendee | RSVP Status | Meal Preference |
| -------- | ----------- | --------------- |
| Alice    | Yes         | Vegetarian      |
| Bob      | No          | N/A             |
| Carol    | Yes         | Vegan           |
| Dave     | Yes         | Gluten-Free     |

**Questions:**

1. How could you use Excel's COUNTIF function to count the number of attendees who RSVP'd "Yes"?
2. How would you filter the table to only show attendees with specific meal preferences?

Feel free to adjust these examples based on the specific topics and skills you want to cover in your computer basic course. These tables cover additional scenarios related to grading, conditional logic, and data tracking, providing more diversity in the application of Excel skills.

### Table 16: Project Status Tracker

| Task                  | Start Date | End Date   | Status      |
| --------------------- | ---------- | ---------- | ----------- |
| Requirement gathering | 2023-01-15 | 2023-02-01 | Completed   |
| Design                | 2023-02-05 | 2023-02-20 | In Progress |
| Development           | 2023-02-25 | 2023-03-15 | Not Started |
| Testing               | 2023-03-20 | 2023-04-05 | Pending     |

**Questions:**

1. How can you use conditional formatting to highlight tasks that are "In Progress" or "Not Started" in the Status column?
2. What formula would you use to calculate the percentage of completion for each task?

### Table 17: Fitness Log

| Date       | Exercise      | Duration (mins) | Calories Burned |
| ---------- | ------------- | --------------- | --------------- |
| 2023-01-15 | Running       | 30              | =B2*C2*0.1    |
| 2023-01-18 | Weightlifting | 45              | =B3*C3*0.05   |
| 2023-01-22 | Yoga          | 60              | =B4*C4*0.02   |

**Questions:**

1. How can you use a formula to calculate the total calories burned for each exercise session?
2. What function would you use to find the average duration of all exercise sessions?

Certainly! Let's continue with a few more examples:

### Table 18: Monthly Budget Comparison

| Category       | January        | February     | March       | Budget      | Variance    |
| -------------- | -------------- | ------------ | ----------- | ----------- | ----------- |
| Groceries      | $300    | $280 | $320  | $300 | =D2-B2      |             |             |
| Utilities      | $150    | $160 | $140  | $160 | =D3-B3      |             |             |
| Entertainment  | $100    | $120 | $90   | $110 | =D4-B4      |             |             |
| TOTAL EXPENSES | =SUM(B2:B4)    | =SUM(C2:C4)  | =SUM(D2:D4) | =SUM(E2:E4) | =SUM(F2:F4) |

**Questions:**

1. How can you use a formula to calculate the variance for the Groceries category in January?
2. What function would you use to find the total variance for all categories?

### Table 19: Survey Data Analysis

| Question           | Response 1      | Response 2      | Response 3      |
| ------------------ | --------------- | --------------- | --------------- |
| Q1: Satisfaction   | 4               | 5               | 3               |
| Q2: Ease of Use    | 5               | 4               | 2               |
| Q3: Recommendation | 4               | 3               | 5               |
| AVERAGE RESPONSES  | =AVERAGE(B2:B4) | =AVERAGE(C2:C4) | =AVERAGE(D2:D4) |

**Questions:**

1. How would you use the AVERAGE function to find the average response for Question 1?
2. What formula would you use to calculate the overall average response across all questions?

Feel free to modify these examples based on the specific skills and concepts you want to emphasize in your computer basic course. These tables cover scenarios such as budget tracking, data analysis, and survey data interpretation, providing learners with a diverse set of practical exercises in Excel.

### Table 20: Task Prioritization

| Task              | Priority | Due Date   | Status      |
| ----------------- | -------- | ---------- | ----------- |
| Report Submission | High     | 2023-01-31 | Pending     |
| Meeting Prep      | Medium   | 2023-02-10 | In Progress |
| Email Responses   | Low      | 2023-02-15 | Not Started |
| Project Review    | High     | 2023-02-28 | Completed   |

**Questions:**

1. How can you use conditional formatting to highlight tasks with different priorities in the Priority column?
2. What formula would you use to calculate the number of days remaining until the due date for each task?

### Table 21: Travel Expense Tracker

| Date       | Expense Type   | Amount | Currency | Exchange Rate | Amount (USD) |
| ---------- | -------------- | ------ | -------- | ------------- | ------------ |
| 2023-01-15 | Meals          | $50    | USD      | 1             | =D2*C2       |
| 2023-01-18 | Transportation | €30   | EUR      | 1.2           | =D3*C3       |
| 2023-01-22 | Accommodation  | ¥8000 | JPY      | 0.009         | =D4*C4       |

**Questions:**

1. How can you use a formula to convert all amounts to USD based on the exchange rates?
2. What function would you use to find the total expenses in USD?

Feel free to adapt and expand upon these examples, tailoring them to the specific needs and objectives of your computer basic course. These scenarios cover additional applications of Excel, such as task prioritization, expense tracking with currency conversion, and more.

### Table 22: Project Resource Allocation

| Task             | Resource 1 Allocation | Resource 2 Allocation | Total Allocation |
| ---------------- | --------------------- | --------------------- | ---------------- |
| Task 1           | 40%                   | 60%                   | =B2+C2           |
| Task 2           | 30%                   | 70%                   | =B3+C3           |
| Task 3           | 50%                   | 50%                   | =B4+C4           |
| TOTAL ALLOCATION | =SUM(B2:B4)           | =SUM(C2:C4)           | =D2+D3           |

**Questions:**

1. How can you use a formula to calculate the total allocation for each task?
2. What formula would you use to find the overall total allocation for all tasks?

### Table 23: Customer Satisfaction Survey Results

| Question             | Strongly Disagree | Disagree        | Neutral         | Agree           | Strongly Agree  |
| -------------------- | ----------------- | --------------- | --------------- | --------------- | --------------- |
| Q1: Product Quality  | 2                 | 1               | 3               | 5               | 4               |
| Q2: Customer Service | 1                 | 3               | 2               | 5               | 4               |
| Q3: Pricing          | 2                 | 2               | 3               | 4               | 5               |
| AVERAGE RESPONSES    | =AVERAGE(B2:B4)   | =AVERAGE(C2:C4) | =AVERAGE(D2:D4) | =AVERAGE(E2:E4) | =AVERAGE(F2:F4) |

**Questions:**

1. How would you use the AVERAGE function to find the average response for Question 1?
2. What formula would you use to calculate the overall average response across all questions?

Feel free to customize these examples based on the specific skills and concepts you want to cover in your computer basic course. These tables cover scenarios such as resource allocation, survey result analysis, and more, providing learners with diverse and practical applications of Excel skills.

Certainly! Here are a couple more examples:

### Table 24: Project Risk Assessment

| Task             | Probability (%) | Impact | Risk Level |
| ---------------- | --------------- | ------ | ---------- |
| Task 1           | 20              | High   | =B2*C2     |
| Task 2           | 10              | Medium | =B3*C3     |
| Task 3           | 5               | Low    | =B4*C4     |
| TOTAL RISK LEVEL | =SUM(D2:D4)     |        |            |

**Questions:**

1. How can you use a formula to calculate the risk level for each task?
2. What formula would you use to find the total risk level for all tasks?

### Table 25: Sales Forecast

| Month    | Actual Sales           | Forecasted Sales | Variance    |
| -------- | ---------------------- | ---------------- | ----------- |
| January  | $50,000      | $45,000 | =B2-C2           |             |
| February | $60,000      | $55,000 | =B3-C3           |             |
| March    | $70,000      | $65,000 | =B4-C4           |             |
| TOTAL    | =SUM(B2:B4)            | =SUM(C2:C4)      | =SUM(D2:D4) |

**Questions:**

1. How would you use conditional formatting to highlight months where actual sales exceed forecasted sales?
2. What formula would you use to find the total variance for all months?

Feel free to adjust and customize these examples based on the specific needs and objectives of your computer basic course. These tables cover additional scenarios such as risk assessment, sales forecasting, and variance analysis, providing learners with a comprehensive set of practical exercises in Excel.

Certainly! Here are a couple more examples:

### Table 26: Task Dependency

| Task   | Duration (days) | Dependencies   |
| ------ | --------------- | -------------- |
| Task 1 | 5               | None           |
| Task 2 | 7               | Task 1         |
| Task 3 | 4               | Task 2         |
| Task 4 | 6               | Task 1, Task 3 |

**Questions:**

1. How would you use a formula to calculate the start date for Task 2 based on the duration and dependency on Task 1?
2. What formula would you use to determine the total project duration?

### Table 27: Project ROI Calculation

| Investment     | Initial Cost           | Return            | ROI (%)         |
| -------------- | ---------------------- | ----------------- | --------------- |
| Marketing      | $10,000      | $25,000 | =((C2-B2)/B2)*100 |                 |
| R&D            | $15,000      | $18,000 | =((C3-B3)/B3)*100 |                 |
| Infrastructure | $20,000      | $30,000 | =((C4-B4)/B4)*100 |                 |
| TOTAL ROI      |                        |                   | =AVERAGE(D2:D4) |

**Questions:**

1. How can you use a formula to calculate the ROI for each investment?
2. What function would you use to find the average ROI for all investments?

Feel free to modify these examples or create new ones based on the specific topics and skills you want to emphasize in your computer basic course. These scenarios cover more advanced concepts, such as task dependencies, project ROI calculation, providing learners with practical applications of Excel in project management and financial analysis.

### Table 28: Social Media Analytics

| Platform         | Followers (Start) | New Followers | Engagement Rate (%) |
| ---------------- | ----------------- | ------------- | ------------------- |
| Twitter          | 10,000            | 500           | =(C2/B2)*100        |
| Instagram        | 20,000            | 1,000         | =(C3/B3)*100        |
| LinkedIn         | 15,000            | 800           | =(C4/B4)*100        |
| TOTAL ENGAGEMENT | =SUM(D2:D4)       |               |                     |

**Questions:**

1. How would you use a formula to calculate the engagement rate for each platform?
2. What function would you use to find the total engagement across all platforms?

### Table 29: Inventory Turnover

| Product        | Beginning Inventory | Ending Inventory | Units Sold | Inventory Turnover |
| -------------- | ------------------- | ---------------- | ---------- | ------------------ |
| Product A      | 100                 | 50               | 200        | =((C2 + C3)/2)/B2  |
| Product B      | 150                 | 100              | 120        | =((C4 + C5)/2)/B4  |
| Product C      | 200                 | 180              | 150        | =((C6 + C7)/2)/B6  |
| TOTAL TURNOVER | =AVERAGE(D2:D7)     |                  |            |                    |

**Questions:**

1. How can you use a formula to calculate the inventory turnover for each product?
2. What function would you use to find the average turnover across all products?

Feel free to customize and extend these examples based on the specific objectives of your computer basic course. These scenarios cover areas such as social media analytics and inventory turnover, offering learners exposure to diverse and practical applications of Excel.

### Table 30: Project Task Estimation

| Task           | Estimated Hours | Actual Hours | Variance |
| -------------- | --------------- | ------------ | -------- |
| Task 1         | 20              | 18           | =B2-C2   |
| Task 2         | 30              | 35           | =B3-C3   |
| Task 3         | 15              | 12           | =B4-C4   |
| TOTAL VARIANCE | =SUM(D2:D4)     |              |          |

**Questions:**

1. How can you use a formula to calculate the variance in estimated vs. actual hours for each task?
2. What function would you use to find the total variance across all tasks?

### Table 31: Employee Training Hours

| Employee    | Department  | Training Hours |
| ----------- | ----------- | -------------- |
| John        | HR          | 20             |
| Jane        | IT          | 15             |
| Bob         | Finance     | 25             |
| TOTAL HOURS | =SUM(C2:C4) |                |

**Questions:**

1. How would you use conditional formatting to highlight employees who have completed more than 20 training hours?
2. What formula would you use to find the total training hours for all employees?

Feel free to adjust and expand upon these examples based on the specific skills and concepts you want to cover in your computer basic course. These tables cover additional scenarios such as task estimation and employee training tracking, providing learners with a diverse set of practical exercises in Excel.

### Table 32: Project Cash Flow

| Month    | Revenue           | Expenses    | Net Cash Flow |
| -------- | ----------------- | ----------- | ------------- |
| January  | $50,000 | $35,000 | =B2-C2      |               |
| February | $60,000 | $40,000 | =B3-C3      |               |
| March    | $70,000 | $45,000 | =B4-C4      |               |
| TOTAL    | =SUM(B2:B4)       | =SUM(C2:C4) | =SUM(D2:D4)   |

**Questions:**

1. How can you use a formula to calculate the net cash flow for each month?
2. What function would you use to find the total revenue and total expenses?

### Table 33: Customer Order Tracking

| Order # | Customer    | Product | Quantity    | Price per Unit | Total  |
| ------- | ----------- | ------- | ----------- | -------------- | ------ |
| 001     | John        | Laptop  | 2           | $800           | =D2*E2 |
| 002     | Jane        | Printer | 1           | $150           | =D3*E3 |
| 003     | Bob         | Monitor | 3           | $200           | =D4*E4 |
| TOTAL   | =SUM(D2:D4) |         | =SUM(D2:D4) | =SUM(F2:F4)    |        |

**Questions:**

1. How would you use a formula to calculate the total cost for each order?
2. What formula would you use to find the overall total for the Quantity and Total columns?

Feel free to adapt these examples based on the specific objectives of your computer basic course. These scenarios cover additional areas such as cash flow tracking and order processing, offering learners a variety of practical applications of Excel skills in different contexts.

Certainly! Here are a couple more examples:

### Table 34: Monthly Budget Projection

| Category       | January Budget         | February Budget     | March Budget | Actual Expenses | Variance    |
| -------------- | ---------------------- | ------------------- | ------------ | --------------- | ----------- |
| Groceries      | $300            | $280 | $320         | $290 | =D2-B2       |                 |             |
| Utilities      | $150            | $160 | $140         | $155 | =D3-B3       |                 |             |
| Entertainment  | $100            | $120 | $90          | $110 | =D4-B4       |                 |             |
| TOTAL EXPENSES | =SUM(B2:B4)            | =SUM(C2:C4)         | =SUM(D2:D4)  | =SUM(E2:E4)     | =SUM(F2:F4) |

**Questions:**

1. How can you use a formula to calculate the variance for each budget category?
2. What function would you use to find the total variance for all budget categories?

### Table 35: Employee Vacation Tracker

| Employee        | Department | Vacation Days Taken | Remaining Vacation Days |
| --------------- | ---------- | ------------------- | ----------------------- |
| John            | HR         | 5                   | =B2-C2                  |
| Jane            | IT         | 8                   | =B3-C3                  |
| Bob             | Finance    | 3                   | =B4-C4                  |
| TOTAL REMAINING |            |                     | =SUM(D2:D4)             |

**Questions:**

1. How would you use conditional formatting to highlight employees with no remaining vacation days?
2. What formula would you use to find the total remaining vacation days for all employees?

Feel free to customize and extend these examples based on the specific objectives and requirements of your computer basic course. These tables cover additional scenarios such as budget projections and employee vacation tracking, providing learners with a comprehensive set of practical exercises in Excel.

### Table 36: Project Evaluation Scores

| Project   | Criteria 1 | Criteria 2 | Criteria 3 | Total Score | Average Score   |
| --------- | ---------- | ---------- | ---------- | ----------- | --------------- |
| Project A | 85         | 90         | 78         | =SUM(B2:D2) | =AVERAGE(B2:D2) |
| Project B | 92         | 88         | 95         | =SUM(B3:D3) | =AVERAGE(B3:D3) |
| Project C | 78         | 85         | 80         | =SUM(B4:D4) | =AVERAGE(B4:D4) |

**Questions:**

1. How can you use a formula to calculate the total score for each project?
2. What function would you use to find the average score for each project?

### Table 37: Monthly Sales Commission

| Salesperson      | Sales Amount | Commission Rate | Commission Earned |
| ---------------- | ------------ | --------------- | ----------------- |
| Alice            | $10,000      | 5%              | =B2*C2            |
| Bob              | $15,000      | 4%              | =B3*C3            |
| Carol            | $12,000      | 6%              | =B4*C4            |
| TOTAL COMMISSION | =SUM(D2:D4)  |                 |                   |

**Questions:**

1. How would you use a formula to calculate the commission earned by each salesperson?
2. What function would you use to find the total commission earned by all salespeople?

Feel free to modify these examples or create new ones based on the specific topics and skills you want to emphasize in your computer basic course. These scenarios cover additional areas such as project evaluation and sales commission calculation, offering learners a diverse set of practical exercises in Excel.

Certainly! Here are a couple more examples:

### Table 38: Event Planning Checklist

| Task                  | Responsible Person           | Status      |
| --------------------- | ---------------------------- | ----------- |
| Venue Selection       | Alice                        | In Progress |
| Budget Planning       | Bob                          | Not Started |
| Guest List Creation   | Carol                        | Completed   |
| Catering Arrangements | Dave                         | In Progress |
| TOTAL COMPLETED TASKS | =COUNTIF(C2:C5, "Completed") |             |

**Questions:**

1. How can you use a formula to count the number of completed tasks in the Status column?
2. What function would you use to find the percentage of completed tasks?

### Table 39: Project Resource Availability

| Resource        | Initial Availability | Hours Used | Remaining Availability |
| --------------- | -------------------- | ---------- | ---------------------- |
| Resource A      | 40                   | 25         | =B2-C2                 |
| Resource B      | 30                   | 20         | =B3-C3                 |
| Resource C      | 35                   | 15         | =B4-C4                 |
| TOTAL REMAINING | =SUM(D2:D4)          |            |                        |

**Questions:**

1. How would you use conditional formatting to highlight resources with less than 10 hours remaining?
2. What formula would you use to find the total remaining availability for all resources?

Feel free to adapt and expand upon these examples based on the specific needs and objectives of your computer basic course. These tables cover additional scenarios such as event planning and resource availability tracking, providing learners with a variety of practical applications for Excel skills.

Certainly! Here are a couple more examples:

### Table 40: Employee Performance Metrics

| Employee          | Sales (in $) | Customer Satisfaction | Errors Count | Performance Score         |
| ----------------- | ------------ | --------------------- | ------------ | ------------------------- |
| Alex              | $12,000      | 4.5                   | 2            | =B2*0.5 + C2*50 - D2*20 |
| Bella             | $15,000      | 4.2                   | 1            | =B3*0.5 + C3*50 - D3*20 |
| Chris             | $10,000      | 4.8                   | 0            | =B4*0.5 + C4*50 - D4*20 |
| TOTAL PERFORMANCE | =SUM(E2:E4)  |                       |              |                           |

**Questions:**

1. How can you use a formula to calculate the performance score for each employee?
2. What function would you use to find the total performance score?

### Table 41: Conference Room Reservation

| Room   | Date       | Start Time | End Time | Reserved By |
| ------ | ---------- | ---------- | -------- | ----------- |
| Room A | 2023-05-10 | 10:00 AM   | 12:00 PM | Alice       |
| Room B | 2023-05-10 | 01:00 PM   | 03:00 PM | Bob         |
| Room C | 2023-05-11 | 09:00 AM   | 11:00 AM | Carol       |
| Room D | 2023-05-11 | 02:00 PM   | 04:00 PM | Dave        |

**Questions:**

1. How would you use conditional formatting to highlight any scheduling conflicts?
2. What formula would you use to find the total number of reserved hours for all conference rooms?

Feel free to customize and extend these examples based on the specific objectives of your computer basic course. These scenarios cover additional areas such as employee performance metrics and conference room reservation, offering learners a diverse set of practical exercises in Excel.


Certainly! Here are a couple more examples:

### Table 42: Project Time Tracking

| Task        | Start Time | End Time | Duration (in hours)                                    |
| ----------- | ---------- | -------- | ------------------------------------------------------ |
| Task 1      | 9:00 AM    | 11:30 AM | =TEXT(B2,"h:mm AM/PM") & " - " & TEXT(C2,"h:mm AM/PM") |
| Task 2      | 1:00 PM    | 3:00 PM  | =TEXT(B3,"h:mm AM/PM") & " - " & TEXT(C3,"h:mm AM/PM") |
| Task 3      | 10:30 AM   | 12:00 PM | =TEXT(B4,"h:mm AM/PM") & " - " & TEXT(C4,"h:mm AM/PM") |
| TOTAL HOURS |            |          | =SUM(D2:D4)                                            |

**Questions:**

1. How can you use a formula to calculate the duration for each task in a human-readable format?
2. What function would you use to find the total hours worked on the project?

### Table 43: Monthly Attendance

| Date       | Employee 1  | Employee 2  | Employee 3  | Total Present          |
| ---------- | ----------- | ----------- | ----------- | ---------------------- |
| 2023-06-01 | Yes         | Yes         | No          | =COUNTIF(B2:D2, "Yes") |
| 2023-06-02 | Yes         | Yes         | Yes         | =COUNTIF(B3:D3, "Yes") |
| 2023-06-03 | No          | Yes         | Yes         | =COUNTIF(B4:D4, "Yes") |
| TOTAL      | =SUM(B2:B4) | =SUM(C2:C4) | =SUM(D2:D4) | =SUM(E2:E4)            |

**Questions:**

1. How would you use conditional formatting to highlight dates where all employees are present?
2. What formula would you use to find the total number of days each employee was present?

Feel free to adapt and expand these examples based on the specific needs and objectives of your computer basic course. These tables cover additional scenarios such as project time tracking and attendance tracking, providing learners with a variety of practical applications for Excel skills.

Certainly! Here are a couple more examples:

### Table 44: Project Task Collaboration

| Task   | Assigned To | Collaborators |
| ------ | ----------- | ------------- |
| Task 1 | Alice       | Bob, Carol    |
| Task 2 | Bob         | Alice, Dave   |
| Task 3 | Carol       | Alice, Bob    |

**Questions:**

1. How can you use a formula to count the number of collaborators for each task?
2. What function would you use to find the total number of unique collaborators across all tasks?

### Table 45: Product Inventory Aging

| Product     | Purchase Date | Current Quantity | Aging (in days) |
| ----------- | ------------- | ---------------- | --------------- |
| Product A   | 2023-07-01    | 100              | =TODAY() - B2   |
| Product B   | 2023-07-15    | 80               | =TODAY() - B3   |
| Product C   | 2023-08-01    | 120              | =TODAY() - B4   |
| TOTAL AGING |               |                  | =AVERAGE(D2:D4) |

**Questions:**

1. How would you use a formula to calculate the aging of each product in days?
2. What function would you use to find the average aging of all products?

Feel free to customize and extend these examples based on the specific objectives and requirements of your computer basic course. These scenarios cover additional areas such as task collaboration and product inventory aging, offering learners a variety of practical exercises to apply Excel skills in different contexts.
