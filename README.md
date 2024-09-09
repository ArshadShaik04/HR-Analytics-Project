HR Analytics Project

Overview:
The HR Analytics Project uses SQL and Power BI to analyze and visualize employee data, focusing on key metrics like employee attrition, job satisfaction, and department-wise trends. The project provides insights that can help HR departments understand workforce dynamics and make data-driven decisions.

Project Structure:
- PowerBI/HR ANALYTICS POWER BI.pbix: A Power BI report that visualizes the HR data and provides key insights.
- Data/HR Data.xlsx: The original dataset in Excel format, containing employee information and related fields.
- Data/hrdata.csv: A CSV version of the HR data used for importing into the SQL database.
- SQL/queries.docx: A document containing SQL queries for analyzing the HR data in PostgreSQL.
- Images/: Screenshots of PostgreSQL query outputs to provide a visual representation of the SQL analysis.

Setup and Usage:

1. Power BI Report
- Open the HR ANALYTICS POWER BI.pbix file in Power BI Desktop to explore the interactive dashboards and visualizations.
- The Power BI report provides a detailed analysis of employee attrition, job satisfaction, and other key metrics.

2. SQL Queries
- Use the SQL queries provided in queries.docx to run data analysis on the HR dataset in a PostgreSQL environment.
- The queries cover various aspects of HR data, such as employee count, attrition rates, and job satisfaction levels.
- Ensure PostgreSQL is installed and configured properly to run these queries.

3. PostgreSQL Query Outputs:
- Attrition by Gender: This query shows the number of employees who have left, grouped by gender. (Refer to output1.png in the Images folder)
- Department-wise Attrition: This query displays the attrition rate across different departments, highlighting areas with the highest employee turnover. (Refer to output2.png in the Images folder)
- Job Satisfaction Rating (Crosstab): This query provides a crosstab view of job satisfaction levels across various job roles, using PostgreSQL's crosstab function. (Refer to output3.png in the Images folder)

Prerequisites:
- Power BI Desktop: Required to view and interact with the Power BI report.
- PostgreSQL: Required to execute the SQL queries. Ensure that the tablefunc extension is enabled for crosstab queries.
- Basic understanding of SQL: To modify or extend the queries provided.

How to Use:
1. Set up PostgreSQL: Create a database and import the data using the hrdata.csv file.
2. Run SQL Queries: Use the queries from queries.docx to perform data analysis and generate insights.
3. Explore Power BI Report: Open the Power BI report file and explore various visualizations and dashboards for deeper insights.

Insights:
- Attrition Analysis: Understand the factors driving employee attrition, including gender and department-related trends.
- Job Satisfaction: Analyze job satisfaction levels across different job roles and departments.
- Employee Demographics: Explore the distribution of employees by age, education field, and other demographics.
