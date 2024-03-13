# Employee-Attrition-Analysis
##  Problem Statement :- 
Employee attrition is a critical concern for organizations as it can lead to disruptions in workflow, loss of institutional knowledge, and increased recruitment costs. Understanding the factors contributing to employee turnover is essential for organizations to develop effective retention strategies and maintain a stable workforce.The objective of this project is to analyze employee attrition data to identify key factors influencing attrition rates within the organization. By uncovering patterns and trends in employee data , the organization aims to gain insights that will inform strategic decisions to improve employee retention and mitigate attrition risks.

## Steps Followed :
- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present. 
- Step 5 : For the Dashborad there are 2 pages named as "HR Analytics1" and "HR Analytics2".
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Since the data contain "Age","Attrition","Department","Education","job level","Employee count","Employee ID"and so on thus in order to represent all these data a visual called KPI were added on the canvas.
- Step 7 : Visual filters (Slicers) were added for "job role","Education field","Department","Age","Job level".
- Step 8 : KPI 1 shows the visual of stacked coloumn chart for the count of employee and clustered bar chart for the count of employee over 18 versus gender.
- Step 9 : KPI 2 shows the visual of line chart For the total working years versus years at company and line and clustered coloumn chart for the percent salary hike of the employee by education field. 
- Step 10 : KPI 3 is a visual of performance ratings of department and stacked bar chart for the count of employee in each job role.
- Step 11 : KPI 4 represents the visuals of donut For the job satisfaction and stock option level by gender.
- Step 12 : KPI 5 represents the visuals of pie chart For the job involovement and monthly income by gender. 
- Step 13 : KPI 6 represents the visuals of clustered coloumn chart For the employee attrition by gender and clustered bar chart for thestandard hours and worklife balance.
- Step 14 : KPI 7 represents the visuals of funnel For the training time by department.

## Snapshot of Dashboard[Power BI Desktop]
Page 1 :HR Analytics 1
![Screenshot (13)](https://github.com/Harhare18/Crop-Production-Analysis-in-India/assets/101700437/e3bc20a3-28d1-4b6b-add3-bca6053ff687)
 

page 2 :HR Analytics 2
![Screenshot (12)](https://github.com/Harhare18/Crop-Production-Analysis-in-India/assets/101700437/4df6048f-ef99-4b0f-a709-9245e328222d)



## Insights :
Following inference can be drawn from the Dashboard    
KPI 1:
- There are 2.6k male and 1.8k female employee.

KPI 2:
- There is higher count of working years of male employee as compared to female employee.
- There are 28k perecent salary hike and 1089 male employee and 720 female employee in the education field of life sciences.

KPI 3:
- Reasearch and Developement deaprtment has the maximum performance ratings of employee with 5.5k of male employee and 3.7k of femle employee.
- Sales Executive job role has the maximum count of employee with 582 of male employee and 396 of female employee.

KPI 4:
- There are 60% of male employee and 40% of female employee which are statisfied with a job.

KPI 5:
- there are 60.33% of male employee and 39.67% of female employee has the job involovement.

KPI 6:
- There are very less attrition of the employee such as 441 of the male employee and 270 of the female employee has attrition.

KPI 7:
- Research and Developement department has a training time of last year is 100%.
