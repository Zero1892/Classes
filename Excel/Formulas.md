# Formulas

1. **SUM**:

   - **Explanation**: Adds up the numbers in a range.
   - **Usage**: `=SUM(A1:A5)`
2. **AVERAGE**:

   - **Explanation**: Calculates the average of a range of numbers.
   - **Usage**: `=AVERAGE(A1:A5)`
3. **MIN/MAX**:

   - **Explanation**: Returns the smallest or largest value in a range.
   - **Usage**:
     - Minimum: `=MIN(A1:A5)`
     - Maximum: `=MAX(A1:A5)`
4. **COUNT**:

   - **Explanation**: Counts the number of cells in a range that contains numbers.
   - **Usage**: `=COUNT(A1:A5)`
5. **COUNTA**:

   - **Explanation**: Counts the number of cells in a range that are not empty.
   - **Usage**: `=COUNTA(A1:A5)`
6. **IF**:

   - **Explanation**: Returns one value if a condition is true and another if it's false.
   - **Usage**: `=IF(A1>10, "Yes", "No")`
7. **VLOOKUP**:

   - **Explanation**: Searches for a value in the first column of a range and returns a corresponding value from another column.
   - **Usage**: `=VLOOKUP(A1, B1:C5, 2, FALSE)`
8. **HLOOKUP**:

   - **Explanation**: Similar to VLOOKUP, but it searches horizontally.
   - **Usage**: `=HLOOKUP(A1, B1:F1, 3, FALSE)`
9. **INDEX and MATCH**:

   - **Explanation**: A combination of functions to look up a value in a range and return a value from a specified column.
   - **Usage**: `=INDEX(C1:C5, MATCH(A1, B1:B5, 0))`
10. **CONCATENATE (or &)**:

    - **Explanation**: Combines text from multiple cells into one cell.
    - **Usage**:
      - Using CONCATENATE: `=CONCATENATE(A1, " - ", B1)`
      - Using & operator: `=A1 & " - " & B1`
11. **TEXT**:

    - **Explanation**: Converts a value to text with a specified format.
    - **Usage**: `=TEXT(A1, "yyyy-mm-dd")`
12. **LEFT/RIGHT/MID**:

    - **Explanation**: Extracts characters from the left, right, or middle of a text string.
    - **Usage**:
      - Left: `=LEFT(A1, 3)`
      - Right: `=RIGHT(A1, 3)`
      - Mid: `=MID(A1, 2, 4)`
13. **SUMIF/SUMIFS**:

    - **Explanation**: Sums values that meet a specified condition.
    - **Usage**:
      - SUMIF: `=SUMIF(A1:A5, ">10")`
      - SUMIFS: `=SUMIFS(C1:C5, A1:A5, ">10", B1:B5, "<>X")`
14. **AVERAGEIF/AVERAGEIFS**:

    - **Explanation**: Calculates the average of values that meet a specified condition.
    - **Usage**:
      - AVERAGEIF: `=AVERAGEIF(A1:A5, ">=50")`
      - AVERAGEIFS: `=AVERAGEIFS(C1:C5, A1:A5, ">=50", B1:B5, "<>X")`
15. **COUNTIF/COUNTIFS**:

    - **Explanation**: Counts the number of cells that meet a specified condition.
    - **Usage**:
      - COUNTIF: `=COUNTIF(A1:A5, "Apples")`
      - COUNTIFS: `=COUNTIFS(A1:A5, "Apples", B1:B5, "Red")`
16. **DATE and TIME functions** (e.g., DATE, NOW, TODAY):

    - **Explanation**: Perform calculations with dates and times.
    - **Usage**: `=DATE(2023, 11, 1)`, `=NOW()`, `=TODAY()`
17. **PIVOT TABLES**:

    - **Explanation**: An advanced feature that summarizes and analyzes data in a dynamic table format.
    - **Usage**: Create a Pivot Table from the "Insert" tab in Excel.
18. **CHOOSE and INDIRECT**:

    - **Explanation**: Allows you to dynamically reference cells and create more flexible formulas.
    - **Usage**: `=CHOOSE(A1, "Option 1", "Option 2", "Option 3")`, `=INDIRECT("A" & A1)`


19. **SUBTOTAL**:

- **Explanation**: Calculates a subtotal for a range while ignoring other subtotals.
- **Usage**: `=SUBTOTAL(9, A1:A10)` (9 for SUM, you can use other numbers for different functions)

20. **RANK**:

- **Explanation**: Returns the rank of a value within a list.
- **Usage**: `=RANK(A1, A1:A5)`

21. **MATCH**:

- **Explanation**: Searches for a specified value in a range and returns its relative position.
- **Usage**: `=MATCH(A1, A1:A5, 0)`

22. **ROUND**:

- **Explanation**: Rounds a number to a specified number of decimal places.
- **Usage**: `=ROUND(A1, 2)` (round to 2 decimal places)

23. **IFERROR**:

- **Explanation**: Returns a specified value if a formula results in an error.
- **Usage**: `=IFERROR(A1/B1, "N/A")`

24. **COUNTBLANK**:

- **Explanation**: Counts the number of empty cells in a range.
- **Usage**: `=COUNTBLANK(A1:A5)`

25. **SUMPRODUCT**:

- **Explanation**: Multiplies corresponding elements in arrays and returns the sum of those products.
- **Usage**: `=SUMPRODUCT(A1:A5, B1:B5)`

26. **SUMIF with Wildcards**:

- **Explanation**: Allows for partial matching using wildcards like "*" and "?".
- **Usage**: `=SUMIF(A1:A5, "Apples*", B1:B5)`

27. **IF, AND, and OR** (used in combination):

- **Explanation**: Perform logical tests and return results based on multiple conditions.
- **Usage**: `=IF(AND(A1>10, B1="Red"), "Yes", "No")`

28. **DAYS, NETWORKDAYS**:

- **Explanation**: Calculate the number of days between two dates or working days between two dates.
- **Usage**: `=DAYS(A1, B1)`, `=NETWORKDAYS(A1, B1)`

29. **TRANSPOSE**:

- **Explanation**: Transposes a range of cells, switching rows and columns.
- **Usage**: Enter as an array formula (Ctrl + Shift + Enter): `{=TRANSPOSE(A1:A5)}`

30. **HYPERLINK**:

- **Explanation**: Creates a clickable hyperlink in a cell.
- **Usage**: `=HYPERLINK("https://www.example.com", "Visit Example")`

31. **RANK.EQ and RANK.AVG**:

- **Explanation**: RANK.EQ assigns the same rank to tied values, while RANK.AVG assigns the average rank.
- **Usage**: `=RANK.EQ(A1, A1:A5)`, `=RANK.AVG(A1, A1:A5)`

32. **LOOKUP**:

- **Explanation**: Searches for a value in a range and returns a corresponding value.
- **Usage**: `=LOOKUP(A1, B1:B5, C1:C5)`

33. **EOMONTH**:

- **Explanation**: Returns the last day of the month, a specified number of months before or after a given date.
- **Usage**: `=EOMONTH(A1, 2)` (2 months after A1)

34. **CHISQ.DIST**:

- **Explanation**: Calculates the chi-squared distribution probability.
- **Usage**: `=CHISQ.DIST(A1, 3, TRUE)` (probability of chi-squared value A1 with 3 degrees of freedom)

35. **GETPIVOTDATA**:

- **Explanation**: Retrieves data from a Pivot Table.
- **Usage**: Enter the function within a Pivot Table cell and reference specific data points.

36. **FORECAST**:

- **Explanation**: Predicts future values based on existing data points.
- **Usage**: `=FORECAST(A1, B1:B5, A1:A5)`

37. **GROWTH**:

- **Explanation**: Calculates predicted exponential growth based on existing data.
- **Usage**: `=GROWTH(B1:B5, A1:A5, C1)`

38. **FV and PV**:

- **Explanation**: Computes the future value or present value of an investment or loan.
- **Usage**:
  - Future Value: `=FV(A1, B1, C1, D1)`
  - Present Value: `=PV(A1, B1, C1, D1)`

39. **NPV (Net Present Value)**:

- **Explanation**: Calculates the net present value of a series of cash flows.
- **Usage**: `=NPV(A1, B1:B5)`

40. **IRR (Internal Rate of Return)**:

- **Explanation**: Determines the internal rate of return for a series of cash flows.
- **Usage**: `=IRR(B1:B5)`

41. **DATEVALUE and TIMEVALUE**:

- **Explanation**: Converts text representations of dates and times into serial numbers.
- **Usage**: `=DATEVALUE("2023-11-01")`, `=TIMEVALUE("15:30:00")`

42. **DAYS360**:

- **Explanation**: Calculates the number of days between two dates based on a 360-day year.
- **Usage**: `=DAYS360(A1, B1)`

43. **HYPERLINK with Cell References**:

- **Explanation**: Creates hyperlinks using cell references for the URL and display text.
- **Usage**: `=HYPERLINK(A1, B1)`

44. **CONCATENATE with Line Breaks**:

- **Explanation**: Combines text from multiple cells with line breaks.
- **Usage**: `=A1 & CHAR(10) & B1`

45. **INDEX and MATCH with Multiple Criteria**:

- **Explanation**: Uses INDEX and MATCH functions to perform a two-dimensional lookup.
- **Usage**: `=INDEX(C1:D5, MATCH(A1, A1:A5, 0), MATCH(B1, B1:B5, 0))`

46. **TEXTJOIN**:

- **Explanation**: Combines text from multiple cells with a specified delimiter.
- **Usage**: `=TEXTJOIN(", ", TRUE, A1:A5)`

47. **RANK with Ties**:

- **Explanation**: Assigns the same rank to tied values.
- **Usage**: `=RANK(A1, A1:A5, 1)`

48. **SUMPRODUCT with Criteria**:

- **Explanation**: Sums the product of arrays based on multiple criteria.
- **Usage**: `=SUMPRODUCT((A1:A5="Apples")*(B1:B5="Red")*(C1:C5))`

49. **XNPV and XIRR**:

- **Explanation**: Calculate the net present value (XNPV) and internal rate of return (XIRR) for irregular cash flows.
- **Usage**:
  - XNPV: `=XNPV(A1, B1:B5, C1:C5)`
  - XIRR: `=XIRR(B1:B5, C1:C5)`

50. **AGGREGATE**:

- **Explanation**: Performs various functions while allowing you to ignore hidden rows or error values.
- **Usage**: `=AGGREGATE(function_num, options, ref1, [ref2], ...)`

51. **CELL**:

- **Explanation**: Retrieves information about the formatting, location, or contents of a cell.
- **Usage**: `=CELL("address", A1)`

52. **NORM.DIST and NORM.INV**:

- **Explanation**: Calculate the cumulative distribution and inverse cumulative distribution of a normal distribution.
- **Usage**:
  - Normal Distribution: `=NORM.DIST(x, mean, standard_dev, cumulative)`
  - Inverse Normal Distribution: `=NORM.INV(probability, mean, standard_dev)`

53. **PERCENTILE and QUARTILE**:

- **Explanation**: Calculate the k-th percentile or quartile of a dataset.
- **Usage**:
  - Percentile: `=PERCENTILE(data_range, k)`
  - Quartile: `=QUARTILE(data_range, quartile_num)`

54. **TREND**:

- **Explanation**: Creates a linear trendline and predicts future values.
- **Usage**: `=TREND(known_y's, known_x's, new_x)`

55. **SUBSTITUTE**:

- **Explanation**: Replaces occurrences of a specified text in a text string with new text.
- **Usage**: `=SUBSTITUTE(A1, "old", "new")`

56. **UPPER and LOWER**:

- **Explanation**: Converts text to all uppercase or all lowercase.
- **Usage**:
  - Uppercase: `=UPPER(A1)`
  - Lowercase: `=LOWER(A1)`

57. **TRIM**:

- **Explanation**: Removes extra spaces from text, leaving only single spaces between words.
- **Usage**: `=TRIM(A1)`

58. **LEN**:

- **Explanation**: Counts the number of characters in a text string.
- **Usage**: `=LEN(A1)`

59. **MID and SEARCH**:

- **Explanation**: Extracts a specific number of characters from a text string starting at a specified position. SEARCH finds the position of a substring within a text string.
- **Usage**:
  - MID: `=MID(A1, start_position, num_characters)`
  - SEARCH: `=SEARCH("substring", A1)`

60. **RANDBETWEEN**:

- **Explanation**: Generates a random integer between two specified values.
- **Usage**: `=RANDBETWEEN(1, 100)`

61. **DATE and TIME functions** (e.g., YEAR, MONTH, DAY, HOUR, MINUTE, SECOND):

- **Explanation**: Extract or manipulate components of dates and times.
- **Usage**: `=YEAR(A1)`, `=MONTH(A1)`, `=HOUR(A1)`, etc.

62. **FLOOR and CEILING**:

- **Explanation**: Rounds numbers down or up to the nearest specified multiple.
- **Usage**:
  - FLOOR: `=FLOOR(A1, multiple)`
  - CEILING: `=CEILING(A1, multiple)`

63. **DEGREES and RADIANS**:

- **Explanation**: Converts angles between degrees and radians.
- **Usage**: `=DEGREES(A1)`, `=RADIANS(A1)`

64. **IFNA**:

- **Explanation**: Returns a specified value if a formula results in a #N/A error.
- **Usage**: `=IFNA(VLOOKUP(A1, B1:C5, 2, FALSE), "Not found")`

65. **SEQUENCE**:

- **Explanation**: Generates a sequence of numbers in a column or row.
- **Usage**: `=SEQUENCE(rows, columns, start, step)`

66. **UNION** (via Excel Tables):

- **Explanation**: Combines data from multiple tables into one table.
- **Usage**: Create Excel Tables and use the "Add Table" feature to combine data.

67. **SLOPE and INTERCEPT**:

- **Explanation**: Calculate the slope and y-intercept of a linear regression line.
- **Usage**:
  - Slope: `=SLOPE(known_y's, known_x's)`
  - Intercept: `=INTERCEPT(known_y's, known_x's)`

68. **Z.TEST and T.TEST**:

- **Explanation**: Perform hypothesis testing for a population mean (T.TEST) or population proportion (Z.TEST).
- **Usage**:
  - Z-Test: `=Z.TEST(data_range, pop_mean, pop_stdev)`
  - T-Test: `=T.TEST(data_range, pop_mean, tails, type)`

69. **RANK.EQ and RANK.AVG with Percentile**:

- **Explanation**: Rank values as a percentile (0 to 1) within a dataset.
- **Usage**: `=RANK.EQ(A1, A1:A5, 1)`, `=RANK.AVG(A1, A1:A5, 1)`

70. **FACT and FACTDOUBLE**:

- **Explanation**: Calculate the factorial or double factorial of a number.
- **Usage**:
  - Factorial: `=FACT(A1)`
  - Double Factorial: `=FACTDOUBLE(A1)`

71. **SIN, COS, and TAN**:

- **Explanation**: Calculate trigonometric functions (sine, cosine, tangent) of an angle in radians.
- **Usage**: `=SIN(A1)`, `=COS(A1)`, `=TAN(A1)`

72. **SIGN**:

- **Explanation**: Returns the sign of a number as 1 (positive), -1 (negative), or 0 (zero).
- **Usage**: `=SIGN(A1)`

73. **MOD**:

- **Explanation**: Returns the remainder after division of one number by another.
- **Usage**: `=MOD(A1, B1)`

74. **SUMPRODUCT with Multiple Criteria**:

- **Explanation**: Sum the product of arrays based on multiple conditions.
- **Usage**: `=SUMPRODUCT((A1:A5="Apples")*(B1:B5="Red")*(C1:C5))`

75. **FREQUENCY**:

- **Explanation**: Calculates the frequency distribution of a dataset.
- **Usage**: Enter as an array formula (Ctrl + Shift + Enter): `{=FREQUENCY(data_range, bins_range)}`

76. **CHIDIST and CHIINV**:

- **Explanation**: Calculate the cumulative distribution and inverse cumulative distribution of the chi-squared distribution.
- **Usage**:
  - Chi-Squared Distribution: `=CHIDIST(x, degrees_freedom)`
  - Inverse Chi-Squared Distribution: `=CHIINV(probability, degrees_freedom)`

77. **PERMUT and COMBIN**:

- **Explanation**: Calculate the number of permutations and combinations of a set of items.
- **Usage**:
  - Permutations: `=PERMUT(n, k)`
  - Combinations: `=COMBIN(n, k)`

78. **HARMEAN, GEOMEAN, and SUMSQ**:

- **Explanation**: Calculate the harmonic mean, geometric mean, and sum of squares of a dataset.
- **Usage**:
  - Harmonic Mean: `=HARMEAN(data_range)`
  - Geometric Mean: `=GEOMEAN(data_range)`
  - Sum of Squares: `=SUMSQ(data_range)`

79. **WEIBULL.DIST**:

- **Explanation**: Calculate the Weibull distribution probability.
- **Usage**: `=WEIBULL.DIST(x, alpha, beta, cumulative)`

80. **XLOOKUP**:

- **Explanation**: A powerful replacement for VLOOKUP and HLOOKUP, providing flexibility and advanced search features.
- **Usage**: `=XLOOKUP(lookup_value, lookup_array, return_array, [if_not_found], [match_mode], [search_mode])`
