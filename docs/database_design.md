# RetailMart Database Design

## Business Domain

RetailMart is a retail company that sells products through multiple stores.

## Core Tables

1. customers
2. products
3. categories
4. suppliers
5. stores
6. employees
7. orders
8. order_items
9. payments
10. inventory
11. returns

## Relationships

customers --> orders

orders --> order_items

products --> order_items

products --> categories

products --> suppliers

stores --> inventory

stores --> employees

orders --> payments

orders --> returns