# 2. PWC SWITZERLAND
**Task 1:**


**Task 2:**
**Project Overview:**


**Project Goals:**
Create a dashboard in Power BI for Claire that reflects all relevant Key Performance Indicators (KPIs) and metrics in the dataset. Get creative! 

KPIs include:

- Overall customer satisfaction
- Overall calls answered/abandoned
- Calls by time
- Average speed of answer
- Agent’s performance quadrant -> average handle time (talk duration) vs calls answered
![image](https://github.com/MyLittleToy/Power-BI-Projects/assets/139712656/04c153b1-f9b8-46a5-83db-862c6ff140a1)


**Dataset:**
[01 Call-Center-Dataset.xlsx](https://github.com/MyLittleToy/Power-BI-Projects/files/12642988/01.Call-Center-Dataset.xlsx)








**Task 3:**

**Project Overview:**


**Project Goals:**
- Customers who left within the last month
- Services each customer has signed up for phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
- Customer account information: how long as a customer, contract, payment method, paperless billing, monthly charges, total charges and number of tickets opened in the       categories administrative and technical
- Demographic info about customers – gender, age range, and if they have partners and dependents
- 
[02 Churn[PhoneNow inputs (3).pdf](https://github.com/MyLittleToy/Power-BI-Projects/files/12642964/PhoneNow.inputs.3.pdf)

**Data Cleanup Phase:**
I utilised Power Query to conduct the following tasks:
- Data type validation
- Checking for 'nulls' within the data set.
  - Within the dataset I identified 11 records in the 'TotalCharges' column that had null values.  I utilised the following formula to amend these values to those within       the TotalCharges column.  My reasoning being that these 11 customers were new customers and did not have any other monthly charges.
    = Table.ReplaceValue(#"Filtered Rows",null,each [MonthlyCharges],Replacer.ReplaceValue,{"TotalCharges"})

**Visual Creation Phase:**
Per the request, I created separate tabs for each task's visualisations, and utilised Power BI to create my visuals for the data.

**Presentation and Analysis Phase:**


**Dataset:**
(https://github.com/MyLittleToy/Power-BI-Projects/files/12642963/02.Churn-Dataset.xlsx)

https://cdn.theforage.com/vinternships/companyassets/4sLyCPgmsy8DA6Dh3/PhoneNow%20inputs%20(3).pdf

