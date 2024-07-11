## HR Analytics Dashboard Insights

### Dashboard Link: https://app.powerbi.com/groups/me/reports/90f17bff-3382-4f3f-aae0-558509833f2a/ReportSection?experience=power-bi


## Project Overview

This project showcases an HR Analytics Dashboard created using Power BI, which provides valuable insights into various HR metrics and workforce dynamics. The dashboard is designed to help organizations make data-driven decisions to improve employee retention, satisfaction, and overall performance.

## Problem Statement
Organizations often struggle with high attrition rates, low employee satisfaction, and inefficient resource allocation. These issues can lead to increased costs, reduced productivity, and a negative impact on overall business performance. Traditional HR management approaches lack the ability to provide real-time, data-driven insights necessary for addressing these challenges effectively.

To tackle these issues, a comprehensive HR Analytics Dashboard is required to:

Monitor key HR metrics such as employee attrition, satisfaction, and performance.
Identify trends and patterns that contribute to workforce challenges.
Provide actionable insights for strategic decision-making.


## Getting Started

# DAX Formula: 

1. Active Employee's = SUM('HR data'[Employee Count])-SUM('HR data'[Attrition Count])

This DAX formula calculates the number of active employees by subtracting the sum of the attrition count from the total employee count. Specifically, the Active Employee's measure is defined as the difference between the total number of employees (SUM('HR data'[Employee Count])) and the total number of employees who have left the organization (SUM('HR data'[Attrition Count])). 

-This calculation provides a clear and straightforward metric to monitor the current active workforce, which is essential for understanding the organization's staffing levels and making informed HR decisions.

2. Attrition rate = DIVIDE(SUM('HR data'[Attrition Count]),SUM('HR data'[Employee Count]),"")

This DAX formula calculates the attrition rate by dividing the total number of employees who have left the organization by the total number of employees. Specifically, the Attrition rate measure is defined as DIVIDE(SUM('HR data'[Attrition Count]), SUM('HR data'[Employee Count]), ""). 

-This calculation provides a precise metric indicating the percentage of employees who have exited the company relative to the overall workforce, offering valuable insights into employee retention and helping HR professionals identify trends and areas for improvement.


## Key Features

Total Employee Overview: Displays the total number of employees, active employees, attrition count, and attrition rate.

<img width="510" alt="image" src="https://github.com/oolajuyi12/HR-Analytics-Dashboard-Insights/assets/173367183/871bff42-a95e-4301-912a-d538df716031"> 


-Demographic Analysis: Includes gender and marital status distribution of employees.

![Screenshot 2024-07-10 225910](https://github.com/oolajuyi12/HR-Analytics-Dashboard-Insights/assets/173367183/801d3d19-d525-4eba-9073-ba56f84a9278)


-Income Analysis: Visualizes the average monthly income by job role.

![Screenshot 2024-07-10 230633](https://github.com/oolajuyi12/HR-Analytics-Dashboard-Insights/assets/173367183/24dbd7ef-a6df-4d03-b68d-db454b48538e)


-Departmental Insights: Shows active employees and the sum of attrition count by the department.

![Screenshot 2024-07-10 231730](https://github.com/oolajuyi12/HR-Analytics-Dashboard-Insights/assets/173367183/d0419d03-a3df-40de-bd41-1af72ab531a6)

-Educational Background: Breaks down active employees by education field and level.

![Screenshot 2024-07-11 081856](https://github.com/oolajuyi12/HR-Analytics-Dashboard-Insights/assets/173367183/a2c65b20-fd36-466b-83ff-26b687d53fc1)

-Performance Ratings: Illustrates performance ratings by department.

![Screenshot 2024-07-11 082235](https://github.com/oolajuyi12/HR-Analytics-Dashboard-Insights/assets/173367183/4529c9ed-e754-40c3-b16f-34d5a918b288)


-Age and Gender Distribution: Provides insights into the age bands and gender distribution of active employees.

![Screenshot 2024-07-11 082732](https://github.com/oolajuyi12/HR-Analytics-Dashboard-Insights/assets/173367183/00d33f63-b2b0-4677-b10c-d922cb3b3904)


-Job Satisfaction: Details job satisfaction ratings by job role.

![Screenshot 2024-07-11 082919](https://github.com/oolajuyi12/HR-Analytics-Dashboard-Insights/assets/173367183/6937dfce-6426-437e-adf0-12db33347988)

-Average Age of Active Employees

![Screenshot 2024-07-11 083441](https://github.com/oolajuyi12/HR-Analytics-Dashboard-Insights/assets/173367183/fd379aa2-d0d0-405e-87c6-818f15b24973)

## Insights

#Employee Demographics:

Total employees: 1,470
Active employees: 1,233
Average age: 37

#Attrition Analysis:

Attrition count: 237
Attrition rate: 16.1%
Highest attrition in R&D department
Monthly Income:

#Highest average monthly income in management roles

#Education Fields:

-Predominantly Life Sciences (41.93%) and Medical (32.52%)

#Performance Ratings:

#Concentrated in R&D and Sales departments

-Job Satisfaction:

#Detailed ratings by job role

-Education Levels:

-Bachelor's degree holders form the largest group
Age and Gender Distribution:

-Diverse age bands and gender representation

##Benefits

-Informed Decision-Making: Enables data-driven hiring, training, and retention decisions.

-Trend Identification: Identifies trends in attrition and job satisfaction.

-Resource Allocation: Optimizes resource allocation by understanding departmental performance.

-Employee Engagement: Enhances engagement through targeted interventions.

## Tools Used
Power BI: For creating and publishing the dashboard:![Screenshot 2024-07-11 085058](https://github.com/oolajuyi12/HR-Analytics-Dashboard-Insights/assets/173367183/ac06d9cc-fd8c-49cf-9ed2-571fb32c4655)


## To view the dashboard: https://app.powerbi.com/groups/me/reports/90f17bff-3382-4f3f-aae0-558509833f2a/ReportSection?experience=power-bi


-Source of Data

## Data Sources: HR data.xlsx https://docs.google.com/spreadsheets/d/1FkDEbK2HCpb6qXgWTb5B0oNaBRHCwYZ3/edit?usp=drive_link 


Access Power BI and import the dataset.
You can use the visuals that are provided to explore insights.

# Contributing
Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

Contact
For further insights or collaboration opportunities, feel free to connect with me at: 

## LinkedIn: linkedin.com/in/olanrewaju-james-olajuyi-9273b6b5 

Olanrewaju Olajuyi
LinkedIn
