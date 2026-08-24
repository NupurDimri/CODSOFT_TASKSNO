# CODSOFT Internship — Task 2

## Exploratory Data Analysis and Business Insights

---

## 1. Objective

The objective of this task is to examine an employee dataset using descriptive statistics and exploratory data analysis techniques.

The analysis focuses on:

- Understanding the structure and features of the dataset
- Examining descriptive statistics
- Identifying trends and distributions
- Studying relationships between variables
- Detecting outliers and unusual patterns
- Answering business questions using summary statistics

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

The dataset contains **490 employee records** and **11 original features**.

---

## 3. Descriptive Statistics

The main numerical variables analyzed were:

- Age
- Salary
- Experience Years

### Age

- Average Age: **38.14 years**
- Median Age: **39 years**
- Minimum Age: **21 years**
- Maximum Age: **55 years**

### Salary

- Average Salary: **₹73,935.93**
- Median Salary: **₹74,272**
- Minimum Salary: **₹25,235**
- Maximum Salary: **₹119,210**

### Experience

- Average Experience: **6.14 years**
- Median Experience: **6 years**
- Minimum Experience: **0 years**
- Maximum Experience: **12 years**

---

## 4. Distribution Analysis

### Salary Distribution

The salary distribution shows that employee salaries range approximately from ₹25,000 to ₹120,000.

A noticeable concentration of salaries occurs around the ₹70,000–₹80,000 range. The distribution contains several salary ranges rather than being concentrated in a single interval.

### Age Distribution

The employee ages range from 21 to 55 years, with the average age being approximately 38 years.

### Experience Distribution

Employee experience ranges from 0 to 12 years, with an average experience of approximately 6.14 years.

---

## 5. Department Analysis

### Employee Distribution

Marketing has the largest number of employees among the identified departments, with **85 employees**.

### Average Salary by Department

Among the identified departments:

- Operations has the highest average salary at approximately **₹78,033**.
- IT has the lowest average salary at approximately **₹69,467**.
- Marketing has the largest workforce with **85 employees**.

The `Unknown` department has an average salary of approximately ₹79,909, but it contains only 7 employees, so it was not considered a reliable department-level comparison.

---

## 6. Relationship Analysis

### Experience and Salary

The correlation between experience and salary is:

**0.069**

This indicates a very weak positive linear relationship between experience and salary.

Therefore, experience alone does not appear to be a strong predictor of salary in this dataset. Other factors such as department, role, location, and performance may have a greater influence on employee compensation.

---

## 7. Outlier Detection

The Interquartile Range (IQR) method was used to identify potential salary outliers.

### Results

- Q1: **₹51,358**
- Q3: **₹98,369.75**
- IQR: **₹47,011.75**
- Lower Bound: **approximately -₹19,159.63**
- Upper Bound: **approximately ₹168,887.38**
- Detected Salary Outliers: **0**

The maximum salary in the dataset is ₹119,210, which is below the calculated upper outlier threshold.

Therefore, no salary values were identified as statistical outliers using the IQR method.

---

## 8. Business Questions

### Q1. What is the average employee salary?

**Answer:** The average employee salary is approximately **₹73,935.93**, while the median salary is approximately **₹74,272**.

### Q2. Which department has the highest average salary?

**Answer:** Operations has the highest average salary among the identified departments, at approximately **₹78,033**.

### Q3. Which department has the most employees?

**Answer:** Marketing has the largest number of employees, with **85 employees**.

### Q4. What is the average employee experience?

**Answer:** The average employee experience is approximately **6.14 years**.

### Q5. Which performance rating is most common?

**Answer:** **Needs Improvement** is the most common performance rating, with **142 employees**, followed by Average with 127, Good with 115, and Excellent with 106 employees.

### Q6. Which city has the most employees?

**Answer:** Dehradun has the highest number of employees, with **57 employees**, followed by Jaipur with 55 and Gurugram with 53 employees. This indicates that Dehradun has the largest workforce concentration among the cities represented in the dataset.

### Q7. Which city has the highest average salary?

**Answer:** Jaipur has the highest average employee salary among the cities analyzed, at approximately **₹79,866.85**. Dehradun ranks second at approximately ₹78,103.40, while Noida has the lowest average salary at approximately ₹67,503.15.

### Q8. Does performance rating relate to salary?

**Answer:** Employees with a **Good** performance rating have the highest average salary at approximately **₹75,365.64**, while employees rated **Excellent** have an average salary of approximately ₹72,810.95. Therefore, the dataset does not show a clear positive relationship between higher performance ratings and higher salaries. Other factors may have a stronger influence on compensation.

### Q9. Which experience group has the highest average salary?

**Answer:** The **9–12 years** experience group has the highest average salary at approximately **₹76,035.22**. The 3–5 years group has the lowest average salary at approximately ₹70,960.07. However, salary does not increase consistently across all experience groups, supporting the earlier finding that experience alone has only a weak relationship with salary.

### Q10. What percentage of employees belong to each department?

**Answer:** Marketing has the largest share of the workforce at **17.35%**, followed by Sales at 14.49% and HR at 13.88%.

The remaining workforce is distributed as follows:

- Operations: **13.47%**
- IT: **13.47%**
- Finance: **13.47%**
- Data Analytics: **12.45%**
- Unknown: **1.43%**

Overall, most identified departments represent approximately 12%–15% of the workforce, indicating a relatively balanced distribution across departments.

### Q11. Which department has the highest salary variation?

**Answer:** Among the identified departments, **Finance** has the highest salary variation, with a standard deviation of approximately **₹28,607.92**.

The `Unknown` category has a higher standard deviation of approximately ₹34,036.36, but it contains only 7 employees and is therefore not considered a reliable department-level comparison.

Operations has the lowest salary variation among the identified departments, at approximately ₹23,783.34.

---

## 9. Key Findings

The exploratory analysis produced the following important findings:

1. The average employee salary is approximately **₹73,935.93**, while the median salary is approximately **₹74,272**.

2. Employee salaries range from approximately **₹25,235 to ₹119,210**.

3. **Operations** has the highest average salary among the identified departments, at approximately **₹78,033**.

4. **Marketing** has the largest workforce, with **85 employees**, representing **17.35%** of the dataset.

5. **Dehradun** has the highest number of employees among the cities, with **57 employees**.

6. **Jaipur** has the highest average salary among the cities, at approximately **₹79,866.85**.

7. The correlation between experience and salary is approximately **0.069**, indicating a very weak linear relationship.

8. The **9–12 years** experience group has the highest average salary, at approximately **₹76,035.22**. However, salary does not increase consistently across all experience groups.

9. Employees with a **Good** performance rating have the highest average salary at approximately **₹75,365.64**. Employees rated Excellent have a lower average salary of approximately ₹72,810.95. Therefore, higher performance ratings do not necessarily correspond to higher salaries in this dataset.

10. The IQR method detected **0 salary outliers**. The maximum salary of ₹119,210 is below the calculated upper outlier threshold of approximately ₹168,887.

11. Among the identified departments, **Finance** has the highest salary variation, with a standard deviation of approximately **₹28,607.92**.

12. Most identified departments represent approximately **12%–15%** of the workforce, indicating a relatively balanced distribution across departments.

---

## 10. Conclusion

This exploratory data analysis examined employee demographics, salaries, experience, departments, cities, and performance ratings using Python, Pandas, NumPy, and Matplotlib.

Descriptive statistics were used to understand the central tendency and spread of numerical variables. Visualizations were created to examine salary, age, and experience distributions. Grouped analysis was used to compare salaries across departments, cities, performance ratings, and experience groups.

The analysis found that experience alone has a very weak linear relationship with salary, while salary differences can be observed across departments and cities. No statistical salary outliers were detected using the IQR method.

Overall, the analysis demonstrates how exploratory data analysis can be used to identify patterns, investigate business questions, and generate meaningful insights from employee data.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Project Files

- `cleaned_employee_data.csv` — Dataset used for analysis
- `Task2_Exploratory_Data_Analysis.ipynb` — Complete analysis and visualizations
- `Task2_Report.md` — Summary of findings and business insights