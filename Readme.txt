# To-Do List Manager

## Overview

The **To-Do List Manager** is a graphical user interface (GUI) application built in MATLAB. It allows users to efficiently organize, track, and manage tasks. With its user-friendly design and interactive features, the To-Do List Manager is an excellent tool for simplifying task management and improving productivity.

## Features

- **Add Tasks**: Users can input new tasks to their to-do list.
- **Optional Time Tracking**: Specify a completion time for tasks or leave it as "Not Specified."
- **Mark as Completed**: Update the status of tasks as "Completed."
- **Remove Tasks**: Delete individual tasks from the list.
- **Clear All**: Remove all tasks at once.
- **Dynamic Task List**: Automatically updates to reflect the current tasks and their statuses.
- **Interactive Dropdown**: Enables or disables time input based on user selection.

## How It Works

1. **Launch the Application**: Run the `TodoListGUI` function in MATLAB to open the GUI.
2. **Add Tasks**: Enter the task description in the input box. If needed, enable time input by selecting "Yes" from the dropdown, then specify a completion time.
3. **Manage Tasks**:
   - Mark tasks as completed using the "Mark Completed" button.
   - Remove specific tasks using the "Remove Task" button.
   - Clear the entire task list using the "Clear All" button.
4. **View Updates**: All actions dynamically update the task list displayed in the GUI.

## Installation and Usage

### Prerequisites

- MATLAB R2020a or later.

### Steps

1. Clone or download the repository from GitHub.
   ```bash
   git clone https://github.com/yourusername/todo-list-manager.git
   ```
2. Open MATLAB and navigate to the project folder.
3. Run the `TodoListGUI.m` file.
   ```matlab
   TodoListGUI
   ```
4. Start managing your tasks using the GUI.

## Code Explanation

- **Main Function**: `TodoListGUI` initializes the application and GUI components.
- **Storage Variables**:
  - `tasks`: Stores task descriptions.
  - `status`: Tracks completion status (0 = Pending, 1 = Completed).
  - `times`: Stores optional completion times.
- **GUI Components**:
  - Buttons (`uicontrol`): Handle task actions like adding, marking, or removing tasks.
  - Dropdown Menu: Enables or disables time input.
  - Listbox: Dynamically displays tasks with their statuses and times.
- **Callback Functions**:
  - `addTask`: Adds a new task to the list.
  - `updateTaskList`: Refreshes the task display.
  - `markCompleted`: Marks selected tasks as completed.
  - `removeTask`: Deletes selected tasks.
  - `clearAllTasks`: Clears all tasks from the list.

## Future Enhancements

- Add categories for tasks (e.g., Work, Personal).
- Include reminders or notifications.
- Save and load tasks from external files.
- Implement multi-user support with authentication.
- Introduce cloud synchronization for cross-device accessibility.

## Contributors

- **Aamir Ali**
- Chandan Sikarwar
- Devashish Mandal
- Abhishek Patel

## License

This project is licensed under the [MIT License](LICENSE).

---

**Enjoy managing your tasks with ease!**

