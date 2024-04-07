# PowerBI_Adventure_Works_Project
The Adventure Works Dashboard is designed to show the business insights for Sales and Revenue for an retail company. The interactive dashboard is built with Executive summary, Product and customer Details. Drill down option enables the user to drill down by individual product or customer from executive Summary.
Adventure Works Datasets are :       
1. AdventureWorks Calendar Lookup
2. AdventureWorks Customer Lookup
3. AdventureWorks Product Categories Lookup
4. AdventureWorks Product Lookup_2
5. AdventureWorks Product Subcategories Lookup
6. AdventureWorks Returns Data
7. AdventureWorks Sales Data 2020
8. AdventureWorks Sales Data 2021
9. AdventureWorks Sales Data 2022
10. AdventureWorks Territory Lookup

DAX Functions :      
Some of the DAX functions used the most include:       
1) ITERATOR FUNCTIONS (SUMX): These are formulas which evaluate an expression based on each row and then aggregate the results.              
2) CALCULATE(): acts as an overriding filter to give you a new filter context. Was incredibly useful for establishing Previous Months Orders, Revenue, Profit, Returns and Overall Average Price.                 
3) RELATED(): This function allows you to pull data from different tables as long as there is an established many to one relationship.                   
4) Date Functions(DateAdd, DATESINPERIOD): These date functions were very helpful when establishing a 90 Day Rolling Profit as well as the Previous Months Order, Profit, Revenue and Returns.                    
The measures which were created for this project were placed into their own specific Measure Table.

Data Visualization  :         
A total of 4 visualization pages were created for this report, these include:                 
1) Executive Dashboard:                
  * Company wide KPI’s, Trending Revenue, Orders as well as several lists of the top selling products.
  * This dashboard is meant to be a general overview of company performance for anyone to understand.
  * A slicer Panel located in the top left is also available to further filter down visuals based on the year and continent providing a more granular look at the most important KPI’s.           
2) Map:
  * This is an interactive visual of the company’s order distribution throughout the world broken down by continent.
  * Some key insights found from this were that while the United States makes up the majority of Adventure Work’s Orders (8,700), the Pacific shares a significant share of the total orders as well (6,060).
  * Additionally, no sales have taken place in Asia, Africa, or South America indicating a potential for new markets to break into.                         
3) Product Detail:         
  * This page provided an in-depth and interactive look at the relationship between the products of Adventure Works and their respective revenue, orders, profit, return percentage and returns.
  * For the selected product like “Road Tire Tube”. Here we can see this item is not meeting the any of the monthly targets for Orders, Revenue or Profit.
  * Additionally, we can see in the bottom area chart that the reason for this is likely due to a sharp increase in returns for this product which may indicate a potential defect with the product.             
4) Customer Detail:          
  * Multiple visuals of the relationship between customers and business metrics can be found on this page.
  * On this page, break the customers down by demographic including occupation and income as represented in the Donut Charts in the bottom left.
  * The Top 100 Customers Table has several interesting factors. In addition to providing an overview of the Top 100 customers, it also provides their total orders.             


 
