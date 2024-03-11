### Question 1
The "Product" and "Product_Category" entities are related through a foreign key relationship. Typically, the "Product" table would contain a foreign key column that references the primary key column 
in the "Product_Category" table. This relationship establishes that each product belongs to a specific category defined in the "Product_Category" table.

### Question 2
To ensure that each product in the "Product" table has a valid category assigned to it, you can enforce referential integrity using foreign key constraints in the database schema. 
By setting up a foreign key constraint between the "Product" table's category column and the primary key column of the "Product_Category" table, the database will prevent the insertion of rows
in the "Product" table that reference non-existent categories in the "Product_Category" table.
