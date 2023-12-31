# Data Analysis of AdventureWorks
a global manufacturing company that produces cycling equipment and accessories

## Introduction
Bicycle apparels and accessories market size was valued at USD 6.8 billion in 2022.Increased prevalence of health related disorders such as high blood pressure,diabetes and obesity among young and middle age people,as well as increased consumer awareness of health and fitness in post COVID period are the key market drivers enhancing the market growth.

For this AdventureWorks’s management needs a way to track KPIS(sales ,revenue,profits etc) , compare regional performance, analyze product-level trends, and identify high-value customers.

## Data Gathering and Data Modeling
As AdventureWorks business spread across Europe,North America and the Pacific continent,gathering various kind of data like Customer details,products details ,Sales data(2020-2022),territories wise data and product return data in various files formats such as csv,excel,json etc.

After gathering all required data then perform some ETL jobs on all this data and create a data model based on fact(Sales and return) and dimension(calendar,customer,product,category,subcategory etc ) tables.

![sales_adventureWorks_dataModel](https://github.com/niladri-dey/AdventureWorks---D2C-bicycle-manufacturing-company-Data-Analytics/assets/63118910/1a9eb57d-9b07-427d-a743-465ac942544f)

![return_datamodel_advenureworks](https://github.com/niladri-dey/AdventureWorks---D2C-bicycle-manufacturing-company-Data-Analytics/assets/63118910/23344583-e51d-4cc2-b96c-33f78c9dbaa0)


A star schema is the simplest and most common type of data model, characterized by a single fact table surrounded by related dimension tables

A snowflake schema is an extension of a star and includes relationships between dimension tables and related sub-dimension tables


![star_schema](https://github.com/niladri-dey/AdventureWorks---D2C-bicycle-manufacturing-company-Data-Analytics/assets/63118910/6984e8b8-cb4f-46b9-9d3f-3d1c4b2d9e2e)
![snowflake_schema](https://github.com/niladri-dey/AdventureWorks---D2C-bicycle-manufacturing-company-Data-Analytics/assets/63118910/69551924-3cdf-470b-a2f3-b5f994f30a98)

## Dashboard Sample View:
![dashboard_main_page](https://github.com/niladri-dey/AdventureWorks---D2C-bicycle-manufacturing-company-Data-Analytics/assets/63118910/8cbeda21-511a-435a-9da8-175be8cbf7ef)
![product_analysis_dashboard](https://github.com/niladri-dey/AdventureWorks---D2C-bicycle-manufacturing-company-Data-Analytics/assets/63118910/14e67ea6-9f03-420a-a3e3-d8a0da4b50ae)

![customer_dashboard](https://github.com/niladri-dey/AdventureWorks---D2C-bicycle-manufacturing-company-Data-Analytics/assets/63118910/8858ddf8-bc24-4eb7-b847-a5fbff456560)

## Details Project Report
https://www.notion.so/Data-Analysis-of-a-global-manufacturing-company-that-produces-cycling-equipment-and-accessories-51affd2126eb419ebf34bf082bf00bdf?pvs=4






