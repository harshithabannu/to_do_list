# To-Do List Manager

## Overview

The To-Do List Manager is a Python application using Tkinter for the graphical user interface and SQLite for database management. It allows users to add, delete, and manage tasks, with persistent storage in a SQLite database.
Pink is having pink themed colors 
Blue is having blue themed colors 
## Features

- **Add Tasks:** Input tasks into the list and save them to the database.
- **Delete Tasks:** Remove individual tasks or clear the entire list.
- **View Tasks:** Display all tasks currently stored in the database.
- **Persistent Storage:** Tasks are saved in an SQLite database and loaded when the application starts.

## Requirements

- Python 3.x
- Tkinter
- SQLite3

## Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/todo-list-manager.git
    ```

2. **Navigate to the project directory:**
    ```sh
    cd todo-list-manager
    ```

3. **Ensure you have Python and Tkinter installed.**

## How to Run

1. **Run the script:**
    ```sh
    python main.py
    ```

2. **Interact with the Application:**
    - **Enter Task:** Type a task into the input field and click "Add Task" to add it to the list.
    - **Delete Task:** Select a task from the list and click "Delete Task" to remove it.
    - **Delete All Tasks:** Click "Delete All Tasks" to remove all tasks from the list.
    - **Exit:** Click "Exit" to close the application.

## User Interface

- **Header:** Displays the title of the application.
- **Task Entry Field:** Input field for entering new tasks.
- **Buttons:**
  - **Add Task:** Adds the entered task to the list.
  - **Delete Task:** Deletes the selected task from the list.
  - **Delete All Tasks:** Clears all tasks from the list.
  - **Exit:** Closes the application.
- **Task List:** Displays all tasks currently stored in the database.

## Customization

You can customize the application by modifying the following:

- **UI Colors:** Adjust the colors used in the UI elements by changing the hexadecimal color codes in the script.
- **Database Table:** Modify the SQLite table schema if you need to store additional information.

## Adding New Languages

The application currently supports English for all messages. To include support for additional languages, you would need to:

1. **Update the application code** to include translations and adjust the text accordingly.
2. **Modify the UI elements** to display text in the desired language.

## Example

When you run the application, you can:

1. Add a task:
    - Input: "Buy groceries"
    - After clicking "Add Task," "Buy groceries" will appear in the task list.

2. Delete a task:
    - Select "Buy groceries" from the list and click "Delete Task."

3. Clear all tasks:
    - Click "Delete All Tasks" to remove everything from the list.

4. Exit:
    - Click "Exit" to close the application.

## License

This project is licensed under the MIT License. See the LICENSE file for details.


## Acknowledgments

Thanks to the Tkinter and SQLite documentation for resources and support.
