Here's a `README.md` file template you can use for your Streamlit To-Do List application. This file will help others understand the purpose of your project, how to set it up, and how to use it.

```markdown
# To-Do List Application

This is a simple To-Do List application built using Streamlit and SQLite. The app allows users to add, update, and delete tasks. It uses SQLite for storing tasks and their statuses, and Streamlit for creating an interactive web interface.

## Features

- **Add New Tasks:** Input and save new tasks to the list.
- **View Tasks:** Display all tasks with their current status.
- **Update Task Status:** Modify the status of existing tasks.
- **Delete Tasks:** Remove tasks from the list.

## Requirements

- Python 3.6 or higher
- Streamlit
- SQLite (comes with Python’s standard library)

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Rameshcm581/streamlit-todo-list.git
   cd streamlit-todo-list
   ```

2. **Install Required Packages:**

   You can install the required packages using pip. It is recommended to use a virtual environment.

   ```bash
   pip install streamlit
   ```

## Usage

1. **Run the Application:**

   Navigate to the project directory and run the Streamlit app:

   ```bash
   streamlit run streamlit_todo_list.py
   ```

2. **Interact with the Application:**

   - **Add a New Task:** Enter a task name in the input field and click "Add Task."
   - **View Tasks:** See all current tasks listed with their statuses.
   - **Update Task Status:** Enter the Task ID and select a new status from the dropdown, then click "Update Status."
   - **Delete a Task:** Click the "Delete" button next to a task to remove it from the list.

## Code Overview

- **Database Setup:** Creates and manages the SQLite database and tasks table.
- **Functions:**
  - `add_task(task)`: Adds a new task to the database.
  - `view_tasks()`: Retrieves all tasks from the database.
  - `update_task(task_id, status)`: Updates the status of a specific task.
  - `delete_task(task_id)`: Deletes a specific task from the database.
- **Streamlit Interface:** Provides an interactive UI for managing tasks.

## Troubleshooting

- **Page Not Refreshing:** Ensure you are using a compatible version of Streamlit. If `st.experimental_rerun()` is not working, the app should still update based on state changes.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have improvements or bug fixes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or issues, feel free to contact me at [rameshc182003@gmail.com](mailto:rameshc182003@gmail.com).

