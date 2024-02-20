
# Sales Analysis Dashboard

### Dashboard Link : https://app.powerbi.com/groups/me/reports/20753466-a647-4b7b-be7d-ea5a006a700c?ctid=c161f32a-a16f-41cd-8e7b-2054e98f9838&pbi_source=linkShare

## Problem Statement

This dashboard to know the sales that occur.Through different category, they get to know their improvement area, & thus they can improve their marketing by identifying these area. 

        
## Dax expression

Following DAX expression was written,
        
        TOTAL SALES = CALCULATE(SUM(Details[Amount]))
        
A card visual was used to represent count of Total Sales.

![Dax1](https://github.com/V3n0mm0us/Online-Sales/assets/81215981/f8d8ac98-87dc-4681-839d-ac679abeb920)


## Dax expression  Revenue of perdays
 Following DAX expression was written to find Revenue of perdays,
 
         Revenue = SUMX(Details, Details[Quantity]*Details[Profit])
 
 A HeatMaps visual was used to represent this values.
 
 Snap of days of customers who preferred Buy.
 
![Dax2](https://github.com/V3n0mm0us/Online-Sales/assets/81215981/9c307eae-6789-4405-959a-a7c48793b66e)

## Dax expression Min sales

 Following DAX expression was written to find Min Sales,
 
         Min Sales = MINX(VALUES(Orders[State]), CALCULATE(SUM(Details[Amount])))
    
 A Line visual was used to represent this total Revenue.
 
 
![Dax Min](https://github.com/V3n0mm0us/Online-Sales/assets/81215981/73b732c3-c8a8-4bd5-9735-337e1ec51dc5)
## Dax expression Max sales

Following DAX expression was written to find Max Sales,
 
         Max Sales = MAXX(VALUES(Orders[State]), CALCULATE(SUM(Details[Amount])))
    
 A Line visual was used to represent this total distance.

 ![Dax Max](https://github.com/V3n0mm0us/Online-Sales/assets/81215981/2255805e-aaf0-41f3-802f-5dd9b3d9cff4)
 
## The report was then published to Power BI Service.
 
 
![Publish To Power BI PNG](https://github.com/V3n0mm0us/Online-Sales/assets/81215981/bc59a56a-9211-4512-ad61-753980a3ada9)


# Snapshot of Dashboard (Power BI Service)

- Sales Dashboard

![Sales Dashboard](https://github.com/V3n0mm0us/Online-Sales/assets/81215981/8b101318-6550-4dcf-82cc-d74b47fece07)


- Transaction Analysis
![TrANSAKTION](https://github.com/V3n0mm0us/Online-Sales/assets/81215981/9cc9c928-0c5f-4b6f-b037-9fce42e15d3d)

- Location Analysis

![Location Analysis](https://github.com/V3n0mm0us/Online-Sales/assets/81215981/493a7343-d654-416e-96fc-b61d9a7b3298)

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Total Number of Customers = 129880

   Number of sales (All category) = 43800000

   Number of All Category = Electronic, Furniture, Clothing

   Total highest Quantity at january (61632)

   Minimum sales at July who had total sales at 12966


           thus, higher number of sales happends at January.
           
