# Adventure-Works
In this project, I used Power BI to visualize the sales &amp; returns data of a hypothetical bike shop, Adventure Works.

## Data
This data comes from Maven Analytics and is hypothetical, as mentioned above. It was stored in 3 separate tables, with 56,046 rows of sales data, 1,809 rows of returns data, and 293 rows of product data.

## PowerBI techniques Learnt
+ What are all the questions should be asked before staring the project
+ Creating calculated columns
+ creating measure using DAX language
+ Data modeling
+ Using Bookmarks to switch between two visuals
+ Page navigation with buttons
+ Using divide function to prevent zero division errors
+ creating date table using m language
+ Using KPI indicators
+ Conditional formatting the values in visuals using icons or background color
+ Data validation techniques
+ Publishing reports to PowerBi services
+ PowerBi App creation
  
## Data Model view
- Data modeling plays a vital role and is considered as the basement of the report. All the visuals will be built upon the data model.
- In this project, we have followed the Snowfall data modeling method.

<img src="https://github.com/Sandeepm959/Adventure-Works/blob/69a5b5c77395443b7d046e3bafd5265114acec8b/Dataset/Data_Model.PNG">

## Executive Dashboard: A high level summary of the entire data set.

<img src="https://github.com/Sandeepm959/Adventure-Works/blob/2e483b08dc78b82b21e0d1f2aae1cb61323bd0ba/Dataset/Executive.jpg">

### Highlights on this dashboard:
+ After inserting the table showing the top 10 products and the associated orders, revenue and return rate, I was able to incorporate some drill through functionality. This means that if you click on a specific product you can go to a separate dashboard (The Product Detail Dashboard) and view more details on just this specific product.
+ While the cards at the bottom left showing monthly revenue, orders and returns are useful on their own, the addition of conditional formatting based off of whether or not they have reached their monthly targets is a huge value add. Further, these targets are dynamic as they are based on the previous months’ revenue/orders/returns total.
+ The filter button at the top left brings up a Slicer Panel which allow users to filter the entire page by continent and year, which allows for a whole new angle of analysis.
<img src="https://github.com/Sandeepm959/Adventure-Works/blob/2e483b08dc78b82b21e0d1f2aae1cb61323bd0ba/Dataset/filter.PNG">

##  Map: A nice simple visualisation to learn about using geospatial data & tooltips.

<img src="https://github.com/Sandeepm959/Adventure-Works/blob/2e483b08dc78b82b21e0d1f2aae1cb61323bd0ba/Dataset/Map.jpg" >

## Product Details: All the product specific KPIs.

<img src="https://github.com/Sandeepm959/Adventure-Works/blob/2e483b08dc78b82b21e0d1f2aae1cb61323bd0ba/Dataset/Product.jpg">

### Highlights on this dashboard:
+ As mentioned above, this page is a drill through from the executive dashboard, so whichever product you look at on that dashboard will be shown in more detail here.
+ A very useful technique shown here is the gauges along the top of the dashboard which are a great way to show KPI performance against targets.
  

##  Customer Details: All the customer specific KPIs.
<img src="https://github.com/Sandeepm959/Adventure-Works/blob/2e483b08dc78b82b21e0d1f2aae1cb61323bd0ba/Dataset/Customer.jpg">

This dashboard is pretty similar to the Product Details dashboard above, but it contains details of specific customers rather than products.

+ The line chart here has chart-specific filters on it, which means that the chart currently shows the total number of customers over time but can be changed to rather show the revenue per customer over time.

##  Decomposition Tree: This allow users to analyze data themselves, across categories and subcategories.

<img src="https://github.com/Sandeepm959/Adventure-Works/blob/2e483b08dc78b82b21e0d1f2aae1cb61323bd0ba/Dataset/Decomposition%20tree.jpg">

+ As can be seen above from the above example, this can be very helpful when analyzing things like a breakdown of total revenue, to see which products drive revenue and which category or subcategory they come from.

you can find the full report file pdf here [Report File](https://github.com/Sandeepm959/Adventure-Works/blob/69a5b5c77395443b7d046e3bafd5265114acec8b/Report%20File/AdventureWorks%20Report.pdf)

Power BI report file here [BI Report](https://github.com/Sandeepm959/Adventure-Works/blob/2e483b08dc78b82b21e0d1f2aae1cb61323bd0ba/Report%20File/AdventureWorks%20Report.pbix)


