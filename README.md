# DSA-Power-BI-Project

### Palmoria Group HR Data Analysis — Summarization

#### Project Background

Palmoria Group, a Nigerian manufacturing company, has come under public scrutiny due to allegations of gender inequality across its three regions. With the goal of expanding internationally, the leadership is eager to address any structural issues — especially those related to gender distribution, salary disparity, and compliance with new wage regulations. As an HR analytics consultant, I was engaged to conduct a comprehensive analysis of the company’s HR data and provide actionable insights.

### Data Cleaning and Preparation

Using Power BI Power Query, the following data quality issues were resolved:

* Removed employees with missing salaries (exited staff).
* Filtered out departments labeled “NULL.”
* Standardized the gender field by labeling all blanks as “Undisclosed.”

Additionally, bonus rules were cleaned by unpivoting department-based percentage ratings for easier mapping during bonus allocation.

### Key Insights Delivered

#### Gender Distribution Analysis

* Gender representation was visualized across departments and regions.
* A stacked column chart and donut chart revealed gender imbalances, particularly underrepresentation of women in certain departments and regions.

#### Performance Rating by Gender

* Ratings such as “Very Good,” “Good,” etc., were analyzed by gender.
* A 100% stacked bar chart exposed inconsistencies in how male and female employees are rated, potentially signaling bias.

#### Gender Pay Gap

* The average salary for each gender was computed and visualized.
* A **matrix visual** by department and region showed significant pay disparities favoring male employees in specific locations and units.

#### Salary Compliance and Distribution

* Employees were grouped into salary bands of \$10,000 increments.
* A salary band distribution chart revealed the majority of employees earn below the regulatory threshold of \$90,000.
* A KPI card calculated the number of non-compliant salaries.

#### Bonus Calculation and Total Pay

* Using the department and performance rating, bonus percentages were assigned to each employee.
* Bonus amounts were calculated and added to the base salary to determine Total Pay.
* A region-wise breakdown of total payouts and bonus sums was presented to guide budgeting.

### Technical Tools and Features Used

* Power Query: for cleaning, filtering, and unpivoting data
* DAX Measures: for salary bands, bonus computations, and compliance metrics
* Visuals: Donut charts, stacked columns, KPI cards, matrices, and salary distribution histograms
* Filtering: Slicers by region, department, and gender enabled interactive exploration

### Recommendations for Management

* Investigate departments and regions where gender imbalance and pay gaps are most pronounced.
* Establish internal policies to ensure rating fairness across all genders.
* Enforce the \$90,000 minimum salary regulation to meet compliance and ethical standards.
* Review bonus allocation models for fairness and consistency.

### Conclusion

This analysis equips Palmoria’s management with critical insights to foster gender equity, ensure regulatory compliance, and create a data-driven roadmap for HR transformation. These insights are essential for enhancing employee satisfaction, brand perception, and long-term global expansion.

Attached is the pdf file and the power BI file link; 
https://www.linkedin.com/in/abimbola-ige-6a7377287

