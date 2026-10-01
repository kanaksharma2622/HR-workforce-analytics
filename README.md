# HR-workforce-analytics
# HR Workforce Analytics using SQL

## 1. Project Overview
Analysis of employee attrition, pay and performance using SQL.
Goal: find which groups of employees leave most and what the company can do about it.

## 2. Dataset
- Synthetic (made-up) HR data: 1,000 employees, 23 columns
- File: `hr_employees.csv`
- Key columns: Department, Job_Level, Annual_Salary_INR, Compa_Ratio,
  Satisfaction_Score, Overtime, Tenure_Years, Attrition, Exit_Reason

## 3. Tools
- MySQL

## 4. SQL Skills Used
- GROUP BY, HAVING, aggregate functions
- Subquery and JOIN
- Window functions: RANK(), ROW_NUMBER()
- CTE, CASE WHEN

## 5. Key Findings

1. **Overall attrition is 23%** (230 of 1,000 employees left).
   - Action: Track attrition every quarter to catch problems early.

2. **Overtime employees leave almost twice as often: 33.9% vs 18.0%.**
   - Action: Set an overtime limit and review workload of overtime-heavy teams first.

3. **Attrition differs by department: 18.4% (IT) to 26.6% (Sales and Customer Support).**
   - Overtime, pay and satisfaction do not explain this gap. For example,
     Engineering has the highest overtime (37.3%) but below-average attrition (21.5%).
   - Action: Look at other factors like manager quality and career growth,
     starting with Sales and Customer Support.

4. **Low satisfaction employees leave at [__]%, vs [__]% for high satisfaction.**
   - Action: [ ]

5. **Top exit reason is [__] ([__]% of exits).**
   - Action: [ ]

## 6. Files
- `hr_employees.csv`: dataset
- `hr_analysis.sql`: all queries
- `README.md`: this file

## 7. Note
Data is synthetic and created for practice. Findings show the analysis method,
not real company insights.
