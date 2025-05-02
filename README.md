# Designing a Second-Hand E-commerce Application

This project models the backend design of a second-hand e-commerce platform inspired by platforms like **Dolap.com**, with a focus on sustainability, trust, and transactional efficiency.

## Objective

To create a database-backed e-commerce system where users can list, purchase, and review second-hand items securely, while promoting environmentally conscious consumption.

## Team Members

- **Engin Kılınç**
- **Esra Şekerci**

## Project Components

- `SQL_Schema_Export.sql`: Database schema creation script
- `Term_Project_Queries.sql`: Collection of advanced SQL queries
- `is503_project.sql`: Final schema including triggers, procedures, and views
- `IS503_Term_Project_Report.pdf`: Full documentation of the system design and implementation

## Features

- **User & Product Management**: Register, list items, and manage personal profiles
- **Transaction System**: Track pending/completed transactions with built-in consistency
- **Review System**: Only allows reviews from verified buyers who completed a transaction
- **Seller Verification**: Based on number of completed sales and review ratings
- **Dashboard Analytics View**: Provides metrics like total sales, top users, and transaction status counts
- **Triggers**:
  - Auto-update seller ratings after review
  - Restrict reviews to actual buyers
  - Track last login
  - Auto-verify sellers after sales milestones
