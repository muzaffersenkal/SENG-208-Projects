# Customer Relationship Management (CRM)

## Project Overview:
The Customer Relationship Management (CRM) system is a Python-based application designed to help businesses manage their interactions with current and potential customers. It provides basic functionalities for storing customer information, tracking interactions, and managing follow-ups.

## Features:
1. **Authentication System:**
    - Only authorized users can access the system.
    - Username and password authentication.

2. **Customer Management:**
    - Add new customers to the system.
    - Update existing customer details like name, contact information, etc.
    - Delete customers from the system.

3. **Interaction Tracking:**
    - Record interactions with customers (e.g., phone calls, emails, meetings).
    - Track the date and nature of interactions.

4. **Follow-up Management:**
    - Schedule follow-up tasks or reminders for each customer interaction.

5. **Search Functionality:**
    - Search for customers by name, contact information, or interaction details.

6. **Display Customers:**
    - Display all customers.
    - Display customers by interaction history or follow-up tasks.

7. **Data Store:**
    - Store customer data in a file

## Technologies Used:
- Python programming language.
- Standard libraries like `os`, `csv` or `pandas`  for file handling and CSV file manipulation.
- Basic data structures like lists, dictionaries for storing and managing data.
- Command-line interface for user interaction.

## Project Structure:
1. **Main Module (`main.py`):**
    - Contains the main logic of the application.
    - Handles user authentication and menu navigation.

2. **Customer Module (`customer.py`):**
    - Functions related to customer management (add, update, delete, search).

3. **Interaction Module (`interaction.py`):**
    - Functions to record and manage customer interactions.

4. **Follow-up Module (`followup.py`):**
    - Functions to schedule and manage follow-up tasks.

5. **Search Module (`search.py`):**
    - Functions to search for customers by name, contact information, or interaction details.

6. **Display Module (`display.py`):**
    - Functions to display customer information and interaction history.

7. **Data Module (`data.py`):**
    - Handles data persistence (read/write data to files/database).

8. **Utils Module (`utils.py`):**
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

