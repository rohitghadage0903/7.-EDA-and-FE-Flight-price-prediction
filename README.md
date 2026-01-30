#  HR Analytics: Employee Engagement & Performance Analysis

##  Project Overview
Evaluating employee performance and efficiency is one of the most critical and challenging tasks for HR professionals. This project uses **Exploratory Data Analysis (EDA)** to help HR departments gain valuable insights into their workforce, identify patterns in employee engagement, and understand factors affecting performance and retention.

##  Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation:** `Pandas`, `NumPy`
* **Visualization:** `Seaborn`, `Matplotlib`
* **Environment:** Jupyter Notebook

##  Key Analysis Features
### 1. Workforce Demographics
* Analyzed distribution of employees across different departments and positions.
* Explored gender diversity and marital status within the organization.

### 2. Performance & Engagement
* Visualized **Performance Scores** to identify top-tier talent and those needing support.
* Correlated **Engagement Survey** scores with employee satisfaction and special project involvement.

### 3. Recruitment & Retention
* Identified the most effective **Recruitment Sources** (LinkedIn, Indeed, etc.) for high-performing employees.
* Analyzed **Termination Reasons** to understand why employees leave the organization.

### 4. Productivity Insights
* Investigated the relationship between **Absences** and performance ratings.
* Analyzed the count of **Special Projects** handled by employees to measure extra-mile contributions.

##  Key Insights from the Data
* **Demographic Distribution:** The distribution of employees by gender shows a higher number of female employees compared to male employees.
The 'Production' department has significantly more employees than any other department, followed by 'IT/IS' and 'Sales'. 'Executive Office' and 'Admin Offices' have the fewest employees.

* **Performance and Satisfaction:** A large majority of employees 'Fully Meet' performance expectations, with a smaller number 'Exceeding' expectations. A notable minority 'Needs Improvement' or are on a 'Performance Improvement Plan' (PIP).
Employee satisfaction ratings are generally high, with the most common rating being 3, followed closely by 5 and 4. Very few employees reported satisfaction ratings of 1 or 2, indicating overall good satisfaction levels.

* **Recruitment Sources:** 'Indeed' and 'LinkedIn' are the most effective recruitment sources, bringing in the highest number of new hires. 'Google Search' and 'Employee Referral' are also significant contributors.
'On-line Web application' and 'Other' sources have yielded the fewest hires, suggesting they are less effective.

* **Salary Distribution:** The box plot of salary by department clearly shows that the 'Executive Office' department has the highest salaries, with some outliers earning exceptionally high amounts. 'IT/IS' and 'Software Engineering' also show relatively high salaries with some outliers.
The 'Production' department, despite having the most employees, generally has the lowest salary range, with fewer high-earning outliers.

* **Engagement Survey by Position:** 'President & CEO' has the highest average engagement survey score, which is expected for a leadership role. Other high-ranking positions like 'Director of Operations' and 'Chief Information Officer' also show high engagement.
Positions like 'Production Technician I' and 'Production Technician II', which are numerous and typically lower-paying, show varied but generally good engagement scores.

* **Termination Reasons:** For terminated employees, 'Another position' and 'unhappy' are the most frequent reasons for departure, suggesting that employees are often leaving for better opportunities or due to dissatisfaction.
Other significant termination reasons include 'more money', 'career change', and 'hours', highlighting common reasons for employee turnover.
Reasons like 'Fatal attraction' and 'Learned that he is a gangster' are rare and stand out as unique or possibly data entry anomalies.
##  Project Structure
```text
├── HRDataset_v14.csv                         # Raw HR Dataset
├── EDA HR-analytics-employees-engagement.ipynb  # Comprehensive Analysis Notebook
└── README.md                                 # Project documentation
