# Task List Manager

## Project Overview:
The Task List Manager (TLM) is a Python-based application designed to help users organize and manage their tasks effectively. It provides functionalities for adding, updating, deleting tasks, setting priorities, marking tasks as completed, and displaying tasks.

## Features:
1. **Authentication System:**
    - Only authorized users can access the system.
    - Username and password authentication.

2. **Task Management:**
    - Add new tasks to the task list.
    - Update existing task details like description, priority, due date, etc.
    - Delete tasks from the task list.

3. **Priority Setting:**
    - Set priority levels for tasks (e.g., high, medium, low).

4. **Marking Tasks as Completed:**
    - Mark tasks as completed once they are done.

5. **Search Functionality:**
    - Search for tasks by keywords, priority, due date, or status (completed/uncompleted).

6. **Display Tasks:**
    - Display all tasks.
    - Display tasks by priority, due date, or status.

7. **Data Persistence:**
    - Store task data in a file to ensure persistence across sessions.

## Technologies Used:
- Python programming language.
- Standard libraries like `os`, `csv` for file handling and CSV file manipulation.
- Basic data structures like lists, dictionaries for storing and managing data.
- Command-line interface for user interaction.

## Project Structure:
1. **Main Module (`main.py`):**
    - Contains the main logic of the application.
    - Handles user authentication and menu navigation.

2. **Task Module (`task.py`):**
    - Functions related to task management (add, update, delete, search).

3. **Priority Module (`priority.py`):**
    - Functions related to priority setting.

4. **Search Module (`search.py`):**
    - Functions to search for tasks by keywords, priority, due date, or status.

5. **Display Module (`display.py`):**
    - Functions to display tasks.

6. **Data Module (`data.py`):**
    - Handles data persistence (read/write data to files).

7. **Utils Module (`utils.py`):**
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
The Task List Manager provides a straightforward yet effective solution for users to organize and manage their tasks efficiently. With its user-friendly interface and essential features, it helps users prioritize tasks, track due dates, and stay productive.
