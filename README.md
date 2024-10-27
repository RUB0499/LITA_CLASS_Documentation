# LITA_CLASS_Documentation

### Project Title: Incubator Hub Milestone

### Project Overview
---
This involves finding solutions to data problems using data analytical tools, thereby creating insights and business strategies. The purpose of data analysis is to understand, interpret and present data adequeately for easy call to action

### Data Source
---
The primary Source of data are CSV files downloaded from open source kaggle  or other repository site

### Tools Used
---
- Microsoft Excel [Download Here](https://www.microsoft.com)
  1. For Data Cleaning
  2. For Analysis
  3. For Visualization
- SQL - structured Query Language
  1. For querying data
- Github
  1. For portfolio building

### Data cleaning and Preperations
---
We perform the following actions;
1. Data loading and Inspection
2. Handling missing varibles
3. Data cleaning and formatting

### Exploratoy Data Analysis
---
EDA involves the exploring of data to answer some question about the Data such as;
- What is the overall sale trend
-  Which product or rigion are the top sellers
- What are the products on peak sales?

### Visualization
---
![image](https://github.com/user-attachments/assets/71c485af-2b82-4bef-a9f7-451a566471c6)

# LITA_ POWER BI _DOCUMENTATION

BI Class Preview
---
We went through data entry, Data cleaning using a columinal data. practise Power BI using an HR data

HR Data Source
---
This data was  downloaded as an CSV file. The data contained document and information about a companyemployee,stating each employee businesstravel,age band,department,gender, educational field, job role,Attrition, marital starus etc....

Steps in visualizing the HR data
---
- Downloaded the data
- Cleaned the data
- Changed types
- Promoted header
- Added conditional column
- Renamed column

![LITA CLASS WORK 10_26_2024 6_21_17 PM](https://github.com/user-attachments/assets/2af358a4-659d-47ec-ac8e-743821afda6e)

Calculations from this data
---
1. Total number of current employee =(Total number of employee - Total number of Attrition)
2. Attrition rate = (sum of attrition  count / sum of employee count)

What is Attrition
---
Attrition refers to a gradual reduction in the number of employees in a company due to various factors like resignations, retirements, or even deaths, without the company necessarily filling these vacancies. In a business context, attrition is often measured as a percentage and is an indicator of workforce stability.

HR Visualisation
---
![LITA CLASS WORK 10_24_2024 1_08_59 PM](https://github.com/user-attachments/assets/ae6df4a6-4c85-4165-a349-7d27c0694d5a)

- Total employee was gotten from employee count
- Total number of current employee =(Total number of employee - Total number of Attrition), which was displayed using card visual tool
- Average age was also gotten from CF-age band column, which was made possible by the use of measure
-  Attrition rate = (sum of attrition  count / sum of employee count) 16%
-  Doughnut chat showing the attrition count by department
-  Bar chart to visualise the count of attrition count by educational field
-  Pie chart shows the amount of attrition by gender

Facts From HR Data
---
1. R$D  Department has the highest level of attrition count 133(56.12%),HR Department has the least attrition count 12(38.06%)
2. life science field has the highest amount of attrition 89 followed by medical field 63, while Human resources field has 7 attriton count, why?
3. Male gender has an attrition count of 150(63.29%), female has 87(36.71%)

- WE noticed that the rate of attrition of employee in the life science and medical educational field are on the high side, which is due to the nature of their field it require constant development

Advise
---
the company should create a car   development plan for it employees, so they can improve the employee retention rate. Employees get to improve in their educational field and then work at the same time


#LITA_CAPSTONE_PROJECT_DOCUMENTATION
---
I documented my final project here, where i worked on a sale data and customer data set through the series of excel, sql then power Bi. Data set link is down below for your personal use
These data contain two data set for:
1. sales data- which show the selling purchase of different product at different regions
2. Customer data- Which customer behaviour to TV Subscription over a certain period of time
[Download here]_https://docs.google.com/spreadsheets/d/12yT7pnZz6-XUSfskManIIpcUO7EBY82i?rtpof=true&usp=drive_fs

Steps taken in excel
---
- Loaded the data
- Cleanedbthe data
- Removed duplicate
- Created pivot table for different visualisation needs
- create report

![LITA Capstone Dataset - Excel 10_26_2024 10_31_59 PM](https://github.com/user-attachments/assets/168e4efe-3ecc-4027-8eeb-fca062caf501)
Sale data

![LITA Capstone Dataset - Excel 10_26_2024 10_32_37 PM](https://github.com/user-attachments/assets/c210242c-3a35-45a7-ba1e-95edd64535b9) Cuctomer data

Pivot Tables for Each Data set
---
![LITA Capstone Dataset - Excel 10_26_2024 10_43_58 PM](https://github.com/user-attachments/assets/409da653-6797-495c-8b21-184c39322a64) 
![LITA Capstone Dataset - Excel 10_26_2024 10_44_22 PM](https://github.com/user-attachments/assets/766d10ca-e540-41e5-b14d-c57337d67a74)
Sale data

![LITA Capstone Dataset - Excel 10_26_2024 10_43_18 PM](https://github.com/user-attachments/assets/06249ead-f94d-4dd2-a969-7bfe7f4478c2) customer data

Calculations in Both data set
---
- Total sale = Quantity * Unit price
- Average Total sale = Total sale / Product Quantity
- Overall Quantity = SUM(F2:F9922)
- Overall Total Sales= sum of total sale in each rigion
- Average sale per product = overall total sales / Total quantity

Visualisation For both Data Set
---
![LITA Capstone Dataset - Excel 10_26_2024 11_36_27 PM](https://github.com/user-attachments/assets/654fd176-0d7b-4e8a-b4f1-e79cd811fcbf)
![LITA Capstone Dataset - Excel 10_26_2024 11_36_45 PM](https://github.com/user-attachments/assets/7fdccd73-a381-49e6-ba92-e7963165e8c9)Sale Data

![LITA Capstone Dataset - Excel 10_26_2024 11_35_21 PM](https://github.com/user-attachments/assets/8dc87606-bc85-4fcc-bf3d-25587b617a34)
![LITA Capstone Dataset - Excel 10_26_2024 11_35_44 PM](https://github.com/user-attachments/assets/c48eac5f-c17c-4041-8dda-8ade390c37e6) Customer Data


Power BI Capstone 

BI Sale Data visualisation
---
![capstone LITA Final Project 10_25_2024 1_44_06 PM](https://github.com/user-attachments/assets/c4086c0c-de3d-4bb8-8474-277cac135b9f)

- Total turn over is 18million
- South has the highest number of sale, while west has the lowest sales
- The highest product brought is hat,jacket has the lowest
- Shoes has the highest % total sales 29.19%, socks has the lowest% total sales of 8.6% 0f the total sale

BI Customer Data Visualisation
---
![capstone LITA Final Project 10_27_2024 12_40_16 AM](https://github.com/user-attachments/assets/0441732b-244f-4ecf-a825-a0a65917069e)

- Basic subscription has thehighest % of cancled subscription by 50% the total revenue
- April 2022 has the lowest revenue
- Premium subscription  has a total revenew of 17M, 25% of cancled subscription. it highest revenew was in june 2023
- Standard subscription has a total revenue of 17M, 24.92% of cancled subscription
- East region has the highest revenue, north is the least

 Overall Conclustion 
 ---

 Customers subscription purchase is determined by many factors ranging from;
 1. Money factor
 2. Regional factor
 3. Time and seasons of the year
 4. Kids & Children factor

