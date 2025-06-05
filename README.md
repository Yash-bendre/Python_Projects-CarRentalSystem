# Car Rental System— Project Summary

__Overview__

The Car Rental System is a console-based Python application developed to simulate the operations of a car rental showroom. It provides a simple interface for managing cars available for rent, processing rentals and returns, and tracking customer transactions efficiently.
This project showcases core programming concepts such as data structures, user input handling, control flow, and modular design using functions. It is ideal for beginners seeking practical experience in building real-world applications.

__Key Features__

<u><em> Add Cars </em></u>: Allows showroom managers to add cars with unique IDs, including brand, model, and daily rental rate.

<u><em>Display Cars </em></u>: Lists all cars currently in the showroom along with their availability status.

<u><em>Rent a Car </em></u>: Customers can rent available cars by entering their details and rental duration; the system calculates total cost and marks the car as rented.

<u><em>Return a Car </em></u>: Supports car returns, calculates final payment based on actual rental days, and updates car availability.

<u><em>Data Management </em></u>: Uses Python dictionaries to maintain car details and rental status, ensuring efficient data retrieval and updates.

<u><em>Input Validation </em></u>: Includes basic error handling to ensure valid user inputs such as unique car IDs, numeric rates, and rental days.

__How It Works__

<u><em>Adding Cars </em></u>: The manager inputs a unique car ID along with brand, model, and daily rate. The car is stored in the system and marked as available.

<u><em>Displaying Cars </em></u>: The system lists all cars, showing their current rental status (available or rented).

<u><em>Renting a Car</em></u>: A customer provides their name, phone number, and selects a car by ID. If available, they specify rental days, and the system calculates and displays the rental cost.

<u><em>Returning a Car </em></u>: When returning, the customer provides the car ID and actual days used. The system computes the final payment and frees the car for future rentals.

__Technical Details__

<u><em>Language</em></u>: Python 3.x

<u><em>Data Structures</em></u>: Uses dictionaries (cars_showeroom and rented_cars) to store car and rental data.

<u><em>Functions</em></u>: Modular design with separate functions for adding cars, displaying cars, renting, and returning.

<u><em>Input Validation</em></u>: Ensures uniqueness of car IDs, numeric input for rates and days, and valid rental operations.

<u><em>User Interface</em></u>: Command-line based menu-driven interaction.

__Use Cases__

Small car rental businesses wanting a simple, low-cost rental management tool.

Beginners learning Python programming with practical examples.

Educational demonstrations of data handling, control flow, and user input management.
