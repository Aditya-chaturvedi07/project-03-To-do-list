# project-03-To-do-list
Name : Aditya Chaturvedi
Sap id : 590015425

Python To-Do List Application
A simple command-line To-Do List application built in Python. This project demonstrates the use of object-oriented programming to manage tasks efficiently. Users can add, view, mark tasks as completed, and delete tasks through an interactive menu.

Features
Add Tasks: Add new tasks to your to-do list.
View Tasks: See all tasks with their completion status.
Mark as Completed: Update a task's status to "completed."
Delete Tasks: Remove unwanted tasks from the list.
Interactive Menu: A simple text-based menu to navigate the application.
How It Works
Class: TodoList
The core logic is implemented in the TodoList class:

Attributes:
tasks: A list of tasks where each task is represented as a dictionary ({'task': str, 'completed': bool}).
Methods:
add_task(task): Adds a new task with its completion status set to False.
view_tasks(): Displays all tasks with their indexes and statuses (✓ for completed, ✗ for pending).
mark_completed(index): Marks a task as completed using its index.
delete_task(index): Deletes a task using its index.
Main Function
The main() function provides a menu-driven interface where users can:

Add tasks.
View tasks.
Mark a task as completed.
Delete a task.
Exit the application.
Running the Application
Clone or download the repository.
Ensure you have Python 3.x installed.
Run the script:
bash
Copy code
python todo_list.py
Use the menu to interact with your to-do list.
Example Interaction
markdown
Copy code
Options:
1. Add Task
2. View Tasks
3. Mark Task as Completed
4. Delete Task
5. Exit
Choose an option (1-5): 1
Enter the task: Learn Python
Added task: 'Learn Python'

Options:
1. Add Task
2. View Tasks
3. Mark Task as Completed
4. Delete Task
5. Exit
Choose an option (1-5): 2
To-Do List:
1. [✗] Learn Python
Requirements
Python 3.x (no external libraries required).
Customization
Feel free to extend this project by:

Adding due dates to tasks.
Saving tasks to a file for persistence.
Adding search or filtering capabilities.
