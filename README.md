# Sales Performance Analysis and Optimization Dashboard:


## **Project Objective**

This project focuses on analyzing sales trends, customer behavior, and operational efficiency to identify bottlenecks, uncover growth opportunities, and provide actionable insights. By leveraging advanced Excel techniques, the project automates reporting, supports data exploration, and creates an interactive dashboard for ongoing decision-making and resource optimization.

## **Tasks to Perform**

1. **Highlight Negative Profit Margins**  
   Identify and highlight the entire rows where the Profit Margin (%) is negative.

`For Task 1, I used Conditional Formatting. By navigating to "Highlight Cell Rules" and selecting "Less Than," I set the rule to highlight all negative profit margins (i.e., values less than zero).`

2. **Categorize Risk Levels**  
   Create a new column to categorize each transaction into a risk category:  
   - "Low Risk" if Profit Margin > 30%  
   - "Medium Risk" if Profit Margin is between 10% and 30%  
   - "High Risk" if Profit Margin < 10%
  
`For Task 2, I used the IFS formula to categorize each transaction into different risk categories. The formula is:
=IFS(V2>30,"Low Risk",V2>10,"Medium Risk",V2<10,"High Risk")`

3. **Split Date Information**  
   Split the Date column into separate Year, Month, and Day columns for further analysis.

`For Task 3, I used the YEAR function to extract the year: =YEAR(N2).
For the month, I used the TEXT function: =TEXT(N2,"MMMM").
For the day, I also used the TEXT function: =TEXT(N2,"DDDD").`

4. **Analyze Sales Performance by Region, Category, and Quarter**  
   Analyze Revenue, Profit, and Profit Margins by Region, Category, and Quarter to identify performance trends.

  ` For Task 4, I used a Pivot Table to analyze revenue, profit, and profit margins by Region, Category, and Quarter.`

5. **Identify Top Products and Regions**  
   Identify the Top 5 Products and Top 5 Regions based on sales and profitability.

`For Task 5, I again used a Pivot Table to identify the top 5 products and regions based on sales and profitability.`

6. **Customer Loyalty Segmentation**  
   Categorize customers into loyalty levels ("Bronze", "Silver", "Gold", "Platinum") based on their total sales.

7. **Count Gold Loyalty Customers by Region**  
   Count the number of customers in the "Gold" loyalty tier for each region.

8. **Rank High-Value Customers**  
   Rank customers based on their total sales to identify high-value customers.

9. **Create a Platinum Tier Slicer**  
   Create a slicer that displays only "Platinum" tier customers.

10. **Sales Performance by Year and Month**  
    Analyze sales performance by Year and Month to identify peak and slow periods.

    `For Tasks 6, 7, 8, 9 , and 10, I used Pivot Tables and Slicers to perform the analysis and create dynamic filters for customer loyalty segmentation.`

12. **Design Interactive Dashboard**  
    Design an interactive dashboard summarizing:  
    - Revenue, Profit, and Profit Margins  
    - Top-performing products and regions  
    - Customer loyalty segmentation  
    - Seasonal trends and discount impact  
    Ensure the dashboard includes dynamic slicers for filtering by region, category, and time period.

`For Task 11, I created an Interactive Dashboard that summarizes key metrics such as revenue, profit, and profit margins, top-performing products and regions, customer loyalty segmentation, and seasonal trends with dynamic slicers for filtering by region, category, and time period.`


