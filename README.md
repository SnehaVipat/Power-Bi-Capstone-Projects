
# HR Analytics - Attrition Dashboard

## Problem Statement

This dashboard helps the HR Department understand the attrition in the organization and its probable causes. It helps the department know if their employees are satisfied . 
Through different charts, they get to know their KPIs, & thus they can iwork upon the root casuess by identifying these area. 

## Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that column Employee id had duplicates which were resolved
- Step 5 : Conditional Column "attrition-count" was created using Attrition values. They were later summed up in the reports
- Step 6 : In the report various KPI s were created for Number of Employees, Attrition , Rate , Average Age , Average Salary and Average Years in the company, using the card Visualizations
- Step 7 : Since the data contains various ratings, thus in order to represent ratings, New Visuals like Donut , Area chart , Stacked Column chart and Matrix
  were created using visualizations pane.
- Step 8 : Visual filters (Slicers) were added for four fields named Human Resources , Research and Sales from Department column
- Step 9 : All the Visuals were aligned with similar properties like Border, Fonts , Colors and Sizes.

