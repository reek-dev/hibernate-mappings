# 📌 Why do we need Hibernate mappings?

 - Most of the times database tables are associated with each other
 - These associations can be of broadly three types
 	- one-to-one
 	- one-to-many / many-to-one
 	- many-to-many
 	
 - Hibernate mappings establish relationships between database tables
 


## Here are the demo tables
 
 ![](https://i.imgur.com/07bA7Jl.png)
 
 - in the `customer_details` table `c_id` is the primary key
 - in the `order_details` table `o_id` is the primary key
 - in the `order_details` table `c_id` is a foreign key that references the `c_id` in the `customer_details` table