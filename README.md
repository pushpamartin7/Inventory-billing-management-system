
# Inventory & Billing Management System

A Python and MySQL based console application to manage products, inventory, billing, and sales records.

## Project Overview

This project helps manage product inventory and billing operations through a menu-driven application. It allows users to manage products, generate bills, view sales history, and monitor low-stock products.

## Features

- View Products
- Add Product
- Update Product
- Delete Product
- Search Product
- Generate Bill
- View Sales History
- Low Stock Alert

## Technologies Used

- Python
- MySQL
- mysql-connector-python
- python-dotenv
- Git
- GitHub

## Project Structure

```text
Inventory_billing_system/
│
├── inventory_billing_system.py
├── README.md
├── .gitignore
└── .env
```

## Setup and Installation

1. Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

2. Open the project folder:

```bash
cd Inventory_billing_system
```

3. Install required packages:

```bash
pip install mysql-connector-python python-dotenv
```

4. Create a MySQL database named `inventory_db`.

5. Create a `.env` file in the project folder:

```env
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=mysql_password
DB_NAME=inventory_db
```

6. Run the application:

```bash
python inventory_billing_system.py
```

## Learning Outcomes

- Python functions and exception handling
- MySQL database connectivity
- CRUD operations (Create, Read, Update, Delete)
- SQL queries
- Environment variables using python-dotenv
- Git and GitHub version control

## Author

**Pushpa Martin**

GitHub: https://github.com/pushpamartin7
