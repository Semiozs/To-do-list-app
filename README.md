# To-Do List Manager

This is a command-line Python to-do list manager that allows users to add, display, edit, and complete tasks. The tasks are stored in a text file (`todos.txt`), which is read and updated based on user commands.

## Features

- **Add Tasks**: Add new tasks to your to-do list.
- **Show Tasks**: View the current list of tasks, with each item numbered.
- **Edit Tasks**: Modify existing tasks by entering the task number.
- **Complete Tasks**: Mark a task as complete, which removes it from the list.
- **Persistent Storage**: Tasks are stored in a text file, so they persist between program runs.
- **Simple Command Interface**: Enter commands like `add`, `show`, `edit`, `complete`, and `exit` to interact with the program.

## How It Works

- The program reads the tasks from a `todos.txt` file and allows the user to interact with their to-do list.
- Users can add new tasks, view current tasks, edit existing ones, and mark tasks as complete, removing them from the list.
- The program continues running in a loop until the user enters the `exit` command.

## Commands

- `add <task>`: Adds a new task to the to-do list. Example: `add Go to the gym`
- `show`: Displays the current list of to-dos with each task numbered.
- `edit <number>`: Allows the user to edit a task based on its position in the list. Example: `edit 2`
- `complete <number>`: Marks a task as complete and removes it from the list. Example: `complete 1`
- `exit`: Exits the program.

### Example Usage

```bash
Tpe add, show, edit, complete or exit: add Buy groceries
Tpe add, show, edit, complete or exit: show
1- Go to the gym
2- Buy groceries
Tpe add, show, edit, complete or exit: complete 1
Todo Go to the gym was removed from the list
Tpe add, show, edit, complete or exit: exit
Bye!
