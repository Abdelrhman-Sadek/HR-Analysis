# HR-Analysis
<p align="center">
  <img src="https://netchex.com/wp-content/uploads/2022/12/HR-Analytics-768x512.png" />
  </p>
</br>

## `Description`

This project aims to analyze and give insights about the employee status such as:
- Some general information like `How many employees do we have(Males, Females)`, `What is their material status, Educational background`, etc
- How many years of service have they spent with the company
- % Employee career levels the company has determined based on their job levels
- Their job satisfaction level working with the company
- % of employees that take overtime shifts
- Age range for every job role
Also, Performing changes from `Retrenchment`and `Promotions` that the organization wants to perform 


The company wants the do some `Retrenchmens`and `Promotions` based on:
</br>
- employees that haven't been promoted 5 years or more get a **Promotion**
- employees that spent over 18 years with the company will be **Retrenched** 
- employees that satisfy both condetion will get **Severance Benefits** due to their services 
Then, visualize how these changes will affect the organization 
<br>

## `Preprocessing`
The data was all in one column so I had to reformat it using `power Query`
<br>
Perform relationships between `HR employee data` and `HR Analytics Data` with joins to gain more insights
<br> 
Add conditional columns like :
- `Pormotion_Stats` based in the company's condition for promotion *(employees that haven't been promoted 5 years or more get a promotion)*
- `Emp_Retrenchment` based in the company's condition for retrenchment *(employees that spent over 18 years with the company will be Retrenched)*
- `Career Level` based on job level *3-5 Senior/0-2 Junior*
- `Distances Status`baced on distance from home  *<= 5 very close,>=10 close,>=20 far,else very far*
And more

<br>

Created:
1. `Promotion` and `Retrenchment` CSVs that have the lists of employees that will get a promotion or will be retrenched
2. `Severance Benefits` CSV that has the duplicate values from `Promotion` and `Retrenchment` tables

## `Dashboards`
### Employee Insights
<p align="center">
  <img src="https://github.com/Abdelrhman-Sadek/HR-Analysis/blob/main/pics/Emp_insights.png" />
  </p>
  
### Changes
<p align="center">
  <img src="https://github.com/Abdelrhman-Sadek/HR-Analysis/blob/main/pics/Changes.png" />
  </p>
  
### Work Filled Insights
<p align="center">
  <img src="https://github.com/Abdelrhman-Sadek/HR-Analysis/blob/main/pics/Dep_insights.png" />
  </p>
