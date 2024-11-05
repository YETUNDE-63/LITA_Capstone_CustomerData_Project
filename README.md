# LITA_Capstone_CustomerData_Project

### Project Title: LITA_Capstone_CustomerData_Project
------------------

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

[Data Cleansing and Preparations](#data-cleansing-and-preparations)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)

[Data Visualization](#data-visualization)

[Key Insights](#key-insights)

[Acknowledgement](#acknowledgement)

### Project Overview
-------------------
This project is an integration of Excel, SQL and Power BI for analysing Key Customer Segments, Cancellations & Subscription Trends; and visualizing the findings per Customer by Subscription Type & across the Regions. It aims to generate insight into the Key Customer Segments of the LITA CAPSTONE Project within tje duration of subscription. 

By analysing the various parameters in the data gotten from open source (Excel); to gather enough insight to make reasonable decisions which enables to tell compelling stories around the data from the insight gotten and to know the best outcome from the data.

### Data Sources
----------------
The dataset for this project was of LITA Capstone -CUSTOMERDATA.csv. This included 7 variables:
 - CustomerID
 - CustomerName
 - Region
 - SubscriptionType
 - SubscriptionStart
 - SubscriptionEnd
 - Canceled

### Tools Used
--------------

- Microsoft Excel [Download Here](http://www.microsoft.com)
  1. For Data Cleaning
  2. For Analysis
  3. For Data Visualization

 - SQL - Structured Query Language
  - For Querying of Data

- Power BI
  - For Data Entry/Get Data from Open Sources
  - For Data Transformation
  - For Data Visualization
 
- GitHub
  - For Portfolio Building

### Data Cleansing and Preparations
-----------------------------------
- In the initial phase of the Data Cleaning and preparations, we perform the following actions:
  1. Data loading and inspection
  2. Handling missing variables
  3. Data cleaning and formatting

### Exploratory Data Analysis
-----------------------------
- EDA involved the exploring of the Data to answer some questions about the Data such as:
  1. Which region is Top 1 by Active Subscription??
  2. Wchich Subscription Type is the Most Popular?
  3. What is the total number of Active Subscriptions?
  4. What is the total number of Cancelled Subscriptions?
  5.Which 3 Regions are the Top by Subscription Cancellation?

### Key Insights
----------------
- The Top performing product is Shoes Category
- The South Region contributed the highest percentage of total sales
- The month of February has the highest sales

### Data Analysis
-----------------
- This is where we included some basic lines of code or queries or even some of the DAX expressions used during the analysis.
  
  - Example 1:
    ~~~MS-EXCEL
    =SUMIF(C2:C50001,C2:C7,H2:H50001)
    ~~~

 - Example 2:
   ~~~POWER BI
   TopSalesProd = CONCATENATEX(TOPN(1, 'SalesData', [Sales]), [Product], )
   ~~~

- Example 3:
   ~~~SQL
   SELECT COLUMN1, 
   SUM(COLUMN2 AS [ALAS], (SUM(COLUMN2)/(SELECT SUM(COLUMN2) FROM TABLE1) *100)
   AS Percentage
   from TABLE1
   GROUP BY COLUMN1
   ORDER BY SUM(COLUMN2) DESC
   ~~~


### Links
-------
https://wesabimarket-my.sharepoint.com/:x:/r/personal/yetunde_wesabimarket_com_ng/Documents/Desktop/LITA/LITA%20PROJECTS/LITA%20Capstone%20Dataset.xlsx?d=w6ee6388415b6421b878912be82ea23ba&csf=1&web=1&e=9dghgQ


### Data Visualization
-----------------------
![SUBSCRIPTION TRENDS](https://github.com/user-attachments/assets/12e3cd45-4356-476a-ad5b-84e0e82c5bb1)

![KEY CUSTOMER SEGMENTS](https://github.com/user-attachments/assets/1d713790-3b4a-4497-96dc-d1f31b36620c)

![KEY CUSTOMER SEGMENTS1](https://github.com/user-attachments/assets/6ed14bdc-48ea-4576-95b2-611332093aba)



|Heading 1|Heading 2|Heading 3|
|---------|---------|---------|
|Table 1|Table 2|Table 3|



### Acknowledgement
-------------------
I appreciate the Almighty God for the privilege to be part of this journey. My thanks also goes to The Incubator Hub, our Well-equipped Facilitators: Muhsin H. (Excel Facilitator); Femi Ayodele (SQL Facilitator); & Temidayo TeeDee Ayeni (Portfolio building - GItHub/Power BI Facilitator) for the great job done.

