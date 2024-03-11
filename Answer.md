1. Explain the relationship between the "Product" and "Product_Category" entities from the above diagram.
Ans: One-to-many relationship where one product belongs to one category, but one category can have multiple products
2. How could you ensure that each product in the "Product" table has a valid category assigned to it?
Ans: You can ensure that each product in the "Product" table has a valid category assigned to it by:
1. Adding a foreign key constraint on the "category_id" column in the "Product" table, referencing 
the "id" column of the "Product_category" table.
2. This constraint ensures that any value entered into the "category_id" column must
exist in the "id" column of the "Product_category" table, maintaining referential integrity.
