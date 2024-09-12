# Python Task Manager

## Overview

This Python Task Manager is a command-line application designed for practice. It allows users to manage their tasks and personal information through a simple menu interface. Users can view their data, add tasks, update task statuses, and view the current status of tasks.

## Features

- **User Authentication:** Sign up and log in to access the task manager.
- **View Data:** Display stored personal information.
- **Add Tasks:** Add new tasks with target dates.
- **Update Tasks:** Update the status of tasks (completed, ongoing, not started).
- **View Task Status:** Check the current status of tasks.

## How to Use

### Running the Application

1. Clone or download the repository.
2. Open a terminal and navigate to the directory containing the Python file.
3. Run the application using:
   ```bash
   python task_manager.py

User Interaction
Initial Setup:
- Upon running the program, you will be prompted to choose between being a new user or an existing user.
- 
New Users:
- If you choose to sign up as a new user (by typing 1), you will be asked to provide a username and password.
- Enter your personal information (name, address, age) when prompted.

Existing Users:
- bIf you choose to log in as an existing user (by typing 0), you will be asked to enter your username and password.
- If credentials are correct, you will be directed to the home page.

Home Page Options:
- View your data: Display the personal information stored for the user.
- Add task: Add new tasks with target dates.
- Update task status: Update the status of tasks (completed, ongoing, not started).
- View task status: View the current status of tasks.
- Exiting the Program:
  - You can choose to exit the program or return to the home page based on the options provided.

File Structure
task_manager.py: The main Python script for the task manager application.

Code Explanation
- home_page(username): Displays the main menu and handles user choices.
- exit_program(username): Manages exiting the program or returning to the home page.
- user_info(username, password): Collects and saves user personal information.
- view_data(username): Shows the stored user data.
- task_information(username): Allows users to add new tasks.
- task_update(username): Updates the status of existing tasks.
- task_update_viewer(username): Displays the status of tasks.
- login(): Handles the user login process.
- signup(): Manages the user signup process.

Dependencies
- Python 3.x
