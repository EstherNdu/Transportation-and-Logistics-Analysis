# Transportation-and-Logistics-Analysis

# Brief Introduction
NEU is a leading provider of dairy products, food items and beverages operating within the fast moving consumer goods (FMCG) sector. The company is committed to delivering high quality consumables efficiently and reliably to meet the needs of her diverse consumer base

This report focuses on analyzing the company's supply chain performance with particular emphasis on On-Time-In-Full Rate, Late Delivery Rate, and Incomplete Deliveries. By eveluating these indicators, this report aims to highlight areas of operational strength and identify opportunities for improving efficiency, reliability and consumer satisfaction across the supply chain.

# About The Dataset
The dataset has 4 tables - Target, Customer, Product and Fact-Orders tables which came in CSV format. Data transformation and analysis was done using Power Query and Power BI

# Problem Questions

* Order Fulfilment Report

  Create an order fulfilment report that shows the overview of supply chain performance - including metrics such as avg lead time, late delivery rate and incomplete deliveries e.t.c

* Customer Report

  Create a report showing the customers whose expectations are not being met and our high valued customers

* Product Fulfilment

  We want to see product performance in order to have a comprehensive view of how the products are performing within the business.

# Tool Used 
  Power BI

# Processes 
* Imported CSV files into Power BI
* Transformed the data using Power Query
* Loaded the data into Power BI for Analysis & Reporting
* Modeled the data
* Used DAX to perform indepth analysis
* Used order placement date & actual delivery date to get the average lead time
* Used the actual delivery date & agreed delivery date to get the percentage of late deliveries
* Created the report wireframe using Figma
* Created interactive reports


# Data Modeling
<img width="1640" height="612" alt="Screenshot 2025-07-13 223142" src="https://github.com/user-attachments/assets/a78221ff-15ab-4103-8a99-74ade1841ff8" />


# Key Insights

<img width="1122" height="163" alt="Screenshot 2025-07-14 220014" src="https://github.com/user-attachments/assets/2932ff67-52dd-4359-b8ed-76fc59f435a0" />


*  Avg Lead Time: 2.42 days.
*  Late Deliveries: 28.9% - increased by 3.6% MoM, highlighting rising delay risks.
*  Incomplete Deliveries: 19K - a slight MoM improvement, but still needs further improvement.
*  OTIF Rate: 47.95% - decreased by 1.7% MoM, indicating a decline in on-time and in-full deliveries.

<img width="1131" height="232" alt="Screenshot 2025-07-14 221428" src="https://github.com/user-attachments/assets/fcdb5ca0-87d5-48c2-ab6e-d851dfa29841" />


* Customers Coolblue and Acclaimed stored had the lowest OTIF Rate of 13.75% and 15.24% respectively.
* Vadodara and Ahmedabad were the Cities with the least OTIF Rate of 45.22% and 48.33% respectively.
* OTIF (On-Time In-Full) Rate: 47.95% which is significantly under the 65.91% target.

<img width="1135" height="251" alt="Screenshot 2025-07-14 232245" src="https://github.com/user-attachments/assets/a8c6ce46-d7ea-4570-95cc-807e171b8999" />


* The bottom 5 customers by delivery rate (e.g., Acclaimed Stores, Coolblue, Elite Mart) have OTIF rates well below standard - with late delivery rates peaking above 70%. Interestingly, these same customers are among the top 5 by order quantity (over 1.1M units each) - revealing a mismatch between customer value and service level.
  
**N/B** This shows that high-volume customers are receiving poor fulfillment, which poses both financial and reputational risk.


<img width="1135" height="253" alt="Screenshot 2025-07-14 232940" src="https://github.com/user-attachments/assets/d35a06aa-98d8-4852-951a-80c7e7c63e2e" />


* On-Time-In-Full rate, On-Time Delivery rate and In-Full Delivery rate were all below target


<img width="1143" height="253" alt="Screenshot 2025-07-14 233445" src="https://github.com/user-attachments/assets/9b1fc08e-3ce2-4b9c-8ec7-2219c6dd274b" />


* All Products showed high incomplete delivery volumes.
* Beverages category had the lowest OTIF rate

# Reports

<img width="1342" height="750" alt="Screenshot 2025-06-30 230725" src="https://github.com/user-attachments/assets/d932117f-e334-4849-8553-0e2ba0d164fe" />


<img width="1341" height="747" alt="Screenshot 2025-06-30 230628" src="https://github.com/user-attachments/assets/cd6a1eae-8c99-44e2-b462-3385c894c79e" />


<img width="1347" height="757" alt="Screenshot 2025-07-01 224236" src="https://github.com/user-attachments/assets/ed0c8155-ef4c-46a6-9d5d-152700f8db61" />


# Recommendations

1. Improve On-Time Delivery Processes
 • Conduct root cause analysis for late deliveries - transportation bottlenecks, warehouse delays, supplier issues etc.
 • Strengthen vendor SLAs, especially for high-volume products with low OTIF.
 • Use route optimization tools or partner with reliable logistics providers to reduce lead time


2. Customer Segmentation Strategy
 • Customers like Acclaimed, Lotus, and Coolblue are high-volume with low OTIF Rate therefore prioritize account-specific investigations.


View the interactive report here: https://tinyurl.com/3jza3wr8


