# Django E-Commerce Web Application

## Overview

This project is a full-stack E-Commerce web application built using Django. It provides a complete online shopping workflow including product management, cart functionality, order processing, and secure payment integration using Stripe and PayPal.

The system is designed following Django’s MVT (Model-View-Template) architecture and demonstrates real-world implementation of authentication, database relationships, payment gateway integration, and order management.

---

## Features

### User Features
- User registration and login authentication
- Browse products by category
- View product details
- Add products to cart
- Update or remove cart items
- Secure checkout process
- Online payments via Stripe and PayPal
- Order confirmation and status tracking

### Admin Features
- Add, update, and delete products
- Manage product categories
- Track customer orders
- Update order statuses
- Monitor payment records

---

## Technology Stack

- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, JavaScript
- **Database:** MySQL / PostgreSQL / SQLite
- **Payment Gateways:** Stripe API, PayPal API
- **Authentication:** Django built-in authentication system
- **Version Control:** Git & GitHub

---

## Database Design

The application uses relational database models including:

- User
- Product
- Category
- Cart
- Order
- Order Items
- Payment

Relationships are implemented using Django ORM with ForeignKey and OneToMany associations to ensure data integrity.

---

## Payment Integration

### Stripe Integration
- Secure payment processing using Stripe Checkout.
- Payment confirmation handled via success callback.
- Order status updated after successful transaction.

### PayPal Integration
- PayPal redirection for secure transactions.
- Payment verification before confirming order.
- Automated status update after payment confirmation.

---

## Security Features

- CSRF protection enabled
- Secure session-based authentication
- Input validation and form validation
- Protected routes for authorized users only
- Payment status verification before order confirmation

---


