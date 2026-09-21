# Sakumaya SQL Analysis

This project is a SQL data analysis project using the Sakumaya banking dataset.

The analysis was conducted using MySQL and phpMyAdmin through XAMPP. The project focuses on analyzing customer information, accounts, cards, loans, and transactions.

## Tools

- MySQL
- phpMyAdmin
- XAMPP
- SQL

## Dataset

The dataset consists of five main tables:

- `customers` - customer information
- `accounts` - bank account information
- `cards` - card information
- `loans` - loan information
- `transactions` - transaction information

## Database Relationships

The database consists of the following relationships:

- `customers` → `accounts`
- `customers` → `cards`
- `customers` → `loans`
- `accounts` → `transactions`

The `customer_id` field is used to connect customers with their accounts, cards, and loans.

The `account_id` field is used to connect accounts with transactions.

## Analysis

The SQL analysis covers:

1. Customer demographics
2. Customer distribution by province
3. Account types and account balances
4. Card types and card status
5. Credit card utilization
6. Loan types and loan status
7. Loan outstanding analysis
8. Loan analysis by province
9. Transaction types
10. Transaction channels
11. Transaction status
12. Transaction analysis by account type
13. Transaction analysis by province
14. Customer transaction analysis
15. Customer 360 analysis

## Key Results

The analysis produced the following results:

- Total customers: 1,000
- Total accounts: 458
- Total cards: 162
- Total loans: 300
- Total transactions: 117
- Total account balance: Rp34,002,978,069
- Total loan outstanding: Rp6,376,366,212
- Total transaction value: Rp949,710,662
- Credit card utilization: 41.93%

## Repository Purpose

This project was created to practice SQL data analysis using a banking dataset. The analysis applies SQL concepts such as SELECT, WHERE, GROUP BY, ORDER BY, JOIN, aggregate functions, subqueries, and data aggregation.

## Author

Aisha Patricia Sekar Ayu
