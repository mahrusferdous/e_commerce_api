# Ecommerce API Project

This is a simple API project for an Ecommerce website. The project is built using Django Rest Framework.

## Features
1. Customer Management
    - Create customer
    - Read Customer
    - Update Customer
    - Delete Customer
2. Product Catalog
    - Create Product
    - Read Product
    - Update Product
    - Delete Product
3. Order Processing
    - Place order
    - Retrieve order
    - Track order
    - Cancel order
4. Account 
    - Create account
    - Read account
    - Update account
    - Delete account

## Installation
1. Clone the repository
2. Virtual Environment should have all the dependencies installed
3. Run the server - flask run

## API Endpoints
1. Customer Management
    - Create customer
        - POST /customers/
    - Read Customer
        - GET /customers/
    - Update Customer
        - PUT /customers/{id}/
    - Delete Customer
        - DELETE /customers/{id}/
2. Product Catalog
    - Create Product
        - POST /products/
    - Read Product
        - GET /products/
    - Update Product
        - PUT /products/{id}/
    - Delete Product
        - DELETE /products/{id}/
3. Order Processing
    - Place order
        - POST /orders/
    - Retrieve order
        - GET /orders/
    - Track order
        - GET /orders/{id}/
    - Cancel order
        - DELETE /orders/{id}/
4. Account
    - Create account
        - POST /accounts/
    - Read account
        - GET /accounts/
    - Update account
        - PUT /accounts/{id}/
    - Delete account
        - DELETE /accounts/{id}/
