# Spring Boot Product Management API

This is a simple CRUD API built with Spring Boot to manage products.

## Prerequisites

- Java Development Kit (JDK) installed
- Maven installed
- Postman or any API testing tool

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/DrakeDarkson/Spring-Boot-Web-Rest-Infnet-TP2
   
Run the application::

mvn spring-boot:run

The application will start on http://localhost:8080.

## API Endpoints

----------------------------------------
1. Create a Product

URL: http://localhost:8080/api/products

Method: POST

Body - json Example:
{
    "name": "Product 1",
    "price": 10.0
}

----------------------------------------
2. Get All Products

URL: http://localhost:8080/api/products

Method: GET

----------------------------------------
3. Get a Product by ID

URL: http://localhost:8080/api/products/{id}

Method: GET

----------------------------------------
4. Update a Product

URL: http://localhost:8080/api/products/{id}

Method: PUT

Body - json Example:
{
    "name": "Updated Product",
    "price": 15.0
}

----------------------------------------
5. Delete a Product

URL: http://localhost:8080/api/products/{id}

Method: DELETE

----------------------------------------
Testing with Postman

You can use Postman or any API testing tool to test the endpoints mentioned above.
