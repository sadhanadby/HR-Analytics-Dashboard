# HR-Analytics-Dashboard
Analyzing employee attrition trends to help HR teams improve retention strategies.

## 📌 Project Overview

Employee attrition is a critical issue for businesses, leading to increased recruitment costs, loss of skilled talent, and disruptions in operations. This project analyzes HR data to uncover key factors driving attrition and provides actionable insights to improve employee retention strategies.

## 🎯 Business Problem Solved

This analysis helps HR teams:

<ul>
  <li>Identify the highest-risk employee groups prone to attrition.</li>
  <li>Recognize patterns in attrition based on tenure, age, and education field.</li>
  <li>Improve job satisfaction by understanding employee sentiment.</li>
  <li>Develop targeted retention strategies using data-driven insights.</li>
</ul>

## 🔑 Key KPIs & Metrics:

| Metric               | Dax | Value |
|----------------------|-------|-----|
| Total Employees      | Employee_Count = DISTINCTCOUNT(HR_Analytics[EmpID]) |1470  |
| Attrition           | Employee_Attrition = CALCULATE(HR_Analytics[Employee_Count], HR_Analytics[Attrition] = "Yes") | 237   |
| Attrition %         | Attrition_% = [Employee_Attrition]/[Employee_Count] | 16.12% |
| Avg Years at Company | Years_at_company = ROUND([Avg_Years_At_Company], 0)&" Years" | 7     |
| Avg Salary          | Average_Salary = AVERAGE(HR_Analytics[MonthlyIncome]) | 6.5K  |
| Avg Age            | Avg_Age = AVERAGE(HR_Analytics[Age]) | 37     |

![image](https://github.com/user-attachments/assets/f8cbef0d-9212-4da9-81fb-49a3d78dc26d)


## 📊 Visual Insights & Findings

1️⃣ Attrition by Years at Company (Area Chart)

<ul>
  <li>Highest attrition (198 employees) occurs at 5 years of tenure.</li>
  
  <li>Second highest attrition (171 employees) occurs at just 1 year, indicating early dissatisfaction.</li>
  
  <li>Lowest attrition (14 employees) at 12 years, showing long-term employees tend to stay.</li>
</ul>

![image](https://github.com/user-attachments/assets/98a3edd2-637a-4f27-aeca-74c1b579ea56)

🚀 Solution: Focus on retention strategies for employees in their 1st and 5th years, such as better onboarding and career development programs.

2️⃣ Attrition by Age Group (Clustered Column Chart)

<ul>
  <li>Employees aged 26-35 have the highest attrition (116 employees), followed by 18-25 age group (44 employees).</li>
  <li>Attrition is lowest (8 employees) in the 55+ age group, indicating experienced employees tend to stay.</li>
</ul>

![image](https://github.com/user-attachments/assets/bbe1c573-494f-419b-9f31-067c54ae7b55)


🚀 Solution: Younger employees may leave due to limited growth opportunities. Implement mentorship programs, skill development, and internal promotions to retain them.

3️⃣ Attrition by Education Field (Donut Chart)

<ul>
  <li>Life Sciences field has the highest attrition (37.55% / 89 employees).</li>
  <li>Medical field has the second highest attrition (26.58% / 63 employees).</li>
  <li>HR field has the lowest attrition (2.95% / 7 employees), indicating stability in administrative roles.</li>
</ul>

![image](https://github.com/user-attachments/assets/f63fddaf-b337-4be9-8606-0dc9fec8bb09)


🚀 Solution: HR teams can explore why attrition is high in technical fields and introduce role-specific engagement programs.

4️⃣ Job Satisfaction Levels (100% Stacked Bar Chart)

<ul>
  <li>Highest attrition in Laboratory Technicians (23.94%), Sales Executives (17.48%), and Research Scientists (16.10%).</li>
  <li>Low job satisfaction (ratings 1 & 2) is a key factor, but other issues like career growth and workload may contribute.</li>
</ul>

![image](https://github.com/user-attachments/assets/0ce6f83b-07cc-42db-8991-89fd3ebac62a)


🚀 Solution: Address salary, career growth & workload concerns to reduce attrition.

5️⃣ Interactive Button Filters & Features

<ul>
  <li>Gender Filter: Compare attrition trends for male and female employees.</li>
  <li>Department Filter: Check attrition for specific departments.</li>
  <li>Light & Dark Mode: User-friendly theme customization for better visibility.</li>
</ul>

![image](https://github.com/user-attachments/assets/8cbcaf87-efb2-43a4-ad9b-48a4d504da15) 
![image](https://github.com/user-attachments/assets/e3676552-d87a-4565-9dad-93c85adc3fd4)
![image](https://github.com/user-attachments/assets/8f984e70-39c9-4d0b-a713-65b07c3b022e)

## 🎯 Final Takeaway

This project showcases how data analytics can drive HR decision-making by identifying key attrition trends and helping organizations improve employee retention. By leveraging Power BI dashboards, HR teams can pinpoint high-risk employee groups, analyze job satisfaction levels, and design effective retention strategies to reduce turnover.

For businesses, reducing attrition means lower recruitment costs, improved workforce stability, and higher employee engagement. This project demonstrates how data can be a powerful tool in workforce planning and can directly impact business profitability and employee satisfaction.

#### 📢 Check out the full analysis in the Power BI dashboard!




