# API Documentation for MetaCortex.Panther (Ocelot Gateway)

This document provides an overview of the API routes configured in the Ocelot gateway.

## Base URL
All routes are prefixed with the following base URL:

```
http://localhost:5000
```

## Routes

### Products

#### `GET /products`
- **Description**: Retrieves a list of products.
- **Downstream Service**: `http://metacortex-products/api/products`

#### `POST /products`
- **Description**: Creates a new product.
- **Downstream Service**: `http://metacortex-products/api/products`

#### `GET /products/{id}`
- **Description**: Retrieves a product by ID.
- **Downstream Service**: `http://metacortex-products/api/products/{id}`

#### `UPDATE /products/{id}`
- **Description**: Updates a product by ID.
- **Downstream Service**: `http://metacortex-products/api/products/{id}`

#### `DELETE /products/{id}`
- **Description**: Deletes a product by ID.
- **Downstream Service**: `http://metacortex-products/api/products/{id}`

### Orders

#### `GET /orders`
- **Description**: Retrieves a list of orders.
- **Downstream Service**: `http://metacortex-orders/api/orders`

#### `POST /orders`
- **Description**: Creates a new order.
- **Downstream Service**: `http://metacortex-orders/api/orders`

#### `GET /orders/{id}`
- **Description**: Retrieves an order by ID.
- **Downstream Service**: `http://metacortex-orders/api/orders/{id}`

#### `UPDATE /orders/{id}`
- **Description**: Updates an order by ID.
- **Downstream Service**: `http://metacortex-orders/api/orders/{id}`

#### `DELETE /orders/{id}`
- **Description**: Deletes an order by ID.
- **Downstream Service**: `http://metacortex-orders/api/orders/{id}`

### Customers

#### `GET /customers`
- **Description**: Retrieves a list of customers.
- **Downstream Service**: `http://metacortex-customers/api/customers`

#### `POST /customers`
- **Description**: Creates a new customer.
- **Downstream Service**: `http://metacortex-customers/api/customers`

#### `GET /customers/{id}`
- **Description**: Retrieves a customer by ID.
- **Downstream Service**: `http://metacortex-customers/api/customers/{id}`

#### `UPDATE /customers/{id}`
- **Description**: Updates a customer by ID.
- **Downstream Service**: `http://metacortex-customers/api/customers/{id}`

#### `DELETE /customers/{id}`
- **Description**: Deletes a customer by ID.
- **Downstream Service**: `http://metacortex-customers/api/customers/{id}`

#### `GET /customers/email/{email}`
- **Description**: Retrieves a customer by email.
- **Downstream Service**: `http://metacortex-customers/api/customers/email/{email}`

### Payments

#### `GET /payments`
- **Description**: Retrieves a list of payments.
- **Downstream Service**: `http://metacortex-payments/api/payments`

#### `POST /payments`
- **Description**: Creates a new payment.
- **Downstream Service**: `http://metacortex-payments/api/payments`

#### `GET /payments/{id}`
- **Description**: Retrieves a payment by ID.
- **Downstream Service**: `http://metacortex-payments/api/payments/{id}`

#### `UPDATE /payments/{id}`
- **Description**: Updates a payment by ID.
- **Downstream Service**: `http://metacortex-payments/api/payments/{id}`

#### `DELETE /payments/{id}`
- **Description**: Deletes a payment by ID.
- **Downstream Service**: `http://metacortex-payments/api/payments/{id}`

