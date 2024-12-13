# D46-assignment-2
Power BI assignment 2 submission repo
# ASSIGNMENT 2

Detailed report on sales transaction of "Global Super Store's" sales data Using Power BI

# Steps Done

1. Dowloaded the data and loaded to Power BI
2. Transformed the data in to power query, all pre processing (cleaning) done.
3. Managed Relashionship from Fact table (Orders) to People and Return.
4. Calculated the percentage of shipping by ship mode using DAX formula,

Percentage of shipping = DEVIDE(SUM('Orders'[Shipping Cost]),CALCULATE(SUM('Orders'[Shipping cost]),ALL('Orders'[Ship Mode])))

5. Created tables for visualisations like Sales over city, market, region, states and shipping percentage Vs ship mode
6. Included charts for each tables.
7. Added slicers for City,Market, region ang Category.
8. Created an interactive Dashboard(Sales report) to show the stake holders.
9. Created a video that explaining the visualizations.
