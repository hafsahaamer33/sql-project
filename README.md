# sql-project
Bilkent SQL Project 2021

This project required our team to implement a database system as indicated below. This rubric was handed out at the beginning of the project by our SQL course coordinators.

Online Market: You are going to implement a database system for an online market that 
delivers products to houses. Users of this system are going to be stockers, deliverers, and 
customers. For each user, you should store a unique SSN, name, and surname. For customers, 
you should also store their address and phone number. For each product, you should store a 
unique product number, product name, description, unit price, and stock amount. For each 
brand, you should store a unique brand name and a description. Each product should belong to 
exactly one brand and one brand can have multiple products. Customers can create carts for 
shopping. Each cart should belong to exactly one customer, and a customer can have zero or 
more carts. For each cart, you should store a unique cart id, date of creation, delivery status 
(“new”, “paid”, “on delivery”, “completed”), and total price. In each cart, there could be many 
products. You should also store the amount of product that is in the cart. The same product can 
be in multiple carts. Carts with paid status are assigned to deliverers for delivery. Each 
deliverer can be assigned to multiple carts but a cart can be assigned to only one deliverer. For 
each truck, you should store a unique plate number and capacity in kilograms. Sometimes, 
deliverers can use trucks for carrying a cart. In this case, you should keep the information 
about which truck is assigned to the delivery of which cart by which deliverer. Stockers can be 
assigned to one-time jobs in different warehouses. These jobs are identified by the 
combination of the name of the warehouse, date of the assignment, and the SSN of the 
assigned stocker. For each one-time job, you should also store a description.
o Log in as a customer. List all products. Filter products by name. Add multiple 
products to the current cart with different amounts. Remove products from the cart. 
Show the total price of the cart. Order the current cart by setting its status to paid.
o Log in as a deliverer. List all paid carts. Choose one cart to assign to this deliverer. 
Show the carts assigned to this deliverer, assign a truck for the delivery of the chosen 
cart for this deliverer. Choose a cart, show its delivery address, mark it as completed.
o Log in as a stocker. List all brands. Choose a brand and list all products of that brand. 
Choose a product, update its stock amount and price. Create a new product for the 
chosen brand. List all one-time jobs of this stocker
