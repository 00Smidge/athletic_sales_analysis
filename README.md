# athletic_sales_analysis

analyze sales data to gain insights into which cities in the U.S. have sold the most athletic wear

# Understanding the Workflow

The data from the two csv files were "outer" merged into combined_df. All nas were dropped and datetime was converted in the same
cell. To prevent over manipulation of the original combined_df I created copies whenever there was a need for grouping or pivoting
the data into new collections.

## DataFrame Copies

    - group_total
    - pivot_totals
     - group_sales
     - pivot_sales
     - group_retailers
     - pivot_retailers
     - womens_wear_df ( This copy is exclusively for womens athletic foot wear )
      - group_shoes_sold
      - pivot_womens_shoes
      - highest_sales_day
