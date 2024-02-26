# Target_DA_SQL
Data Analysis with SQL

# Context:

Target is a globally renowned brand and a prominent retailer in the United States. Target makes itself a preferred shopping destination by offering outstanding value, inspiration, innovation and an exceptional guest experience that no other retailer can deliver.
This particular business case focuses on the operations of Target in Brazil and provides insightful information about 100,000 orders placed between 2016 and 2018. The dataset offers a comprehensive view of various dimensions including the order status, price, payment and freight performance, customer location, product attributes, and customer reviews.

By analyzing this extensive dataset, it becomes possible to gain valuable insights into Target's operations in Brazil. The information can shed light on various aspects of the business, such as order processing, pricing strategies, payment and shipping efficiency, customer demographics, product characteristics, and customer satisfaction levels.

___________________________________________________________________________________________________________
Below are the 8 tables which are used as part of the analysis.

1. customers
2. sellers
3. order_items
4. geolocation
5. payments
6. reviews
7. orders
8. products
___________________________________________________________________________________________________________

The column description for these tables is given below.

# 1. The customers table contain following features:
1. customer_id - ID of the consumer who made the purchase
2. customer_unique_id - Unique ID of the consumer
3. customer_zip_code_prefix - Zip Code of consumer’s location
4. customer_city - Name of the City from where order is made
5. customer_state - State Code from where order is made (Eg. são paulo - SP)

# 2. The sellers table contains following features:
1. seller_id - Unique ID of the seller registered
2. seller_zip_code_prefix - Zip Code of the seller’s location
3. seller_city - Name of the City of the seller
4. seller_state - State Code (Eg. são paulo - SP)

# 3. The order_items table contain following features:
1. order_id - A Unique ID of order made by the consumers
2. order_item_id - A Unique ID given to each item ordered in the order
3. product_id - A Unique ID given to each product available on the site
4. seller_id - Unique ID of the seller registered in Target
5. shipping_limit_date - The date before which the ordered product must be shipped
6. price - Actual price of the products ordered
7. freight_value - Price rate at which a product is delivered from one point to another

# 4. The geolocations table contain following features:
1. geolocation_zip_code_prefix - First 5 digits of Zip Code
2. geolocation_lat - Latitude
3. geolocation_lng - Longitude
4. geolocation_city - City
5. geolocation_state - State

# 5. The payments table contain following features:
1. order_id - A Unique ID of order made by the consumers
2. payment_sequential - Sequences of the payments made in case of EMI
3. payment_type - Mode of payment used (Eg. Credit Card)
4. payment_installments - Number of installments in case of EMI purchase
5. payment_value - Total amount paid for the purchase order

# 6. The orders table contain following features:
1. order_id - A Unique ID of order made by the consumers
2. customer_id - ID of the consumer who made the purchase
3. order_status - Status of the order made i.e. delivered, shipped, etc.
4. order_purchase_timestamp - Timestamp of the purchase
5. order_delivered_carrier_date - Delivery date at which carrier made the delivery
6. order_delivered_customer_date - Date at which customer got the product
7. order_estimated_delivery_date - Estimated delivery date of the products

# 7. The reviews table contain following features:
1. review_id - ID of the review given on the product ordered by the order id
2. order_id - A Unique ID of order made by the consumers
3. review_score - Review score given by the customer for each order on a scale of 1-5
4. review_comment_title - Title of the review
5. review_comment_message - Review comments posted by the consumer for each order
6. review_creation_date - Timestamp of the review when it is created
7. review_answer_timestamp - Timestamp of the review answered

# 8. The products table contain following features:
1. product_id - A Unique identifier for the proposed project.
2. product_category_name - Name of the product category
3. product_name_length - Length of the string which specifies the name given to the products ordered
4. product_description_length - Length of the description written for each product ordered on the site
5. product_photos_qty - Number of photos of each product ordered available on the shopping portal
6. product_weight_g - Weight of the products ordered in grams
7. product_length_cm - Length of the products ordered in centimeters
8. product_height_cm - Height of the products ordered in centimeters
9. product_width_cm - Width of the product ordered in centimeters

___________________________________________________________________________________________________________

# Dataset schema:

![image](https://github.com/shubham-11821/Target_DA_SQL/assets/34592956/42e35287-8031-431b-b0d6-7ac0ccccd8dc)

