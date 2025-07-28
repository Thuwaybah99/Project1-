# Project1-

---sales.csv - This csv file provides insights into product sales, revenue, stock levels, pricing, and promotional effectiveness across different stores and dates.
product_id - The unique identifier of a product (String)
store_id - The unique identifier of a store (String)
date - Sales date (YYYY-MM-DD)
sales - Sales quantity (Number)
revenue - Daily total sales revenue (Number)
stock - End of day stock quantity (Number)
price - Product sales price (Number)
promo_type_1 - Type of promotion applied on channel 1 (String)
promo_bin_1 - Binned promotion rate for applied promo_type_1 (String)
promo_type_2 - Type of promotion applied on channel 2 (String)
promo_bin_2 - Binned promotion rate for applied promo_type_2
promo_discount_2 - Discount rate for applied promo type 2
promo_discount_type_2 - Type of discount applied

---product_hierarchy.csv - This csv file provides details about product dimensions such as length, depth, and width, along with cluster and hierarchy IDs.
product_id - The unique identifier of a product (String)
product_length - Length of product (Number)
product_depth - Depth of product (Number)
product_width - Width of the product (Number)
Cluster_id (String)
hierarchy1_id (String)
hierarchy2_id (String)
hierarchy3_id (String)
hierarchy4_id (String)
hierarchy5_id (String)

---store_cities.csv - This csv file contains information about store identifiers, types, sizes, and the corresponding city identifiers.
store_id - The unique identifier of a store (String)
storetype_id (String)
store_size (Number)
city_id (String)


---product_names.csv - This file links product identifiers with their corresponding names, providing a mapping for easier reference and analysis.
product_id (String)
product_name (String)

---store_names.csv - This file associates store identifiers with their respective names, allowing for better identification and analysis of stores.
store_id (String)
store_name (String)

---city_names.csv - This file maps city identifiers to their names, enabling geographical analysis and insights based on city-level data.
city_id (String)
city_names (String)
