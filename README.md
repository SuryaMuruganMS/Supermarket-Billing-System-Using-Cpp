# Supermarket Billing System

## Introduction

The Supermarket Billing System is a C++ project designed to manage and streamline the billing process in a supermarket. This system allows for the addition, modification, and deletion of products, as well as generating bills for customers. It provides a simple command-line interface for managing these tasks efficiently.

## Features

- Add new products to the inventory
- Modify existing product details
- Delete products from the inventory
- Generate bills for customers
- Display product details

## Prerequisites

- C++ compiler (GCC, Clang, MSVC, etc.)

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/supermarket-billing-system.git
## Navigate to the project directory
  ```bash
  cd supermarket-billing-system
##Compile the code
  ```bash
  g++ -o supermarket supermarket-cpp.cpp
##Run the compiled program
  ```bash
  ./supermarket
Follow the on-screen instructions to use the system

To add a new product, select the option to add and enter the required product details.
To modify a product, select the modify option and provide the necessary information to update the product details.
To delete a product, choose the delete option and enter the product ID to remove it from the inventory.
To generate a bill, select the billing option and enter the product IDs and quantities. The system will calculate and display the total bill.
To display all products, select the display option to view the product details in the inventory.

##The main code for the Supermarket Billing System can be found in the supermarket-cpp.cpp file.

##Class Shopping
#Methods
-menu(): Displays the main menu and handles user input for different functionalities.
-administrator(): Handles administrative tasks such as adding, modifying, and deleting products.
-buyer(): Handles buyer tasks such as viewing products and generating receipts.
-add(): Adds a new product to the inventory.
-edit(): Edits details of an existing product.
-rem(): Removes a product from the inventory.
-list(): Lists all products in the inventory.
-receipt(): Generates a receipt for the purchased products.
##Main Function
-main(): Creates an instance of the Shopping class and calls the menu() method to start the program.
