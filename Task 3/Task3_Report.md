# CODSOFT Internship — Task 3

## Data Visualization and Analysis

---

## 1. Objective

The objective of this task is to create meaningful visualizations using Python libraries such as Matplotlib and Seaborn.

The analysis focuses on:

- Creating bar charts
- Creating line charts
- Creating pie charts
- Creating histograms
- Creating scatter plots
- Creating box plots
- Customizing visualizations with titles, labels, legends, and appropriate formatting
- Presenting data insights in a clear and understandable manner

---

## 2. Dataset Overview

The dataset contains employee-related information including:

- Employee ID
- Name
- Age
- Gender
- Department
- City
- Salary
- Joining Date
- Experience Years
- Email
- Performance Rating

The cleaned employee dataset from Task 2 was used for visualization.

---

## 3. Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 4. Visualizations

## 4.1 Bar Chart — Average Salary by Department

A bar chart was created to compare the average salary across different departments.

### Key Findings

- The `Unknown` department shows the highest average salary, but it contains only 7 employees.
- Among the identified departments, **Operations** has the highest average salary at approximately **₹78,033**.
- **IT** has the lowest average salary among the identified departments at approximately **₹69,467**.
- The chart makes it easy to compare salary levels between departments.

### Business Insight

Operations appears to have the highest average compensation among the identified departments. However, salary differences between departments are relatively moderate compared with the overall salary range.

---

## 4.2 Line Chart — Average Salary by Joining Year

A line chart was created to examine how average salary varies according to the employee's joining year.

### Key Findings

- Average salary varies considerably across joining years.
- The average salary reaches its highest point around **2020**.
- Salary decreases from 2020 through 2024.
- There is a noticeable increase in 2025.
- Average salary decreases again in 2026.

### Business Insight

The visualization does not show a consistent upward or downward salary trend based solely on joining year. Salary appears to fluctuate across different joining years.

---

## 4.3 Pie Chart — Employee Distribution by Department

A pie chart was created to show the percentage distribution of employees across departments.

### Key Findings

- **Marketing** has the largest workforce share at approximately **17.3%**.
- **Sales** represents approximately **14.5%**.
- **HR** represents approximately **13.9%**.
- **Operations** represents approximately **13.5%**.
- **Finance** represents approximately **13.5%**.
- **IT** represents approximately **13.5%**.
- **Data Analytics** represents approximately **12.4%**.
- The `Unknown` category represents approximately **1.4%**.

### Business Insight

Marketing has the largest workforce among the identified departments. The remaining departments have relatively similar workforce proportions.

---

## 4.4 Histogram — Salary Distribution

A histogram was created to examine the distribution of employee salaries.

### Key Findings

- Employee salaries range approximately from **₹25,235 to ₹119,210**.
- Salaries are distributed across a wide range.
- A noticeable concentration occurs around the middle salary ranges, particularly around **₹70,000–₹80,000**.
- The distribution does not appear to be concentrated around a single salary value.

### Business Insight

The organization has a relatively broad salary range. Most employees fall within the middle salary ranges, while lower and higher salary levels are also represented.

---

## 4.5 Scatter Plot — Experience vs Salary

A scatter plot was created to examine the relationship between employee experience and salary.

### Key Findings

The correlation between experience and salary was approximately:

**0.069**

This indicates a **very weak positive linear relationship** between the two variables.

The points in the scatter plot do not form a strong upward pattern.

### Business Insight

Experience alone does not appear to be a strong predictor of salary in this dataset. Other factors such as department, job role, location, performance, and responsibilities may have a stronger influence on employee compensation.

---

## 4.6 Box Plot — Salary Distribution by Department

A box plot was created to compare salary distributions across departments.

### Purpose

The box plot helps visualize:

- Median salary
- Interquartile range
- Salary variation
- Minimum and maximum salary ranges
- Potential outliers

### Business Insight

The box plot provides a department-level comparison of salary variation and helps identify departments with wider or narrower salary distributions.

It can also be used to visually inspect potential unusually high or low salary values.

---

# 5. Overall Findings

The visualization analysis produced several important findings:

1. **Operations** has the highest average salary among the identified departments.

2. **IT** has the lowest average salary among the identified departments.

3. **Marketing** has the largest workforce share at approximately **17.3%**.

4. Average salary varies considerably across joining years and does not follow a consistent trend.

5. Employee salaries range approximately from **₹25,235 to ₹119,210**.

6. A large proportion of salaries are concentrated around the middle salary ranges.

7. Experience and salary have a very weak positive relationship, with a correlation of approximately **0.069**.

8. The box plot provides a useful comparison of salary variation between departments.

---

# 6. Conclusion

This task demonstrated how data visualization can be used to transform employee data into meaningful business insights.

Different visualization techniques were selected based on the type of information being analyzed:

- **Bar charts** were used for department-level salary comparisons.
- **Line charts** were used to examine salary variation across joining years.
- **Pie charts** were used to represent workforce distribution.
- **Histograms** were used to understand salary distribution.
- **Scatter plots** were used to examine the relationship between experience and salary.
- **Box plots** were used to compare salary variation across departments.

The analysis shows that visualization makes patterns, comparisons, and relationships easier to understand than examining raw data alone.

---

# 7. Project Files

- `employee_data.csv` — Employee dataset used for visualization
- `Task3_Data_Visualization.ipynb` — Jupyter Notebook containing Python code and visualizations
- `Task3_Report.md` — Summary of visualization findings and business insights

---

# 8. Author

**Nupur Dimri**

CODSOFT Internship — Task 3