# Shop-Data-Analysis
# Overview
This dataset is a comprehensive collection of data from an e-commerce platform, covering various aspects of the business including customer details, order transactions, payment records, product listings. It is ideal for performing detailed analysis of e-commerce activities such as sales trends, customer behavior, product performance, and payment methods.
# Objective
The primary objective of this dataset is to enable in-depth analysis of an e-commerce platform’s operations, customer behavior, and product performance. By providing data across various facets of the business — payments, orders, customer details, product information.

Sales Performance: Understand the trends in order frequency, total revenue, and customer purchasing patterns.
Customer Behavior: Analyze customer demographics, loyalty status, and geographical distribution to personalize marketing efforts.
Product Analysis: Assess product popularity, stock levels, pricing strategies, and performance within specific categories.
Payment Methods: Evaluate the efficiency and preference of different payment methods, and understand payment status trends.
# Payments Table
order_id: Unique identifier for the order associated with the payment.
payment_sequential: Sequential number indicating the order of payments for a particular transaction (e.g., for split payments or multiple installments).
payment_type: The type of payment method used (e.g., credit card, Upi, debit).
payment_installments: Number of installments in which the payment is divided, if applicable.
payment_value: The total amount paid in this particular payment transaction.
# Customer Tables
customer_id: Unique identifier for each customer within the system.
customer_unique_id: Unique external identifier for the customer, used across platforms or systems.
customer_zip_code_prefix: The first digits of the customer’s zip code, used for geolocation or regional analysis.
customer_city: The city in which the customer is located.
customer_state: The state or region where the customer resides.
 # Orders_items Table
order_id: Unique identifier for each order placed on the platform.
order_item_id: Unique identifier for each individual item within an order.
product_id: Unique identifier for the product being ordered.
seller_id: Unique identifier for the seller responsible for fulfilling the order.
shipping_limit_date: The last date by which the seller is expected to ship the product.
price: The price of the product for the specific order item.
freight_value: The shipping cost associated with the order item
# Order Table
order_id: Unique identifier for each order, linking to the main order.
customer_id: Unique identifier for the customer who placed the order.
order_status: Current status of the order (e.g., delivered, shipped, canceled).
order_purchase_timestamp: The date and time when the order was initially placed.
order_approved_at: The date and time when the order was approved for processing.
order_delivered_carrier_date: The date when the order was handed over to the carrier for delivery.
order_delivered_customer_date: The date when the order was actually delivered to the customer.
order_estimated_delivery_date: The estimated date by which the order is expected to be delivered to the customer.
# Product Table
product_id: Unique identifier for each product.
product_category: Category to which the product belongs (e.g., electronics, clothing).
product_name_length: The length of the product name in characters.
product_description_length: The length of the product description in characters.
product_photos_qty: Number of photos available for the product.
product_weight_g: Weight of the product in grams.
product_length_cm: Length of the product in centimeters.
product_height_cm: Height of the product in centimeters.
product_width_cm: Width of the product in centimeters.
# Seller Table
seller_id: Unique identifier for each seller on the platform.
seller_zip_code_prefix: The prefix of the seller's zip code, used for regional analysis.
seller_city: City where the seller's business is located.
seller_state: State or region where the seller's business is based.
