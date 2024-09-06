I took a dataset 4 csv files from online sources namely traffic.csv, brand.csv, reviews.csv, finance.csv.  
Finance CSV contains
product_id,
listing_price,
sale_price,
discount,
revenue

Brands CSV contains
product_id,
brand

Traffic CSV contains
product_id,
last_visited

Reviews CSV contains
product_id,
rating,
reviews
these columns.

I merged all these columns based on product key and created a new table called full_data which contains all the attributes.
The operations performed can be viewed in the notebook.
