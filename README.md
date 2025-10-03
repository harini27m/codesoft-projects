Features

Add new tasks to the list

View all existing tasks with their status

Mark tasks as completed

Delete tasks from the list

Interactive console menu for easy navigation



---

How to Run

1. Ensure Python (version 3.x) is installed on your system.


2. Download the file todo_list.py.


3. Run the program using a terminal or IDE (e.g., VS Code):



python todo_list.py


---

Program Workflow

1. Data Storage

Tasks are stored in a list of dictionaries, where each dictionary represents a single task with two keys:

task → stores the task description

done → boolean value indicating completion status (True if completed, False if pending)




2. Interactive Menu

The program displays a menu with the following options:

1. Add Task


2. View Tasks


3. Mark Task as Done


4. Delete Task


5. Exit



Users select an option by entering the corresponding number.



3. Adding a Task

Users select option 1 to add a new task.

The program prompts for a task description and stores it in the list with done set to False.



4. Viewing Tasks

Users select option 2 to view all tasks.

Each task is displayed along with its status:

❌ Pending

✔️ Done




5. Marking a Task as Completed

Users select option 3 and enter the task number.

The program updates the task’s done status to True.



6. Deleting a Task

Users select option 4 and enter the task number.

The program removes the selected task from the list.



7. Exiting the Program

Users select option 5 to safely exit the program.





---

Example Menu

===== TO-DO LIST MENU =====
1. Add Task
2. View Tasks
3. Mark Task as Done
4. Delete Task
5. Exit


---

Skills Demonstrated

Python loops and conditional statements

Use of lists and dictionaries for data organization

Building an interactive console-based application
