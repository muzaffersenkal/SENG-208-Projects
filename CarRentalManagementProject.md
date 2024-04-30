# Car Rental Management

## Project Overview:
The Car Rental Management system is a Python-based application designed to help rental agencies manage their car rental operations efficiently. It provides functionalities for renting out cars, returning cars, managing inventory, tracking rental history, and generating rental invoices.

## Features:
1. **Authentication System:**
    - Only authorized users can access the system.
    - Username and password authentication.

2. **Car Rental Management:**
    - Rent out cars to customers.
    - Process returns for rented cars.
    - View available cars and their details (e.g., make, model, year, mileage).

3. **Inventory Management:**
    - Add new cars to the inventory.
    - Update existing car details like availability, rental price, etc.
    - Remove cars from the inventory.

4. **Rental History Tracking:**
    - Track rental history for each car (e.g., rental start date, return date, customer details).

5. **Invoice Generation:**
    - Generate invoices for completed rentals with detailed rental information and charges.

6. **Search Functionality:**
    - Search for cars by make, model, year, availability, or rental price.

7. **Display Cars:**
    - Display all cars in the inventory.
    - Display available cars for rent.

8. **Data:**
    - Store car and rental data in a file.

## Technologies Used:
- Python programming language.
- Standard libraries like `os`, `csv` for file handling and CSV file manipulation.
- Basic data structures like lists, dictionaries for storing and managing data.
- Command-line interface for user interaction.

## Project Structure:
1. **Main Module (`main.py`):**
    - Contains the main logic of the application.
    - Handles user authentication and menu navigation.

2. **Car Module (`car.py`):**
    - Functions related to car management (add, update, delete, search).

3. **Rental Module (`rental.py`):**
    - Functions to process car rentals and returns.

4. **Inventory Module (`inventory.py`):**
    - Functions to manage the car inventory.

5. **History Module (`history.py`):**
    - Functions to track rental history for each car.

6. **Invoice Module (`invoice.py`):**
    - Functions to generate rental invoices.

7. **Search Module (`search.py`):**
    - Functions to search for cars in the inventory.

8. **Display Module (`display.py`):**
    - Functions to display car details and rental information.

9. **Data Module (`data.py`):**
    - Handles data persistence (read/write data to files/database).

10. **Utils Module (`utils.py`):**
    - Utility functions used across modules.

## User Interaction:
- Upon running the application, users are prompted to log in with their username and password.
- After successful authentication, users are presented with a menu of options to perform various tasks.
- Users can navigate through the menu by entering corresponding numbers/options.

## Additional Considerations:
- Error handling: Implement robust error handling to handle unexpected inputs and scenarios gracefully.
- Logging: Implement logging to record significant events and errors for debugging and auditing purposes.
- Documentation: Include inline comments and documentation to make the codebase understandable and maintainable.
- OOP: use object-oriented programming principles for code organization and modularity.

## Conclusion:
The Command Line Car Rental Management system provides a reliable solution for rental agencies to streamline their rental operations. With its user-friendly interface and essential features, it helps agencies manage their car inventory, track rentals, and generate invoices efficiently.
