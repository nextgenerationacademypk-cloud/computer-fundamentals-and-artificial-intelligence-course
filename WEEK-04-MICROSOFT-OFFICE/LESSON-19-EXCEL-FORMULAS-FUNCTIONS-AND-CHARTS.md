# Lesson 19 — Excel Formulas, Functions and Charts

**Week:** 4 | **Duration:** 120 minutes | **Practical focus:** 80%

## Learning outcomes
Students can write basic formulas, use SUM, AVERAGE, MIN, MAX, COUNT and IF, use AutoFill, distinguish relative and absolute references, apply simple conditional formatting and create a suitable chart.

## Key terms
Formula, function, argument, operator, relative reference, absolute reference, AutoFill, conditional formatting, chart, data series.

## 1. Formula basics
A formula begins with an equals sign (=). Use cell references rather than retyping values so calculations update when data changes.

Examples:
- `=B2+C2` adds two cells.
- `=B2-C2` subtracts.
- `=B2*C2` multiplies.
- `=B2/C2` divides (check that the divisor is not zero).

Use parentheses to make calculation order clear, such as `=(B2+C2)/2`.

## 2. Common functions
- `=SUM(B2:B10)` adds values.
- `=AVERAGE(B2:B10)` calculates the mean.
- `=MIN(B2:B10)` returns the smallest value.
- `=MAX(B2:B10)` returns the largest value.
- `=COUNT(B2:B10)` counts cells containing numbers.
- `=IF(C2>=50,"Pass","Review")` returns one result when a condition is true and another when false.

A function name is followed by parentheses. The values inside are called arguments. A range uses a colon between its first and last cell.

## 3. Relative and absolute references
When a formula is copied, relative references adjust. For example, copying `=B2*C2` down one row changes it to `=B3*C3`.

An absolute reference stays fixed. Dollar signs lock the column and row, for example `=$F$1*B2`. This is useful when many rows use one fixed tax rate or multiplier. Mixed references can be introduced later.

## 4. AutoFill
Use the fill handle to copy a formula or continue a recognized series. Check the results after filling. Do not assume every copied formula is correct.

## 5. Conditional formatting
Conditional formatting changes appearance when a rule is met. For example, highlight marks below 50. It helps draw attention but does not correct the underlying data. Use labels as well as colours so meaning is not colour-only.

## 6. Charts
Choose a chart that matches the question:
- Column/bar chart: compare categories.
- Line chart: show change over time.
- Pie chart: show a small number of parts of one whole, when values are meaningful and total 100%.

Include a useful title and readable labels. Avoid 3D effects and unnecessary decoration. Check that the selected data range includes the correct labels and values.

## Guided practical — Marks and performance workbook
Create fictional student marks with columns Student ID, Name, HTML, Computer Basics and Excel. Add Total, Average and Result. Use SUM, AVERAGE, IF, MIN and MAX. Use COUNT to count numeric scores. Copy formulas down, apply conditional formatting to low marks and create a column chart comparing subject averages.

Test one formula manually with a calculator. Correct errors before saving.

## 120-minute teaching plan
| Time | Activity |
|---|---|
| 0–20 min | Formula rules, operators and cell references |
| 20–45 min | Demonstrate arithmetic and core functions |
| 45–65 min | Students build totals, averages and IF results |
| 65–80 min | Relative/absolute references and AutoFill |
| 80–95 min | Conditional formatting |
| 95–112 min | Create and format chart |
| 112–120 min | Verify results and review |

## Understanding check
1. Why does a formula begin with =?
2. What does SUM(B2:B10) calculate?
3. How is COUNT different from COUNTA?
4. What does the dollar sign do in $F$1?
5. Which chart is suitable for values changing by month?

## Homework
Extend the marks workbook with a separate monthly expense table. Calculate total and average expense, identify the largest category and create one suitable chart. Use fictional values.

## Instructor notes
Teach one formula at a time. Students should predict a result before pressing Enter. Explain that formula separators may vary with regional settings; if a formula errors, check the installed application's locale and syntax. Never use real student marks in public demonstrations.

## Completion checklist
- [ ] Write arithmetic formulas.
- [ ] Use the six named functions.
- [ ] Explain relative and absolute references.
- [ ] Copy formulas with AutoFill and verify.
- [ ] Apply conditional formatting.
- [ ] Create a readable chart.
