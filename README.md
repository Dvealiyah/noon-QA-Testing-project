# Noon QA Testing Project

Manual QA testing project for Noon e-commerce platform

This project demonstrates manual testing on the Noon e-commerce platform.

## Test Coverage:
- Login (valid & invalid)
- Product search
- Add to cart
- Checkout process

## Tools Used:
- Manual Testing
- Excel (Test Cases)

## Summary:
Designed and executed multiple test cases to validate system behavior and ensure quality.

## API Testing

### GET /products

- Endpoint: https://dummyjson.com/products
- Method: GET
- Status Code: 200 OK
- Description: Retrieve list of products

### POST /products/add

- Endpoint: https://dummyjson.com/products/add
- Method: POST
- Status Code: 201 Created
- Description: Add new product

### Request Body:
{
  "title": "Test Product",
  "price": 100
}

### Response:
 {
  "id": 195
}






