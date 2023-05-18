# HR-Analysis
<p align="center">
  <img src="https://netchex.com/wp-content/uploads/2022/12/HR-Analytics-768x512.png" />
  </p>
</br>

## `Description`

The aim of this project is to analyze and give insights about the employee status such as:
- Some general information like `How many employees do we have(Males,Females)`,`What is there material status,Educational background`,etc
- How many years of service do they spent with the company
- % Employee career levels the company has determined based on their job levels
- Their job satisfaction level working with the company
- % of employees that take over time shifts
Also, Performing changes from `Retrenchment`and `Promotions` that the organization wants to perform 


The company wants the do some `Retrenchmens`and `Promotions` based on:
</br>
- employees that haven't been promoted 5 years or more get a **Promotion**
- employees that spent over 18 years with the company will be **Retrenched** 
- employees that satisfy both condetion will get **Severance Benefits** duo to there services 
Then, visualize how these changes will affects the organization 
<br>

## `Preprossing`
The data was all in one column so I had to refromat it using `power Query`
<br>
Preform relationships between `HR employee data` and `HR Analytics Data` with joins to gain more insights
<br> 
Add conditional columns like :
- `Pormotion_Stats` baced in the compamy's condition for promotion *(employees that haven't been promoted 5 years or more get a promotion)*
- `Emp_Retrenchment` baced in the compamy's condition for retrenchment *(employees that spent over 18 years with the company will be Retrenched)*
- `Career Level` baced on job level *3-5 Senior/0-2 Junior*
- `Distances Status`baced on distance from home  *<= 5 very close,>=10 close,>=20 far,else very far*
And more

<br>

Careated `Promotion` and `Retrenchment` CSVs that have the lists of employees that will get a promotion or will be retrenched
