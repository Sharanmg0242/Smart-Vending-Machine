# Smart Vending Suite

## Overview

The **Smart Vending Suite** is a modern solution for managing vending machine operations. This project aims to streamline inventory management, provide timely restock notifications, and ensure secure user access. Designed for ease of use and efficiency, the Smart Vending Suite enhances the overall operation and management of vending machines.

## Features

- **Inventory Management**: Monitor the stock levels of products in vending machines.
- **Restock Notifications**: Receive alerts when product quantities fall below the specified threshold.
- **Secure Access**: User authentication and input validation to ensure data security.
- **User-Friendly Interface**: Intuitive and easy-to-navigate interface for employees.

## Technologies Used

- **Front-End**: HTML, CSS, JavaScript
- **Back-End**: PHP
- **Database**: MySQL

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/smart-vending-suite.git
   ```
2. **Navigate to the project directory**
   ```bash
   cd smart-vending-suite
   ```
3. **Set up the database**
   - Create a database named `project`.
   - Import the `project.sql` file to set up the necessary tables.

4. **Configure the database connection**
   - Update the database connection details in the PHP files (`servername`, `username`, `password`, and `dbname`).

## Usage

1. **Start the local server**
   - Use XAMPP, WAMP, or any other local server to host the project.

2. **Access the application**
   - Open a web browser and navigate to `http://localhost/smart-vending-suite`.

3. **Login**
   - Use the login page to access the admin or employee homepage.

4. **Manage Inventory**
   - Use the interface to view inventory, create restock notifications, and manage products.

## Project Structure

```
smart-vending-suite/
│
├── index.php             # Login page
├── employee_homepage.php # Employee dashboard
├── admin_homepage.php    # Admin dashboard
├── inventory.php         # Inventory status page
├── restock.php           # Restock settings page
├── confirmation pages    # Confirmation and error pages for various actions
│
├── assets/               # Static files (images, stylesheets)
│   ├── css/
│   ├── img/
│
├── db/                   # Database setup
│   ├── project.sql       # SQL file for database setup
│
├── functions/            # PHP functions
│   ├── inventory_functions.php
│   ├── restock_functions.php
│
└── README.md             # Project documentation
```

## Contributions

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
