# Consumer Goods Ad - Hoc Insights
**Domain** :  Consumer Goods | **Function** : Executive Management </br>
> You can find this project as *[Resume Project Challenge - 4](https://codebasics.io/challenge/codebasics-resume-project-challenge)* at **[Codebasics](https://codebasics.io/)** offical website

## About Company
  Atliq Hardwares (imaginary company) is one of the leading computer hardware producers in India and well expanded in other countries too.
  
## Problem Statement
  The management of AtliQ Hardware noticed that they do not get enough insights to make quick and smart data-informed decisions. They want to expand their data analytics team by adding several junior data analysts. Tony Sharma, their data analytics director wanted to hire someone who is good at both tech and soft skills. Hence, he decided to conduct a SQL challenge which will help him understand both the skills.

## Task
  Imagine yourself as the applicant for this role and perform the following task
  1. Check Ad Hoc Requests for which the business needs insights.
  2. Run SQL query to answer these requests. 
  3. The target audience of this dashboard is top-level management - hence create a presentation to show the insights.
    
## Dataset
  * Database : __'gdb023'__ (atliq_hardware_db)
  * Tables:
      1. **dim_customer**: contains customer-related data
      2. **dim_product**: contains product-related data
      3. **fact_gross_price**: contains gross price information for each product
      4. **fact_manufacturing_cost**: contains the cost incurred in the production of each product
      5. **fact_pre_invoice_deductions**: contains pre-invoice deductions information for each product
      6. **fact_sales_monthly**: contains monthly sales data for each product.

## ERD (Entity relationship diagram)
  Various dimension and fact tables are connected with the help of primary and foreign keys.
  ![Schema2](https://github.com/user-attachments/assets/53782f7b-f6d8-4df2-806c-408a9246c000)

## AD HOC Requests
  1.  Provide the list of markets in which customer  **"Atliq  Exclusive"**  operates its business in the  **APAC**  region. 
  2.  What is the percentage of __unique product__ increase in 2021 vs. 2020? The final output contains these fields:
        - unique_products_2020 
        - unique_products_2021 
        - percentage_chg 
  3.  Provide a report with all the __unique product counts__ for each  segment  and sort them in descending order of product counts. The final output contains fields:
        - segment 
        - product_count 
4.  Follow-up: Which segment had the most increase in __unique products__ in 2021 vs 2020? The final output contains these fields:
     - segment 
     - product_count_2020 
     - product_count_2021 
     - difference 
5.  Get the products that have the highest and lowest ___manufacturing costs__. The final output should contain these fields:
     - product_code 
     - product 
     - manufacturing_cost 
6.  Generate a report which contains the __top 5 customers__ who received an average high  **pre_invoice_discount_pct**  for the  __fiscal  year 2021__  and in the Indian  market. The final output contains these fields:
     - customer_code 
     - customer 
     - average_discount_percentage 
7.  Get the complete report of the __Gross sales amount__ for the customer  -**Atliq Exclusive**_  for each month  .  This analysis helps to  get an idea of low and high-performing months and take strategic decisions. 
    The final report contains these columns: 
     - Month 
     - Year 
     - Gross sales Amount 
8.  In which quarter of __2020__, got the maximum **total_sold_quantity**? The final output contains these fields sorted by the __total_sold_quantity__, 
     - Quarter 
     - total_sold_quantity 
9.  Which channel helped to bring more __gross sales__ in the __fiscal year 2021__ and the percentage of contribution?  The final output  contains these fields:
     - channel 
     - gross_sales_mln 
     - percentage 
10.  Get the __Top 3 products__ in each division that have a high __total_sold_quantity__ in the __fiscal_year 2021__? The final output contains these fields:
     - division 
     - product_code
     - product 
     - total_sold_quantity 
     - rank_order

## Presentaion
  * __(Video Presentation)[]__

## Insights
  * (PPT)[https://github.com/shellynagar27/Consumer-Goods-Ad-Hoc-Insights---Resume-Project-Challenge/blob/main/Consumer%20Goods%20-2%20PPT.pdf]

## Tools Used:
  1. MySQL
  2. Canva
  3. [Flaticon](https://www.flaticon.com/)
  4. [Freepik](https://www.freepik.com/)
  5. [ShutterStock](https://www.shutterstock.com/)
  6. [Adobe Stock](https://stock.adobe.com/)
  7. [Icons8](https://icons8.com/)
