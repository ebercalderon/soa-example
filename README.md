SOA REST API
=================

A simple mock demo of Service Oriented Architecture to display two tables - Products and Users. The Products table is fetched by the products API and the user tables can be fetched by directly querying the Users API or via the Products API.

Usage
-----
>npm install

#Running the mock APIs

In the root directory,
``` 
node Products/server_products_api.js 
node Users/server_users_api.js 
```
    

API Details
-----------
#Products -
Endpoint - http://127.0.0.1:8888/api
Response Format - JSON

#Operations
```
GET /products - Lists all products
GET /products/:id - Lists details of product with id

GET /users - Lists all users
GET /users/:id - Lists details of users with id
```
#Users -
Endpoint - http://127.0.0.1:8889/api
Response Format - JSON

#Operations

```
GET /users - Lists all users
GET /users/:id - Lists details of users with id
```
