HR Attrition Analysis — Python & Pandas
Project Overview
End-to-end exploratory data analysis (EDA) on a dataset of 1,000 employees to identify the key drivers of attrition and provide actionable HR recommendations. The goal is to help businesses understand why employees leave and where to focus retention efforts.
Tools & Technologies
Python (Pandas, NumPy)
Data Visualization — Matplotlib, Seaborn
Skills demonstrated — EDA, attrition analysis, KPI calculation, business insight generation, heatmap analysis
Dataset
1,000 employee records
Features: age, department, job role, salary band, overtime, job satisfaction score, years at company, marital status, education, attrition status
Analysis Performed
#	Analysis	Key Finding
1	Overall Attrition Rate	22.4% attrition across the company
2	Attrition by Department	Sales (26.4%) and Finance (25.5%) highest
3	Attrition by Salary Band	Low salary = 33.5% vs High salary = 13.2%
4	Overtime Impact	Overtime workers leave at 2x the rate
5	Age Distribution	Employees aged 20-30 most likely to leave
6	Job Satisfaction vs Attrition	Low satisfaction drives significantly higher attrition
7	Heatmap: Department x Salary	Sales + Low salary is the highest risk combination
Key Business Insights
Overtime is the strongest attrition driver — employees on overtime leave at nearly 2x the rate (33.6% vs 17.7%)
Salary band directly impacts retention — low-salary employees leave at 33.5% vs 13.2% for high-salary band
Sales and Finance need focused retention programs — both departments exceed the company average significantly
Young employees (20-30) are highest flight risk — early career development and growth paths are critical
Job satisfaction score is a leading indicator — low satisfaction (score 1) predicts high attrition — regular pulse surveys recommended
Charts Generated
`01_overall_attrition.png` — Pie chart of active vs left employees
`02_attrition_by_department.png` — Bar chart with average line
`03_attrition_by_salary.png` — Attrition rate across salary bands
`04_overtime_impact.png` — Overtime vs non-overtime attrition
`05_age_distribution.png` — Age histogram split by attrition
`06_satisfaction_vs_attrition.png` — Job satisfaction score vs attrition rate
`07_heatmap_dept_salary.png` — Heatmap of department x salary band attrition count
How to Run
```bash
pip install pandas numpy matplotlib seaborn
python hr_attrition_analysis.py
```
Project Structure
```
hr-attrition-analysis/
|-- hr_attrition_data.csv              # Dataset (1000 employees)
|-- hr_attrition_analysis.py           # Full analysis script
|-- 01_overall_attrition.png
|-- 02_attrition_by_department.png
|-- 03_attrition_by_salary.png
|-- 04_overtime_impact.png
|-- 05_age_distribution.png
|-- 06_satisfaction_vs_attrition.png
|-- 07_heatmap_dept_salary.png
|-- README.md
```
---
Project by Afeera Begum | Data Analyst | Bangalore, India
