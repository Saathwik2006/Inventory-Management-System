# Inventory Management System

A simple console-based Inventory Management System developed in C++.
The project allows users to add, remove, search, update, and view
products, with inventory data stored and loaded using CSV files.

## Features

- Add new products
- Remove products using product ID
- Search for a product using its ID
- Update existing product details
- Display all products
- Save inventory data to a CSV file
- Load inventory data from a CSV file
- Prevent duplicate product IDs
- Menu-driven console interface

## Technologies Used

- C++
- Object-Oriented Programming (OOP)
- STL `vector`
- File Handling
- CSV
- `stringstream`

## Concepts Demonstrated

### Object-Oriented Programming

The project uses two main classes:

- `Product` – stores information about an individual product.
- `Inventory` – manages the collection of products.

### Encapsulation

Product attributes such as ID, name, category, price, and quantity
are kept private and accessed through getter and setter methods.

### STL Vector

The inventory is stored using:

```cpp
vector<Product>
