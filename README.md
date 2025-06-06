# HR Analytics Dashboard
## Project Objective
The primary goal of the HR analytics dashboard is to provide data-driven insights into workforce metrics such as employee headcount, turnover, attrition trends, hiring patterns, and employee demographics. By leveraging Power BI's interactive visualizations, the dashboard aims to support HR decision-making, improve talent management strategies, and enhance organizational efficiency through timely and informed analysis.
## Datset Used
- <a href="https://github.com/redwan011235/Power-BI-Project/tree/main/Dataset">Dataset</a>
## Tools Used
- Power BI
- Power Query
- Dax Query
## Project Workflow
- Data Import & Preparation:
The raw .csv file was imported into Power BI and loaded into the Power Query Editor for preliminary data transformation and structuring.
- Data Cleaning & Formatting:
Unnecessary columns, duplicate entries, and errors were removed. Column values were standardized, renamed appropriately, and data types were accurately assigned using the auto-detect feature in Power Query.
- Data Transformation & Calculation:
A new column named "AttritionCount" was created using conditional logic: If Attrition = "Yes", then 1; otherwise, 0. This was used to build KPIs and visualizations. A DAX measure for Attrition Rate was also created using:
Attrition Rate = SUM([AttritionCount]) / SUM([EmployeeCount])
to represent the rate as a percentage.
- Data Visualization & Insight Generation:
Multiple visual elements such as bar charts, KPI indicators, tables, and pie charts were developed to explore key HR metrics. These visuals provide a clear, interactive, and insightful representation of the data for better decision-making.
## Analytical Focus Areas
- What is the total number of employees?
- What are the average age and average salary of employees?
- How many men and women have experienced attrition?
- What is the average tenure of employees at the company?
- Which department has the highest number of employees?
- How is the workforce distributed by gender?
- Which education field has the largest representation among employees?
- Which business travel category has the most employees?
  ## Dashboard
  ![Screenshot](https://github.com/redwan011235/Power-BI-Project/blob/main/Screenshot%20of%20HR%20Analytics%20Dashboard/HR%20Analytics%20Dashboard%20%201.jpg),![Screenshot](https://github.com/redwan011235/Power-BI-Project/blob/main/Screenshot%20of%20HR%20Analytics%20Dashboard/HR%20Analytics%20Dashboard%20%202.jpg),![Screenshot](https://github.com/redwan011235/Power-BI-Project/blob/main/Screenshot%20of%20HR%20Analytics%20Dashboard/HR%20Analytics%20Dashboard%20%203.jpg)
## Project Insight
- 📊 HR Analytics Dataset contains detailed employee information, including demographics, job satisfaction, work-life balance, and attrition data for 1,470 employees.
- 📁 Promotion Dataset highlights 72 employees marked as "Due for Promotion" (1 indicates eligible).
- 🧾 Retrenchment Dataset flags employees at risk of being retrenched, where 1 indicates a potential retrenchment candidate.
- 🧹 Initial data preprocessing was required to correct encoding and split tab-separated fields in the HR dataset.
- 🔄 All datasets were merged on Employee Name to provide a unified view of employee performance, retention, and promotion readiness.
- 📈 Exploratory Data Analysis (EDA) revealed patterns in attrition, promotion readiness, and retrenchment risk based on factors such as age, job satisfaction, education level, and distance from home.
- 👥 Employees marked for promotion showed higher scores in performance and job involvement on average.
- ⚠️ Employees at risk of retrenchment often had lower job satisfaction, more frequent job changes, and fewer years at the company.
- 🧠 The project builds a foundation for predictive modeling, such as identifying future attrition or promotion candidates using classification algorithms.
- 📦 The project demonstrates real-world HR decision-making using data-driven insights, useful for talent management and workforce planning.
## Conclusion
This project provides a data-driven overview of employee performance, promotion readiness, and retrenchment risk. By integrating and analyzing HR datasets, it uncovers key workforce trends and supports strategic decisions in talent management.






