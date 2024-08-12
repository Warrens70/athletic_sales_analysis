# athletic_sales_analysis
This assignment analyzed sales data to gain insights into which cities in the U.S. have sold the most athletic wear over two years. Next, I was able to determine which retailers had the greatest total sales for athletic wear, and which retailers sold the most women's athletic footwear. Finally, I was able to determine which day and week had the highest sales for women's athletic footwear.  I was able to:
    Determine which Region Sold the Most Products
        By Using either the groupby or pivot_table function I was able to create a multi-index DataFrame with the "region", "state", and "city" columns.
        Rename the aggregated column to reflect the aggregation of the data in the column.
        Sort the results in descending order to show the top five regions, including the state and city that have the greatest number of products sold. 
    Determine which Region had the Most Sales
        By Using either the groupby or pivot_table function to create a multi-index DataFrame with the "region", "state", and "city" columns.
        Rename the aggregated column to reflect the aggregation of the data in the column.
        Sort the results in descending order to show the top five regions, including the state and city that generated the most sales. 
    Determine which Region had the Most Sales
        By Using either the groupby or pivot_table function to create a multi-index DataFrame with the "region", "state", and "city" columns.
        Rename the aggregated column to reflect the aggregation of the data in the column.
        Sort the results in descending order to show the top five regions, including the state and city that generated the most sales. 
    Determine which Region had the Most Sales
        By Using either the groupby or pivot_table function to create a multi-index DataFrame with the "region", "state", and "city" columns.
        Rename the aggregated column to reflect the aggregation of the data in the column.
        Sort the results in descending order to show the top five regions, including the state and city that generated the most sales. 
    Determine the Day with the Most Women's Athletic Footwear Sales
        Created a pivot table with the "invoice_date" column as the index and the "total_sales" column as the values parameter.
        Rename the aggregated column to reflect the aggregation of the data in the column.
        Apply the resample function to the pivot table, place the data into daily bins, and get the total sales for each day.
        Sort the resampled DataFrame in descending order to show the top 10 days that generated the most women's athletic footwear sales.
    Determine the Week with the Most Women's Athletic Footwear Sales
        Apply resample to the pivot table above, place the data into weekly bins, and get the total sales for each week.
        Sort the resampled DataFrame in descending order to show the top 10 weeks that generated the most women's athletic footwear sales.