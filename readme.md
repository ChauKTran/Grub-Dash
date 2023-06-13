GrubDash Project

GrubDash is a web application that aims to provide a platform for users to order and manage dishes from various restaurants. It consists of a backend API that handles dish and order management, allowing frontend developers to build the user interface for the application.

Features

Dishes: The API supports the creation, reading, updating, and listing of dishes. Each dish has properties such as name, description, price, and image URL. Dishes cannot be deleted once created.
Orders: The API provides functionality to create, read, update, delete, and list orders. Each order contains information about the customer, the list of dishes ordered, and the status of the order. The status can be updated to reflect the progress of the order.
RESTful Design: The API follows RESTful design principles, ensuring that the routes and endpoints are structured in a logical and intuitive manner.

API Routes

Dishes: The following routes are available for dish management:
GET /dishes: Retrieve a list of all dishes.
GET /dishes/:dishId: Retrieve a specific dish by its ID.
POST /dishes: Create a new dish.
PUT /dishes/:dishId: Update an existing dish.
Orders: The following routes are available for order management:
GET /orders: Retrieve a list of all orders.
GET /orders/:orderId: Retrieve a specific order by its ID.
POST /orders: Create a new order.
PUT /orders/:orderId: Update an existing order.
DELETE /orders/:orderId: Delete an order.
