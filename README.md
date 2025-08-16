# shopAPI

## Task 
Make an API that will allow clients to:  
* Get a list of unique products - each product is a single copy, it has a description, name and price.  
* Add product to cart  
* Remove product from cart  
* Place an order. To do this, the user only needs to indicate their email.  

All endpoints for clients should work without authentication.  
There are also two additional roles - manager and admin. 
A manager can change the price and description of products. 
An administrator can do everything a manager can, as well as add products to the platform. 
Authentication and authorization are mandatory for administrators and managers. 
