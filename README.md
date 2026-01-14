
#Sales Data Analysis Project [ Power Bi]


### Dashboard Link :[ https://app.powerbi.com/view?r=eyJrIjoiYjk4MzZlMDctNjJiMy00NzE2LWExOGItYjg1NzM1YTMyODRmIiwidCI6IjRmMTQ4MDg0LTUyYzMtNDJiNS1hODAxLWQ3MmEzYWI3NjU1YyJ9 ]

## Problem Statement

Performed end-to-end sales data analysis using Power BI to identify trends, patterns, and business insights. Collected and cleaned raw sales data from multiple sources, transformed it using Power Query, and built data models to enable accurate reporting. Created interactive dashboards and visualizations to track sales performance, revenue, profit, regional sales, and product-wise analysis. Used DAX measures to calculate KPIs such as total sales, growth rate, monthly trends, and customer contribution. The analysis helped stakeholders make data-driven decisions, improve sales strategies, and monitor overall business performance effectively.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : There were a lot of null values ​​present in one of the fact tables, so I replaced the null values ​​using the left join function.
- step 4 : Built relationships between tables (fact table, Dim Product,Dim Promotion, Dim Customer, Date Table 1, Date Table 2) to enable accurate analysis.
 

- Step 5 :Stack holder wants to show top/bottom 5 products based on sales/profit/quantity sold, so I created stacked bar chart in Power BI and showed top/bottom 5 products based on sales, profit and quantity.
- Step 6 : Stackholder wants to Show relationship between sales & profit, than i created Scatter Chart in power Bi and show the relationship between sales and profit.
- Step 7 : Stackholder wants to Compare sales/profit/quantity sold between any two periods selected by the user so I created a two time period column using DAX expression was written.
  
          Date Table 1 = CALENDARAUTO(). 
          Date Table 2 = CALENDARAUTO().
  Snap of new Date column

  
 <img width="163" height="563" alt="two Date column" src="https://github.com/user-attachments/assets/c92aa7b9-4b55-490e-b2fe-1d608e795cd6" />

- Step 8 : The stakeholder wants to see the sales according to different cities, I have shown all the different cities using a map.

 <img width="126" height="164" alt="map" src="https://github.com/user-attachments/assets/c3163f51-160c-47b6-afd4-6b4779791ef0" />


 ## Customer requirments
 1) Top/Bottom 5 product by Sales/Profit/Quantity Sold.
 2) How do sales trends vary over time (daily, monthly, quarterly, annually)
 3) Show relationship between sales & profit.
 4) Compare sales/profit/quantity sold between any two periods selected by the user.
 5) Average discount offered in each discount category.
 6) Total number of orders.
 7) Show Sales/Profit/Discount/Net Sales/All remaining fields for each order that could be filtered using visual filters. (Product/Date/Customer ID/Promotion Categories)
 8) Show sales by different cities.
 <img width="1128" height="573" alt="requirment" src="https://github.com/user-attachments/assets/649cb773-89c1-41bb-bacc-7d2311e593e6" />

## Deshboard Look like
step1 : Top/Bottom 5 product by Sales/Profit/Quantity Sold.

<img width="1361" height="663" alt="top5, bottom 5 " src="https://github.com/user-attachments/assets/4093f6f3-3b06-499d-a865-63b55621a0c3" />

step2 : sales trends vary over time (daily, monthly, quarterly, annually).
<img width="891" height="209" alt="sales trend by period" src="https://github.com/user-attachments/assets/a6a996e0-7dba-4405-bc78-fd28d66073bb" />

Step3 :  Show relationship between sales & profit.

<img width="299" height="244" alt="relation between sales and profit" src="https://github.com/user-attachments/assets/520321d3-38d0-4271-aee1-ea7daff1292d" />

Step4 : Compare sales/profit/quantity sold between any two periods selected by the user.
<img width="793" height="444" alt="sales profit Quantity between two period" src="https://github.com/user-attachments/assets/704147fe-4bf9-48f7-8208-cd69ce1e6198" />



