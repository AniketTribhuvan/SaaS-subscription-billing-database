# Multi User Billing System

A simple PostgreSQL database project for managing users, subscription plans, subscriptions, and payments.

This project was created to practice SQL and database design by building a basic billing system using PostgreSQL. It focuses on creating a well-structured relational database with proper constraints and relationships.

## Features

- User management
- Subscription tier management
- User subscriptions
- Payment tracking
- UUID primary keys
- Foreign key relationships
- CHECK constraints for data validation
- JSONB support for storing tier features

## Database Schema

The database consists of the following tables:

- **users** – Stores user information.
- **tiers** – Stores available subscription plans.
- **subscriptions** – Links users to subscription plans.
- **payments** – Stores payment details for subscriptions.

## Technologies Used

- PostgreSQL
- SQL

## What I Learned

While building this project, I learned about:

- Database normalization
- Primary and foreign keys
- One-to-many relationships
- UUIDs
- Constraints
- JSONB data type
- Relational database design

## Project Structure

```
.
├── schema.sql
└── README.md
```

## How to Run

1. Install PostgreSQL.
2. Open pgAdmin or psql.
3. Run the `schema.sql` file.
4. The database and tables will be created automatically.

## Future Improvements

Some features I would like to add in the future:

- Organizations/Companies
- User roles and permissions
- Invoice generation
- Discounts and coupons
- Payment methods
- Audit logs
- REST API integration

## Purpose

This project was built as a practice project to improve my SQL and database design skills by creating a simple billing system. It serves as a foundation for learning more advanced database concepts.