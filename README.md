Task Management App with Team Collaboration
The Task Management App with Team Collaboration is a Ruby-based console application that enables teams to manage tasks efficiently, assign tasks to team members, and track task progress. It provides basic functionalities to handle user and task management, making it a lightweight yet effective solution for task organization.

Features
User Management

Add team members.
View a list of all team members.
Task Management

Create, view, update, and delete tasks.
Track the status of tasks (Pending, In Progress, Completed).
Task Assignment

Assign tasks to specific team members.
Persistent Storage

Data is saved in a JSON file (task_management_data.json) for persistence across sessions.
Prerequisites
Ruby (version 2.5 or above)
Basic understanding of Ruby programming.
How to Install and Run
Clone the Repository

bash
Copy code
git clone https://github.com/vijayleo31/task-management-app.git
cd task-management-app
Install Ruby If Ruby is not installed on your system, download and install it from Ruby's official site.

Run the Application Execute the application in your terminal:

bash
Copy code
ruby task_management_app.rb
Usage Guide
Main Menu
Upon running the app, you will see the following options:

Manage Users: Add or view team members.
Manage Tasks: Create, update, or delete tasks.
Assign Task to User: Assign a task to a specific team member.
View All Tasks: View the status, assignee, and details of all tasks.
Save and Exit: Save data and close the application.
User Management
Add team members by providing their name.
View the list of all users with their unique IDs.
Task Management
Create tasks by entering a title and description.
Update the status of tasks to Pending, In Progress, or Completed.
Delete tasks by specifying their ID.
Task Assignment
Assign a task to a user by providing the task ID and user ID.
View the assigned user when listing all tasks.
File Structure
bash
Copy code
task-management-app/
├── task_management_app.rb       # Main application file
├── task_management_data.json    # Persistent storage for users and tasks
└── README.md                    # Project documentation
Enhancements (Future Work)
Add deadlines and priorities to tasks.
Implement a web-based user interface using frameworks like Ruby on Rails.
Integrate email notifications for task assignments or updates.
Add reporting and analytics features for task tracking.
License
This project is licensed under the MIT License. You are free to modify and use the code as per the license terms.

Contributing
Contributions are welcome! If you have ideas for improvements, feel free to fork the repository, make changes, and create a pull request.

Acknowledgments
This project is designed as an educational tool to demonstrate how to build a task management system using Ruby. Special thanks to the Ruby community for providing extensive resources and documentation.

