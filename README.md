# To-Do List Application

This is a simple command-line To-Do List application written in Python. It allows users to manage their tasks effectively.

## Class: ToDoList

The `ToDoList` class is the core of this application. It has the following methods:

- `__init__(self)`: Initializes a new instance of the `ToDoList` class. It creates an empty list `self.tasks` to store tasks.

- `add_task(self, task)`: Adds a new task to the list. Each task is a dictionary with two keys: `"task"` for the task description and `"completed"` for the task status.

- `view_tasks(self)`: Prints all tasks in the list. If there are no tasks, it prints "No tasks found.".

- `mark_completed(self, task_index)`: Marks a task as completed. If the task index is invalid, it prints "Invalid task index.".

- `delete_task(self, task_index)`: Deletes a task from the list. If the task index is invalid, it prints "Invalid task index.".

## Function: main

The `main` function provides a command-line interface for the To-Do List application. It displays a menu with the following options:

1. Add Task
2. View Tasks
3. Mark Task as Completed
4. Delete Task
5. Quit

Users can select an option by entering the corresponding number. The application runs in a loop until the user chooses to quit.

## Usage

To run the application, simply execute the Python script from the command line:

```bash
python todo_list.py
```

This will start the application and display the menu to the user. Users can then interact with the application by choosing options from the menu and following the prompts.
```
