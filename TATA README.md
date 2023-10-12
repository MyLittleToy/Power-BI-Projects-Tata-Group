# Power-BI-Projects

# 1. TATA GROUP
   Data Visualisation: Empowering Business with Effective Insights

**Project Overview:**
I was tasked with analysing available data to understand key revenue drivers & growth opportunities. I also provided actionable insights to the CEO and CMO. The results of my analysis was presented through a Power BI dashboard to aid decision-making and expansion planning.

**Project Goals:**
- Analyse revenue-driving factors from operational and marketing perspectives.
- Identify key strengths and growth opportunities.
- Provide insights for strategic planning & expansion.
- Present findings through visualisations tailored to requirements.

**Dataset:**
[Online Retail.xlsx](https://github.com/MyLittleToy/Power-BI-Projects/files/12643037/Online.Retail.xlsx)

**Data Cleanup Phase:**
I identified and excluded inaccurate data (returns, negative quantities, and negative unit prices). I also utilised conditional formulas to filter out incorrect data, ensuring good quality data for my analysis.

**Visual Creation Phase:**
Per the request, I created separate tabs for each task's visualisations, and utilised Power BI to create my visuals for the data.

**Presentation and Analysis Phase:**
My findings were presented as a video presentation piece in which I explained the process taken to clean the data and my rationale for each visualisation. I then discussed the insights gleaned from the data along with the implications for the business strategy.

_1. Data Analysis and Visualisations:_
Time Series Revenue Analysis - I created a time series line chart showcasing the monthly revenue and seasonal variations for the requested year.

<img width="329" alt="Q1" src="https://github.com/MyLittleToy/Power-BI-Projects/assets/139712656/9fcf269f-47ef-4446-a0c0-f5618206316d">

_2. Top Revenue-Generating Countries Analysis:_
A bar chart was utilised to identify and showcase the top revenue-generating countries (excluding the UK) which included the quantities sold.

<img width="281" alt="Q2" src="https://github.com/MyLittleToy/Power-BI-Projects/assets/139712656/feba0404-bb8f-41c4-b7a2-0b827dd44d33">

_3. Top Customer Revenue Analysis:_
A matrix tabe was used to identify the top 10 customers by revenue in a descending order. I included revenue as a monthly view to ensure quick oversight of any variations in customer revenue.

<img width="575" alt="Q3" src="https://github.com/MyLittleToy/Power-BI-Projects/assets/139712656/f5855989-06da-449b-ac39-28a3d2add20e">

_4. Product Demand by Region Analysis:_
A waterfall chart was used to identify the regions with high product demand to guide the business's expansion strategy.

<img width="332" alt="Q4" src="https://github.com/MyLittleToy/Power-BI-Projects/assets/139712656/3a6f2172-afb5-4d45-bfa5-c52fa00da86a">








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


