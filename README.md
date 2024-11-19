# Restaurant Ordering System (C++)

## Overview

This project is a C++ application that simulates an online food ordering system. It allows customers to choose from a list of restaurants, view the menus, place orders, and make payments. The system also supports administrative functionality, where admins can manage restaurant details, modify menus, and view user orders.

The application uses Object-Oriented Programming (OOP) concepts like classes, inheritance, templates, and file handling.

## Features

### Customer Features:
- **Browse Restaurants**: Users can view a list of available restaurants with delivery charges and estimated delivery time.
- **View Menus**: For each selected restaurant, users can view the menu, select items, and place orders.
- **Cart Management**: Users can add, remove, and review items in their cart before proceeding to checkout.
- **Order Summary**: The total bill is calculated, including the delivery charge. Users can enter their details (name, address, and phone) for order processing.
- **User Details Saving**: The system saves user details and order summaries to a file (`users.txt`).

### Admin Features:
- **Modify Restaurant Details**: Admins can update the delivery charges and times of restaurants.
- **Modify Menu Items**: Admins can update item prices for a given restaurant.
- **View User Orders**: Admins can view order summaries and details of users, including the total bill and items ordered.

## Project Structure

The project consists of the following main components:

1. **Main Class**:
   - `MainClass`: Handles the customer-facing functionality like displaying restaurants, placing orders, and reviewing the cart.
   - **MenuItem** and **Restaurant**: Template classes that store and display menu items and restaurant details.
   - **Order Management**: Manages the customer's cart, total bill, and checkout process.

2. **Admin Page**:
   - `AdminPage`: Allows the admin to modify restaurant and menu details, view user orders, and update the order summaries.

3. **Files**:
   - `restaurants.txt`: Contains the list of restaurants, delivery charges, and delivery times.
   - `menus.txt`: Contains the list of menu items, their prices, and associated restaurant names.
   - `users.txt`: Stores user details and their order histories.

## Setup Instructions

### Prerequisites:
- A C++ compiler (such as `g++` or an IDE like Visual Studio, Code::Blocks, etc.)
- Standard C++ libraries (such as `iostream`, `fstream`, `vector`, `map`, etc.)

### Steps to Compile and Run:

1. **Clone the Repository**:
   Clone this repository to your local machine using the following command:

   ```bash
   git clone https://github.com/yourusername/restaurant-ordering-system.git
