
# Product Controller API - Spring Boot

This Spring Boot application provides a RESTful API for managing products. It includes endpoints for creating, retrieving, updating, and deleting product records.

## Endpoints

### POST /products
- Description: Create a new product.
- Request Body: `ProductRecordDto` (Product details)
- Response: `ProductModel` (Created product details)

### GET /products
- Description: Retrieve all products.
- Response: List of `ProductModel`

### GET /products/{id}
- Description: Retrieve a product by its ID.
- Path Variable: `id` (UUID of the product)
- Response: `ProductModel` or "Product not found."

### PUT /products/{id}
- Description: Update an existing product.
- Path Variable: `id` (UUID of the product)
- Request Body: `ProductRecordDto` (Updated product details)
- Response: Updated `ProductModel` or "Product not found."

### DELETE /products/{id}
- Description: Delete a product by its ID.
- Path Variable: `id` (UUID of the product)
- Response: "Product deleted successfully." or "Product not found."

## Technologies Used
- Spring Boot
- JPA (Java Persistence API)
- HATEOAS (Hypermedia as the Engine of Application State)

## Author
- **Matheus Costa**
  - LinkedIn: [Matheus Costa](https://www.linkedin.com/in/matheus-costa-b7a46425b/)
  - GitHub: [MatheusCosta616](https://github.com/MatheusCosta616)

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
