Car Rental System— Project Summary

Overview

The Car Rental System is a console-based Python application developed to simulate the operations of a car rental showroom. It provides a simple interface for managing cars available for rent, processing rentals and returns, and tracking customer transactions efficiently.
This project showcases core programming concepts such as data structures, user input handling, control flow, and modular design using functions. It is ideal for beginners seeking practical experience in building real-world applications.

Key Features

Add Cars: Allows showroom managers to add cars with unique IDs, including brand, model, and daily rental rate.

Display Cars: Lists all cars currently in the showroom along with their availability status.

Rent a Car: Customers can rent available cars by entering their details and rental duration; the system calculates total cost and marks the car as rented.

Return a Car: Supports car returns, calculates final payment based on actual rental days, and updates car availability.

Data Management: Uses Python dictionaries to maintain car details and rental status, ensuring efficient data retrieval and updates.

Input Validation: Includes basic error handling to ensure valid user inputs such as unique car IDs, numeric rates, and rental days.

How It Works

Adding Cars: The manager inputs a unique car ID along with brand, model, and daily rate. The car is stored in the system and marked as available.

Displaying Cars: The system lists all cars, showing their current rental status (available or rented).

Renting a Car: A customer provides their name, phone number, and selects a car by ID. If available, they specify rental days, and the system calculates and displays the rental cost.

Returning a Car: When returning, the customer provides the car ID and actual days used. The system computes the final payment and frees the car for future rentals.

Technical Details

Language: Python 3.x

Data Structures: Uses dictionaries (cars_showeroom and rented_cars) to store car and rental data.

Functions: Modular design with separate functions for adding cars, displaying cars, renting, and returning.

Input Validation: Ensures uniqueness of car IDs, numeric input for rates and days, and valid rental operations.

User Interface: Command-line based menu-driven interaction.

Use Cases

Small car rental businesses wanting a simple, low-cost rental management tool.

Beginners learning Python programming with practical examples.

Educational demonstrations of data handling, control flow, and user input management.
