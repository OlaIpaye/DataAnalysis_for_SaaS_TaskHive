# DataAnalysis_for_SaaS_TaskHive

TaskHive is a fictional company that offers subscription to their online platform for project management.

## Project Sumnmary

The purpose of this project is to showcase my ability to understand and analyse a dataset using the exploratory data analysis(EDA) process.

**Tools used in this project:**

- Microsoft Excel, for exploratory data analysis(EDA).
- SaaS company Datasets, from Datacamp platform.
- Git, for documenting my process and pushing work to Github.
- Git Bash command line interface, for cloning the remote repository on my local computer and for creating and accessing folders and images for this project.

## Summarising Data Using PivotTable (EDA)

- **Finding out how many subscriptions TaskHive has sold and for how much:**
  Using the TaskHive account sales worksheet, I created a pivot table to quickly summarise, familiarise and explore the dataset I am working with.

  This helped me quickly learn of some important figures such as: **TaskHive sold 35,101 subscriptions and for £693,025, with an average customer bringing in £312 each month.**

Before:
![how to create pivot table in excel](<images/0. Before creating pivot table from TaskHive account sales worksheet.png>)

After:
![creating pivot table in excel](<images/1. creating pivot table to summarise supscription sold, for how much and avearge customer subscription each month.png>)

![pivot table in excel](<images/1.1 created pivot table to summarise supscription sold, for how much and avearge customer subscription each month.png>)

- **Finding out how many sales per paying subscription:**
  Adding the subscription type field to the pivot table allows me to explore the subscription model of the business and learn the reality of how TaskHive operates as a subscription model business.

  Additionally, I wanted to explore how much on average TaskHive made per paying customers since they had a basic subscription type of non-paying customers too.

  So I created a calculated field using this formula (= IFERROR('Sales Amount'/'Licenses Bought', 0)), which allowed me to handle the #DIV!0 error I encountered initially so any cell that would result in a division by zero error will show 0 instead of the error. **This helped me learn the average sales per paying subscription is £20.**

  Before:
  ![division by zero error handling in excel](<images/2. division by zero error handling.png>)

  After:
  ![using calculated field in pivot table in excel](<images/2. calculated average sales per paying subscription with calculated field tab.png>)

* **Finding out subscription type with highest and lowest sales:**
  The **Enterprise subscription type** has the highest sales of £318,600 as shown in the Sum of Sales Amount field and with 11,850 subscriptions bought as shown in the Sum of Licences Bought field. Whilst the **basic subscription type** has the lowest sales of £0 and with zero subscription bought too.

  **Subscription type with highest sales for TaskHive:**
  ![pivot table in excel](<images/2.2 subscription type with highest sales.png>)

  **Subscription type with lowest sales for TaskHive:**
  ![how to create pivot table in excel](<images/2.3 subscription type with zero sales.png>)

##
